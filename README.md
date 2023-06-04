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
Comando para explorar o historico de um repositorio
```
git log
```
Comando para adicionar um origin para o repositório se não existe nenhum
```
git add
```
Comando para enviar o conteúdo do repositório local para um repositório remoto
```
git push origin
```
Comando para altera uma URL do repositório remoto existente
```
git remote set-url 
```
Comando para ver o repositório remoto
```
git remote -v
```
Comando para fazer o commit
```
git commit -m ""
```
Comando para mostrar o diretorio
```
ls -la
```
Comando para clonar repositorio
```
g clone "link/chave" github-"nome"-clone
```
Comando para criar um branch
```
git checkout --b "nome"
```
Comando para mostrar os branch existentes
```
git branch
```
Comando para trocar de branch
```
git checkout "nome"
```
Comando para deletar um branch
```
git branch -D "nome"
```
Comando para criar merge
```
git merge "branch"
```
Comando para criar rebase
```
git rebase "branch"
```
Comando gitignore
```
vi .gitignore
```

Comando para guardar modificações sem commitar com git stash
```
git stash
```
Para aplicar as mudanças com stash
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
git show
```
Comando para apagar tags e branches repositorio remoto
```
git push origin:
```