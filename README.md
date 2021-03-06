<h1 align="center">
    <img alt="P.A.I.F" src=".github/logo.png" height="100px" /><br/>
    Python | Selenium | Requests
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/T635/P.A.I.F?style=social">&nbsp;
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/T635/P.A.I.F?style=social">&nbsp;
  <img alt="GitHub language count" src="https://img.shields.io/github/stars/T635/P.A.I.F?style=social">&nbsp;
</p>
<p align="center">
  <a href="#sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>
<br/>

## Sobre

O **P.A.I.F** é uma aplicação desktop feita para automatizar o processo de postagem de imagens em grupos do Facebook, para isto foi necessário analisar, com um proxy, todas as requisições http/https feitas entre o navegador e a plataforma após, elas foram reproduzidas no programa usando a linguagem de programação Python e as bibliotecas Requests e Selenium.

## Tecnologias

- [Python](https://www.python.org/)
- [Selenium](https://selenium-python.readthedocs.io/)
- [Requests](https://requests.readthedocs.io/en/master/)

## Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Python 3.8](https://www.python.org/)** instalado.
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado.
  - Também, é **preciso** ter o gerenciador de pacotes **[PIP](https://pip.pypa.io/en/stable/installing/)**.
  - É **essencial** ter o **[Selenium](https://selenium-python.readthedocs.io/)** .
  - Por fim, é necessário instalar o driver de seu **[navegador](https://selenium-python.readthedocs.io/installation.html#drivers)**.

- ### **Configuração**

  Caso use linux, instale o driver na pasta /usr/local/bin/

  Para qualquer outro S.O faz-se necessário colocar o driver na pasta do programa.

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/T635/P.A.I.F.git
```

2. Executando a Aplicação:

```sh
  $ cd P.A.I.F
  $ python3.8 main.py
```
