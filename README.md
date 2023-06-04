# Comandos GIT 📖
Curso GIT e GIT-HUB 
link: https://www.udemy.com/course/git-e-github-para-iniciantes

Comando para inicializar um repositorio
```
git init
```
Exibe as condições do diretório de trabalho e da área de staging
```
git status
```
Comando para explorar o historico de commits de um repositorio
```
git log
```
Comando para adicionar um determinado arquivo para ser commitado
```
git add nome do arquivo ou . para adicionar tudo
```
Comando para fazer o commit
```
git commit -m "alguma mensagem"
```
Comando para enviar o conteúdo do repositório local para um repositório remoto
```
git push origin nome da branch remoto
```
Comando para altera uma URL do repositório remoto existente
```
git remote set-url "link da url"
```
Comando para ver o repositório remoto
```
git remote -v
```
Comando para mostrar o diretorio(Linux)
```
ls -la
```
Comando para clonar um repositorio
```
git clone "link do repositorio remoto" -clone
```
Comando para criar um branch
```
git checkout -b "nome da branch"
```
Comando para mostrar os branch existentes
```
git branch
```
Comando para trocar de branch
```
git checkout "nome da branch"
```
Comando para deletar um branch do repositorio local
```
git branch -D "nome da branch"
```
Comando para deletar um branch do repositorio remoto
```
git push origin :nome da branch
```
Comando para levar um codigo de uma branch para outra
```
git merge "nome da branch origin"
```
Comando para mergear não mantendo o historico
```
git rebase "nome da branch origin"
```
Arquivo gitignore para ignorar arquivos que não deseja commitar ou salvar no git
```
arquivo .gitignore
```
Comando para guardar modificações sem commitar com git stash
```
git stash
```
Comando para voltar as modificações que foram salvas na stash
```
git stash apply
```
Mostrar lista de git stash
```
git stash list
```
Limpar tudo que esta no stash
```
git stash clear
```
Comando para colocar tag 
```
git tag -a suaversão -m "mensagem"
```
Comando para subir as tag
```
git push origin master --tags
```
Comando para reverter alterações do commit
```
git revert "serial do commit"
```
Comando para ver um commit
```
git show "serial do commit"
```

