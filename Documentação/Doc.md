# Requisitos Funcionais

## Páginas Externas

- Slider explicativo
- Login
- Login Social
- Cadastro

## Páginas internas

- Home do Restaurante
- Detalhe do produto
- Adicionar ao carrinho
- Carrinho
- Finalizar o pedido
- Meus pedidos
- Perfil

## Rotas

- /app = slider inicial
- /login = login
- /cadastro = cadastro
- /restaurant/id:/home = home do restaurante
- /restaurant/id:/product = detalhes do produto
- /user/id:/cart = carrinho do usuário
- /user/id:/orders = meus pedidos
- /user/id:/profile = perfil do usuário
- /restaurant/id:/checkout = finalizar pedido

## Cadastros

- Usuários
  - Id (auto incremento)
  - Nome Completo (string)
  - CPF (string | number)
  - Email (string)
  - Senha (string)
  - Confirmar Senha (string)

- Restaurantes
  - Id (auto incremento)
  - Nome Fantasia (String)
  - Nome do Responsável (String)
  - CNPJ (String | number)
  - Email (string)
  - Endereço (string)
  - Faz entrega ? (boolean)
  
- Produtos
  - Id (auto incremento)
  - Nome (string)
  - Descrição (string)
  - Preço (number)
  - Imagem (string | Object)
  - Categoria (string)

- Categorias
  - id (auto incremento)
  - Nome (string)
  - Descrição (string)

- Mesas
  - Id (auto incremento)
  - Nome (string)
  - Status (string)

## Implementar Futuramente ou caso encontre um cliente

- Métodos de pagamento
- Implementação com cartões debito / credito (armazenamento seguro de dados)
- Banco de dados para comportar vários restaurantes e vários usuários
- Implementação de um sistema de notificações para todos os usuários
- Implementação de um sistema de reservas
- Leitura do Qr code para acesso do cardápio.
