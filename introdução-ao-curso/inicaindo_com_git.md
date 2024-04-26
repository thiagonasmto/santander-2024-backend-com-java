## Sobre o Git

O projeto do núcleo (kernel) do Linux, que é open source, começa a utilizar o BitKeeper, um DVCS proprietário;

Após conflitos com a comunidade, o BitKeeper rescinde a licença gratuita. O que leva a Linux Torvald, o criador do Linux, e sua equipe desenvolverem sua própria ferramenta, o Git.

## Instalação do Git

## Instalação no Windows

1. Acesse o site oficial do Git em [git-scm.com](https://git-scm.com/).
2. Clique no botão de download para Windows.
3. Após o download, execute o instalador.
4. Siga as instruções do instalador, aceitando os padrões, a menos que você tenha uma razão específica para mudar.

## Instalação no macOS

1. No macOS, o Git pode ser instalado de várias maneiras. A mais simples é usando o Homebrew.
2. Se você não tiver o Homebrew instalado, acesse [brew.sh](https://brew.sh/) e siga as instruções para instalá-lo.
3. Após instalar o Homebrew, abra o Terminal e execute o comando:
    ```
    brew install git
    ```

## Instalação no Linux (Ubuntu/Debian)

1. Abra o Terminal.
2. Execute o seguinte comando para instalar o Git:
    ```
    sudo apt-get update
    sudo apt-get install git
    ```

## Verificando a Instalação

Para verificar se o Git foi instalado corretamente, abra o Terminal ou Prompt de Comando e execute o seguinte comando:

```
git --version
```

Se a instalação for bem-sucedida, você verá a versão do Git que foi instalada.

## Configuração Inicial (opcional)

Depois de instalar o Git, é uma boa prática configurar seu nome de usuário e endereço de e-mail. Isso é usado em cada commit que você faz. Você pode configurá-los com os seguintes comandos:

```
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

Substitua "Seu Nome" pelo seu nome e "seuemail@example.com" pelo seu endereço de e-mail.