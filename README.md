# e-commerce

Escopo do Projeto de E-commerce com Django e Django Rest Framework

1. Visão Geral
Criar uma aplicação de e-commerce simples utilizando Django e Django Rest Framework com as seguintes funcionalidades:
- Gerenciamento de produtos e categorias via API.
- Visualização de produtos em uma página web utilizando templates.
- Administração de produtos para usuários autenticados.

 2. Funcionalidades Principais

2.1. Gerenciamento de Produtos e Categorias
  - Modelo de Categoria
  - Campos: `name` (nome da categoria).
  - Relação: Uma categoria pode ter vários produtos.

- Modelo de Produto
  - Campos: `name` (nome do produto), `description` (descrição), `price` (preço), `category` (referência à categoria).
  - Relação: Um produto pertence a uma categoria.

 2.2. API RESTful
- Endpoints para Categorias.
  - Listar todas as categorias.
  - Criar uma nova categoria.
  - Detalhar, atualizar e deletar uma categoria específica.

- Endpoints para Produtos
  - Listar todos os produtos.
  - Criar um novo produto.
  - Detalhar, atualizar e deletar um produto específico.

 2.3. Visualização de Produtos
- Página de Listagem de Produtos
  - Exibir uma lista de produtos com nome, descrição, preço e categoria.

- Página Detalhada do Produto
  - Exibir detalhes de um produto específico ao clicar no nome do produto na lista.

2.4. Autenticação e Autorização
- Administração de Produtos e Categorias
  - Apenas usuários autenticados e com permissões adequadas podem criar, atualizar ou deletar produtos e categorias.

4. Administração
- Usar o painel de administração do Django para gerenciar produtos e categorias.

 5. Autenticação e Segurança
- Implementar autenticação básica para acessar endpoints de criação, atualização e deleção.
- Utilizar o `django.contrib.auth` para gerenciar usuários e permissões.

Conclusão
Esse escopo abrange a criação de um e-commerce básico com Django e DRF, proporcionando uma base sólida para futuras expansões, como carrinho de compras e checkout.
