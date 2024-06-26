# Aplicação CRUD Django com PostgreSQL

Este projeto implementa uma aplicação CRUD (Create, Read, Update, Delete) simples usando Django e PostgreSQL.

## Funcionalidades
- **Criar**: Adicionar novos livros ao sistema.
- **Ler**: Visualizar detalhes de cada livro cadastrado.
- **Atualizar**: Atualizar informações de livros existentes.
- **Deletar**: Remover livros do sistema.

## Pré-requisitos
- Python 3.x
- Django 3.x
- PostgreSQL

## Instalação
**Clone o repositório:**</br>
   bash> </br>
   <code>git clone https://github.com/seu-usuario/crud_postgres.git</code></br>
   <code>cd crud_postgres</code>

**Instale as dependências:**</br>
<code>pip install -r requirements.txt</code></br>

**Configuração do Banco de Dados:**</br>
Certifique-se de ter o PostgreSQL instalado e configurado corretamente.</br>
Crie um banco de dados para o projeto.</br>
**Configuração do Django:**
Renomeie o arquivo env.example para .env e configure suas variáveis de ambiente.</br>
**Aplique as migrações do Django para criar as tabelas no banco de dados:**
<code>python manage.py migrate</code></br>

**Execute o Servidor de Desenvolvimento:**</br>
<code>python manage.py runserver</code>

**Acesso à Aplicação:**</br>
Acesse a aplicação em http://localhost:8000/books/.</br>
**Estrutura do Projeto**</br>
books/: Aplicação Django para gerenciar os livros.</br>
crud_postgres/: Configurações principais do projeto Django.</br>
templates/: Templates HTML para as páginas da aplicação.</br>
**Uso**</br>
Adicionar Livro: Clique em “Add Book” na página inicial para adicionar um novo livro.</br>
Editar Livro: Clique no link “Edit” ao lado de cada livro para editar suas informações.</br>
Excluir Livro: Clique no link “Delete” ao lado de cada livro para removê-lo do sistema.</br>
**Contribuição**</br>
Sinta-se à vontade para contribuir com o projeto. 
