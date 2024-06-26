# Django CRUD Application with PostgreSQL
 This project implements a simple CRUD (Create, Read, Update, Delete) application using Django and PostgreSQL.

<h1>Features</h1>
Create: Adicionar novos livros ao sistema.
Read: Visualizar detalhes de cada livro cadastrado.
Update: Atualizar informações de livros existentes.
Delete: Remover livros do sistema.
<h1>Pré-requisitos</h1>
Python 3.x
Django 3.x
PostgreSQL
<h1>Instalação</h1>
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/crud_postgres.git
cd crud_postgres
Instale as dependências:

Copiar código
pip install -r requirements.txt
Configuração do Banco de Dados:

Certifique-se de ter o PostgreSQL instalado e configurado corretamente.
Crie um banco de dados para o projeto.
Configuração do Django:

Renomeie o arquivo env.example para .env e configure suas variáveis de ambiente.

Aplique as migrações do Django para criar as tabelas no banco de dados:

Copiar código
python manage.py migrate
Executar o Servidor de Desenvolvimento:

Copiar código
python manage.py runserver
Acesso à Aplicação:

Acesse a aplicação em http://localhost:8000/books/.

<h1>Estrutura do Projeto</h1>
books/: Aplicação Django para gerenciar os livros.
crud_postgres/: Configurações principais do projeto Django.
templates/: Templates HTML para as páginas da aplicação.
<h1>Uso</h1>
Adicionar Livro: Clique em "Add Book" na página inicial para adicionar um novo livro.
Editar Livro: Clique no link "Edit" ao lado de cada livro para editar suas informações.
Excluir Livro: Clique no link "Delete" ao lado de cada livro para removê-lo do sistema.
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou relatar problemas.

Autores
Tarcisio Reinert Neto 
