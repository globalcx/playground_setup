# Setup de Projeto em Python com Visual Studio Code no Debian 12

## Sumário
### 1. Instalação do Pythony
### 2. Instalação e Configuração VSCode
### 2. Instação e Configuração do Git Bash
### 3. Instalação e Configuração do GitHub
### 5. Criação do Primeiro Projeto com Chave SSH no GitHub

## 1. Instalação do Python

O Python vem instalado por padrão no Debian 12, assim como em outras distros Linux. Para verificar a versão do Python instalada em seu sistema operacional, digite

    python --version


## 2. Instação e Configuração do VSCode

Para instalar o Visual Studio Code no Debian, há diversas formas, cofnorme abaixo.

**Primeira forma:**
    Entre na loja de aplicativos do Debian e busque por Visual Studio Code. Daí é só clicar em instalar, assim como no Microsof Windows.


**Segunda forma:**

a. [Entre no link] 
    (https://code.visualstudio.com/)
    
Escolha baixar a versão .deb. 

 b. O arquivo será baixado para a pasta Downloads. Entre na pasta e abra um terminal. Espera-se que o usuário saiba navegar pelos directórios do Debian, tanto na forma visual quando via terminal. Caso necessário, sugere-se realizar um trainamento básico de Linux Debian.

c. Digita 
    
    sudo dpkg -i code_1.93.1-1726079302_amd64.deb. 
    
A versão do VSCode será aquela que o usuaŕio baixar. Este é apenas um exemplo. Trocando a ersão, funcionará perfeitamente.


Há outras formas de instalar a ferramenta no Debian 12, como uso do isntalador de pacote Snap, mas as duas acima já são suficientes.

**Extensões**

O Visual Studo Code possui uma loja de extensões abuntantes, portanto fica a critério do usuário instalar a que lhe convier. No entanto, sugiro duas extensões muito usadas no mercado de dados. Veja a seguir.

- Python

    Esta extensão é, provavelmente uma das mais baixadas. E é necessária para o projeto.

- Material Icon Theme

    Esta extensão torna o código mais bonito e mais visual.



**Arquivo README.md**

O arquivo README.md é desenvolvido na linguagem Markdown e é extremamente útil para o usuário se orientar na compreensão e setup de um projeto baseado em um repositório já existem, ou em projeto empresarial amplamente usado. Ele serve como um tutorial passo-a-passo que facilita e agiliza o processo de configuração dos projetos.

Para criar o **README.md** é muito simples. Basta criar um arquivo novo no VSCode com a extensão md, abrir o arquivo e editar. A linguagem é flexível e rica em recursos, permitindo links para páginas web e imagens.


## 2. Instação e Configuração do Git Bash

Para instalar o Git no Debian é muito simples. Basta abrir um terminal e digitar

    sudo apt install git

**Comandos git básicos - para projetos já existens**

- Verficiar versão do git instalada

        git --version

- Versionar o projeto
    
        git init

- Verificar se o git está no projeto (comando bash)

        ls -ll

- Adicionar aquivos ao git

    git add + nome do arquivo. Exemplo:

        git add main.py

- Salvar no repositório do Git

    git commit -m + "mensagem_de_commit".  Exemplo:

        git commit -m "Meu primeiro commit"

É possível que no commit não seja bem-sucedido devido ao fato de a conta local não estar conectada ao Github. Neste caso, deve-se primeiro conectar-se à conta do Github, como se segue...

- Adicionar usuário ao GitHub

        git config --global user.e-mail "seuemail@gmail.com"   
    Onde: "seuemail.@gmail.com" é o e-mail do usuário do GitHub.

        git config --global user.name "João de Barro"

    Onde: "João de Barros" é seu nome ou nome do projeto.

- Em seguida, já é possível fazer o commit com o comando 

        git commit -m "Sua mensagem de Commit"

- Mostrar log / histórico de commits

        git log














[Link para website](https://lunadata.com.br). Ou

![Imagem](https://miro.medium.com/v2/resize:fit:640/format:webp/1*06aeJgtJ4c4mUQOG3qIbCw.png)




*talico*

**Negrito**

- Elemento de lista 1
- Elemento de lsita 2

1) Elemento numerado 1
2) Elemento numerado 2

[Link para site Lunadata] (https://www.lunadata.com.br)

![Link para imagem do Google] (https://images.app.goo.gl/rVqk3xbLAa5utgEJ9)