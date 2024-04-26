# Comandos Básicos do Git

## git clone

O comando `git clone` é usado para criar uma cópia local de um repositório remoto. Isso é útil quando você deseja começar a colaborar em um projeto existente ou quando deseja trabalhar em uma cópia de um repositório em seu próprio sistema.

### Sintaxe:
```
git clone <URL_do_repositório>
```

### Exemplo:
```
git clone https://github.com/usuario/nome-do-repositorio.git
```

Isso criará uma cópia do repositório `nome-do-repositorio` em sua máquina local.

## git add e git commit

O comando `git add` é usado para adicionar alterações feitas em arquivos ao índice (staging area) para serem incluídas no próximo commit. O comando `git commit` é usado para salvar as alterações confirmadas no repositório.

### Sintaxe:
```
git add <nome_do_arquivo>
git commit -m "Mensagem de commit"
```

### Exemplo:
```
git add arquivo.txt
git commit -m "Adicionando arquivo.txt"
```

Isso adicionará o arquivo `arquivo.txt` ao índice e o commitará com a mensagem "Adicionando arquivo.txt".

## git pull

O comando `git pull` é usado para recuperar as alterações do repositório remoto e mesclá-las com o seu repositório local. Isso é útil quando você deseja atualizar seu repositório local com as alterações feitas por outros colaboradores.

### Sintaxe:
```
git pull
```

Este comando recuperará as alterações do repositório remoto e mesclará automaticamente com o seu repositório local.

## git push

O comando `git push` é usado para enviar as alterações confirmadas do seu repositório local para um repositório remoto.

### Sintaxe:
```
git push <nome_do_repositório_remoto> <nome_do_branch_local>
```

### Exemplo:
```
git push origin main
```

Isso enviará as alterações confirmadas do branch `main` do seu repositório local para o repositório remoto chamado `origin`.