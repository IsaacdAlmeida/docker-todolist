# TODO LIST COM DOCKER

## Introdução

O projeto tem uma aplicação desenvolvida em React pela Trybe, desenvolvi arquivos de configuração para cada parte da aplicação: back end, front end e testes! A aplicação está conteinerizada, foi feito a conexão entre os containeres e a orquestração com o compose da aplicação!

## Sumário

- [Introdução](#introdução)
- [Tecnologias utilizadas](#tecnologias-utilizada)
- [Aprendizados](#aprendizados)
- [Instruções para utilizar a aplicação](#instruções-para-utilizar-a-aplicação)
- [Disclaimer](#disclaimer)

## Tecnologias utilizada

**Back End:** Docker 

## Aprendizados

Fui capaz de criar imagens e configurá-las com docker-compose. Existem diversos comandos Docker com vários níveis de complexidade, o objetivo foi consolidar e fixar os conhecimentos com os principais comandos utilizados para subir um container com o docker-compose.

## Instruções para utilizar a aplicação

Para utilizar a aplicação você precisará ter o [Docker](https://docs.docker.com/engine/install/ubuntu/) instalado.

Após clonar o repositório, você precisará usar o comando `docker-compose up -d` para criar e iniciar o container. O comando deverá ser feito via terminal no diretório em que está o arquivo **docker-compose.yml**.

Você poderá utilizar o comando `npm start` para exibir a página da aplicação.

## Disclaimer

A aplicação em react foi toda desenvolvida pela Trybe, fui responsável por criar os arquivos e comandos para a montar o container utilizando docker!
