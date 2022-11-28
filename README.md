<div align="center">
    <img src="./images/ubuntu.png"/>

# Instalação de aplicativos necessários para desenvolvedores no Ubuntu
</div>


## Visual Studio Code (Vscode)

1º Faça o <a href="https://code.visualstudio.com/download"> download </a> do vscode .deb no site oficial.
<br>
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
<br>
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

<hr>

## Wine

1º Baixando propriedades do wine para o seu computador
> sudo apt install software-properties-common apt-transport-https winbind -y <br>

2º Instalando leitor 32bits linux
> sudo dpkg --add-architecture i386 <br>

3º Atualize as configurações do seu ubuntu
> sudo apt update <br>

4º Instalando wine 64 e 32 bits
> sudo apt install wine64 wine32 -y <br>

5º Verificando instalação
> wine --version <br>

6º Visualizar menu de configurações wine
> winecfg <br>

7º Instalando winetricks
> sudo apt isntal winetricks

8º Instalando dependências do wine
> winetricks atmlib gdiplus msxml3 msxml6 vcrun2005 vcrun2005sp1 vcrun2008 ie6 fontsmooth-rgb gecko