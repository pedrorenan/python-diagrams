<p  align="center">
<img  alt="GitHub language count"  src="https://img.shields.io/github/languages/count/pedrorenan/python-diagrams">
<img  alt="Repository size"  src="https://img.shields.io/github/repo-size/pedrorenan/python-diagrams">
<a  href="https://www.twitter.com/pedrorenan/">
<img  alt="Siga no Twitter"  src="https://img.shields.io/twitter/url?url=https://github.com/pedrorenan/python-diagrams">
</a>
<a  href="https://github.com/tgmarinho/README-ecoleta/commits/master">
<img  alt="GitHub last commit"  src="https://img.shields.io/github/last-commit/pedrorenan/python-diagrams">
</a>
<img  alt="License"  src="https://img.shields.io/badge/license-MIT-brightgreen">
<a  href="https://github.com/pedrorenan/python-diagrams/stargazers">
<img  alt="Stargazers"  src="https://img.shields.io/github/stars/pedrorenan/python-diagrams?style=social">
</a>
</p>
<!--ts-->

*  [🇧🇷🇵🇹Português](#-português)

*  [🌎English](#-english)

<!--te-->

# 🇧🇷🇵🇹Português

<h3  align="center">

Um exemplo de como utilizar o Python Diagrams para gerar diagramas de arquitetura de sistemas em nuvem, bonitos, com poucas linhas de código e usando Remote-Containers do VSCode.

</h3>

Tabela de conteúdos

=================

<!--ts-->

*  [Sobre o projeto](#-sobre-o-projeto)

*  [Funcionalidades](#-funcionalidades)

*  [Como executar o projeto](#-como-executar-o-projeto)

*  [Pré-requisitos](#pré-requisitos)

*  [Como contribuir no projeto](#-como-contribuir-no-projeto)

*  [Autor](#-autor)

*  [Licença](#-licença)

<!--te-->
  

## 💻 Sobre o projeto


A idéia surgiu da leitura desse artigo aqui sobre ["Como criar belos diagramas de arquitetura usando Python"](https://towardsdatascience.com/create-beautiful-architecture-diagrams-with-python-7792a1485f97). Existem várias ferramentas visuais para fazer isso, mas geralmente elas não fazem só diagramas de arquitetura e se são boas, não são gratuítas.

  
Achei essa solução bem interessante e testei com as instruções do artigo acima e também verificando a [documentação oficial do Diagrams](https://diagrams.mingrammer.com/docs/getting-started/installation). O incremento que fiz foi fazer o projeto utilizando os recursos da extensão [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) do [VSCode](https://code.visualstudio.com/download).

  
---


## ⚙️ Funcionalidades

  
Gera diagramas de arquitetura de sistemas em nuvem usando Python.

---


## 🚀 Como executar o projeto

  
  
### Pré-requisitos

 

Desde que você tenha instalado no seu computador o [VSCode](https://code.visualstudio.com/download) e a extensão [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers), não tem pré-requisito algum, é só rodar o projeto! 😲

  

Instruções:

  
```bash
# Clone este repositório
$ git clone https://github.com/pedrorenan/python-diagrams.git

# Acesse a pasta do projeto no terminal/cmd
$ cd python-diagrams

# Abra o projeto com o VSCode
$ code .
```

Quando o [VSCode](https://code.visualstudio.com/download) abrir você verá uma mensagem informando que foram detectadas as configurações necessárias para que a extensão [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) faça a mágica acontecer.



<p  align="center">

<img  alt="Remote Containers Dialog"  title="Remote Containers Dialog"  src="./assets/python-diagrams-remote-containers-dialog.png"  width="400px">

</p>

  

Clique em "Reopen in Container". O [VSCode](https://code.visualstudio.com/download) vai reiniciar e é só aguardar o ambiente ficar pronto para você. Pode demorar um pouco na primeira vez se você nunca tiver feito o download dos containers necesários 🕐. Mas vale a pena!

  

<p  align="center">

<img  alt="Terminal inside Container"  title="Terminal inside Container"  src="./assets/python-diagrams-terminal-inside-vscode.png"  width="400px">

</p>

  

Quando finalizar, você terá um terminal dentro do [VSCode](https://code.visualstudio.com/download) que já está dentro do container. Tudo integrado! Tipo [Inception](https://www.imdb.com/title/tt1375666/) mesmo 🍿.

  

💡 Tudo que você executar nesse terminal será executado dentro do container apenas!

  

Então vamos ao útlimo passo:

  

```bash
# Gere os diagramas
$ python diagram.py
```

Os diagramas serão gerados em uma pasta chamada "diagrams", mas você pode alterar isso se quiser 😀. Olha como fica bonitão:

  

<p  align="center">

<img  alt="Running the project"  title="Running the project"  src="./assets/python-diagrams-running.png"  width="800px">

</p>

  

>Eu escrevi um post sobre [VSCode](https://code.visualstudio.com/download) e [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers), se quiser ler um pouco mais sobre o assunto, é só acessar ["Em busca da independência para o ambiente de desenvolvimento"](https://medium.com/@pedrorenan/em-busca-da-independ%C3%AAncia-para-o-ambiente-de-desenvolvimento-2adc22f6f250).

  
  

## 💪 Como contribuir no projeto

1. Faça um **fork** do projeto.

2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`

3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`

4. Envie as suas alterações: `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## 🦸 Autor 

[![Twitter Badge](https://img.shields.io/badge/-@pedrorenan-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/pedrorenan)](https://twitter.com/pedrorenan) [![Linkedin Badge](https://img.shields.io/badge/-Pedro%20Renan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/opedrorenan/)](https://www.linkedin.com/in/opedrorenan/) [![Gmail Badge](https://img.shields.io/badge/-pedrorenan@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:pedrorenan@gmail.com)](mailto:pedrorenan@gmail.com)

  
---
  

## 📝 Licença

 
Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Pedro Renan 👋🏽 [Entre em contato!](https://www.linkedin.com/in/opedrorenan/)


---

# 🌎 English

<h3  align="center">

A Python Diagrams example to generate cloud systems architecture diagrams, beautiful, typing few code lines and using Remote-Containers VSCode extension.

</h3>

  
Table of content

=================

<!--ts-->

*  [About](#-about)

*  [Features](#-features)

*  [How it works](#-how-it-works)

*  [Prerequisites](#prerequisites)

*  [How to contribute](#-how-to-contribute)

*  [Author](#-author)

*  [License](#-license)

<!--te-->

  
  

## 💻 About

The idea came from reading this article here on ["Create Beautiful Architecture Diagrams with Python"](https://towardsdatascience.com/create-beautiful-architecture-diagrams-with-python-7792a1485f97). There are a number of visual tools to do this, but generally they don't just make architectural diagrams and if they are good, they are not free.

I think this solution is very interesting and tested it with the instructions in the article above and also checking the official Diagrams documentation. The increment I did was to make the project using the resources of the [VSCode](https://code.visualstudio.com/download) and [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.  

---

## ⚙️ Features

Generates architecture diagrams of cloud systems using Python.

---


## 🚀 How it works



### Prerequisites

If you have [VSCode](https://code.visualstudio.com/download) and the [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension installed on your computer, there is no prerequisite, just run the project! 😲

Steps:

```bash
# Clone this repository
$ git clone https://github.com/pedrorenan/python-diagrams.git

# Open the project folder in the terminal
$ cd python-diagrams

# Open the project with VSCode
$ code .
```
  
When [VSCode](https://code.visualstudio.com/download)  opens, you will see a message stating that the necessary settings have been detected for the[Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension to make the magic happen.

<p  align="center">

<img  alt="Remote Containers Dialog"  title="Remote Containers Dialog"  src="./assets/python-diagrams-remote-containers-dialog.png"  width="400px">

</p>
  

Click on “Reopen in Container”. The[VSCode](https://code.visualstudio.com/download)  will restart and just wait for the environment to be ready for you. It may take a while the first time if you have never downloaded the necessary containers 🕐. But it's worth!


<p  align="center">

<img  alt="Terminal inside Container"  title="Terminal inside Container"  src="./assets/python-diagrams-terminal-inside-vscode.png"  width="400px">

</p>

When finished, you will have a terminal inside the [VSCode](https://code.visualstudio.com/download)  that is already inside the container. Everything integrated! Like [Inception](https://www.imdb.com/title/tt1375666/)  🍿.

💡 Everything you do in this terminal will be done inside the container only!

Last Step:

```bash
# Generate diagrams
$ python diagram.py
```
Diagrams will be generated in a folder called “diagrams”, but you can change this if you want 😀.
 Look how handsome he looks:

<p  align="center">

<img  alt="Running the project"  title="Running the project"  src="./assets/python-diagrams-running.png"  width="800px">

</p>


>I wrote a post (Portuguese only) about [VSCode](https://code.visualstudio.com/download) and [Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers), if you want to read a little more about it, just go to ["Em busca da independência para o ambiente de desenvolvimento"](https://medium.com/@pedrorenan/em-busca-da-independ%C3%AAncia-para-o-ambiente-de-desenvolvimento-2adc22f6f250).

  
## 💪 How to contribute
  
1. Fork the project.
2. Create a new branch with your changes: `git checkout -b my-feature`
3. Save your changes and create a commit message telling you what you did: `git commit -m" feature: My new feature "`
4. Submit your changes: `git push origin my-feature`
> If you have any questions check this [guide on how to contribute](./CONTRIBUTING.md)
  
---

 
## 🦸 Author

[![Twitter Badge](https://img.shields.io/badge/-@pedrorenan-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/pedrorenan)](https://twitter.com/pedrorenan) [![Linkedin Badge](https://img.shields.io/badge/-Pedro%20Renan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/opedrorenan/)](https://www.linkedin.com/in/opedrorenan/) [![Gmail Badge](https://img.shields.io/badge/-pedrorenan@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:pedrorenan@gmail.com)](mailto:pedrorenan@gmail.com)

---

## 📝 License

This project is under the license [MIT](./LICENSE).

Made with ❤️ por Pedro Renan 👋🏽 [Get in Touch!](https://www.linkedin.com/in/opedrorenan/)

---