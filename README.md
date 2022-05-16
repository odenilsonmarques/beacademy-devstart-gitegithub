# beacademy-devstart-gitegithub

O propósito desse material é demostrar os comandos 
utilizados por um dos principais controladores
de versões do mercado de tecnologia, o Git / Github.

## Autor

- [@odenilsomarques](https://www.github.com/odenilsonmarques)


## Definições

## git: 
Responsável por permitir o gerenciamento de diferenntes 
versoes de um documento / projeto de forma local.

## github: 
Plataforma web onde será armazenado as versoes dos 
projetos feito pelo git de forma public ou não..

## comandos

## Para saber a versão do git, usá o comando
git --version 

## Configurando informações do usuario
1º git config --global user.name "nome do usuario"

2º  git config --global user.email "email do usuario"

3º  git config --global core.editor nome do editor usado

## Acessando uma informações por vez do usuario
git config user.name

## Acessando todas as informações do usuario em o unico comando
git config --list

## Branchs
git branch:  Exibe a BRANCH que o usuário está utilizando

git checkout -b feature/nome da branch: Cria uma nova BRANCH e logo depois muda  para branch criada

git checkout feature/nome da branch: Alterna de BRANCH

git branch -d feature/nome da branch: Deleta a BRANCH

