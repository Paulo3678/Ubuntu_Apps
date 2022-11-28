<div align="center">
    <img src="./images/ubuntu.png"/>

# Instalação de plicativos necessários para desenvolvedores no Ubuntu
</div>


## Visual Studio Code (Vscode)

1º Faça o <a href="https://code.visualstudio.com/download"> download </a> do vscode .deb no site oficial.
2º Entre na pasta que você baixou o arquivo e abra o terminal.

> sudo su
> apt install ./&lt;nome do arquivo baixado.deb&gt;


## Postman

1º Abra o terminal e digite:
> sudo snap install postman

## Workbench

1º Abra o terminal e digite (necessário ter o mysql instalado, <a href="https://github.com/Paulo3678/Ubuntu_Config">clique aqui para aprender a instalar</a>):
> sudo snap install mysql-workbench-community

## Dbeaver

1º Faça o <a href="https://dbeaver.io/download/"> download </a> do instalador .deb no site oficial
2º Entre na pasta que você baixou o arquivo e abra o terminal.

> sudo su
> apt install ./&lt;nome do arquivo baixado.deb&gt;

## Notion

1º Abra o terminal e digite:
> sudo snap install notion-snap

## Filezilla

1º Abra o terminal e entre como super usuário.
> sudo su

2º Adicione o repositório do Filezilla no seu ubuntu
> add-apt-repository ppa:sicklylife/filezilla

3º Atualize as configurações do seu ubuntu
> apt-get update

4º Instale o Filezilla
> sudo apt-get install filezilla
