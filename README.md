# 🎥 Replica Netflix 🎥
 <p align="center"><img alt="Status Concluído" src="https://img.shields.io/badge/STATUS-CONCLU%C3%8DDO-brightgreen">

## 💻 Sobre o projeto
Esse projeto foi desenvolvido com o Django

Reproduzir a replica da Netflix, que permite o usuário criar conta, fazer login, logout, editar perfil, escolher filmes e assitir episódios.

A nossa home page principal, começa com a requisição para acessar a plataforma, e caso tenha uma conta direciona para logar, caso contrário redireciona para criar seu cadastro.

Cada usuário tem uma página de perfil adaptada, com base no filmes que o usuário acessou. Temos um carrossel com os filmes em alta, novos e assistindo, barra de pesquisa de filmes.

O diretório principal foi a pasta Filme, nela contém as migrações, templates, rotas, modelos, formulários, admin e urls.

Para o gerenciamento de banco de dados online usei o PostgreSQL no Heroku, garantindo que seus dados esteja seguros.
Para configurar a conexão com o banco de dados, importei a biblioteca dj-database-url.

Para os arquivos de mídia, usei a plataforma cloudinary que hospeda e processa mídias digitais.

Hospedado no Heroku, [https://replica-netflix-abc673e7841c.herokuapp.com](https://replica-netflix-abc673e7841c.herokuapp.com/)  


## 🛠 Tecnologias

<p>Django</p>
<p>Heroku</p>
<p>Postgresql</p>
<p>Cloudinary</p>
