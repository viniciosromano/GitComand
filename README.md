# Comandos git

## Inserir um repositorio no GitHub
git init

git add .

git commit -m "primeiro commit"

git branch -M main

git remote add origin git@github.com:{user}/{repository}.git

git remote add origin https://github.com/{user}/{repository}.git

git push origin main

## Controle de alterações
git status

git log

## Pegar um repositorio presente no GitHub
git init

git clone {url}

## Configurar Email e User
git config --global user.name "fiap"

git config --global user.email "RM93018@fiap.com.br"

## Adicionar o git em um repositorio existente
git init

git remote add origin git@github.com:{user}/{repository}.git

git remote add origin https://github.com/{user}/{repository}.git

## Ignorando arquivos
Criar um arquivo .gitignore

Conteudo da pasta:

{pasta}

{pasta}/*

{arquivo}

Site para ignorar arquivos do java, ecplise, visualStudioCode https://www.toptal.com/developers/gitignore/
