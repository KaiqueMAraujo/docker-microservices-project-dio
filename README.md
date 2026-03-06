Docker Microservices Project

Projeto prático utilizando Docker para simular um ambiente de Microsserviços, baseado no laboratório apresentado por Toshiro Shibakita na plataforma Digital Innovation One.

O objetivo deste projeto é demonstrar como containers podem ser utilizados para criar aplicações isoladas, escaláveis e independentes da infraestrutura.

Tecnologias utilizadas

Docker

NGINX

MySQL

PHP

Linux

Git e GitHub

Arquitetura da aplicação

A arquitetura do projeto segue o seguinte fluxo:

Cliente
↓
NGINX (Proxy reverso)
↓
Aplicação PHP em container
↓
Banco de dados MySQL

Essa arquitetura permite que cada serviço seja executado de forma independente dentro de containers.

Estrutura do projeto

docker-microservices
│
├── dockerfile
├── index.php
├── banco.sql
├── nginx.conf
└── README.md

Descrição dos arquivos:

dockerfile
Responsável por criar a imagem Docker da aplicação.

index.php
Aplicação web simples em PHP utilizada para testes.

banco.sql
Script responsável por criar o banco de dados e suas tabelas.

nginx.conf
Arquivo de configuração do servidor NGINX que atua como proxy.

README.md
Documentação do projeto.
