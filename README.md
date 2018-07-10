------------------------------------------PROJETO------------------------------------------------

PizzaMia - Sistema de pedidos on-line

Projeto desenvolvido por: Adriana Alves e Deiziane Buganti, com Node js, Express e MongoDb

Trabalho final da disciplina: Desenvolvimento Web com JavaScript

Professor: Luiz Pedro Petroski

------------------------------------------LOGIN---------------------------------------------------

Sistema permite a escolha de dois perfis diferentes, e caso o usuário não conste no banco de dados, ele será criado, ao contrário, fará o login. Usuários para teste:

CLIENTE

	Nome: Adriana Alves
	Senha: 12345

	Nome: Deiziane Buganti
	Senha: 56789
  
ADMIN

	Nome: admin
	Senha: admin
	
------------------------------------------PERFIS------------------------------------------------------

Sistema de pedidos com dois perfis distintos:

*Cliente = pode criar pedidos, editar e excluir seus pedidos, porém não pode alterar o status dos mesmos.

*Admin = pode visualizar todos os clientes cadastrados e listar seus pedidos, mas não pode alterá-los ou excluí-los. Apenas pode alterar o status do pedido.

------------------------------------------INSTALANDO O SISTEMS------------------------------------------

Passos para instalação do sistema:

*Instalação:

	$ npm install -g express

*Esqueleto do projeto:

	$ express pizzaria --ejs
	$ cd pizzaria
	$ npm install

*Substituir todas as pastas

*Atualiar modulos:

	$ npm install

*Módulos adicionais:

	$ npm install --save cookie-parser
	$ npm install --save express-session
	$ npm install --save body-parser
	$ npm install bootsstrap -save
	$ npm install -g @angular/cli@latest

*Iniciar MongoDB

	Colocar nas variaveis Path do windows o caminho da pasta Bin do MongoDb instalado no seu computador
	Entrar na pasta onde está instalado:
	Ex: C:\Program Files\MongoDB\Server\3.6\bin
	Iniciar o Mongoose
	$ mongod --dbpath=c:\pizzaria\db (troque pelo caminho salvo o projeto)

*Conectar ao MongoDB

	Abra outro prompt de comando e digite
	$ mongo
	Para listar as bases de dados, digite
	$ show databases
	Para selecionar o banco do projeto
	$ use pizzamia
	Para visualizar as collections, digite
	$ show collections
	Pra apagar collection
	$ db.usuarios.drop()

*Iniciar projeto

	Entre na pasta e digite:
	$ node app.js
	ou
	$ npm start
