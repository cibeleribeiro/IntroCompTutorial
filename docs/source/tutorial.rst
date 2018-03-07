.. Tutorial de Introdução à Computação documentation master file, created by
   sphinx-quickstart on Tue Feb 20 16:53:25 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


**INSTALAÇÃO DE PROGRAMAS**
===========================

.. image:: _static/happy.jpg

INSTALAR ORACLE VM VIRTUALBOX
-----------------------------

O VirtualBox é um sistema que possibilita criar e gerenciar maquinas virtuais no seu computador. O que isso significa? Significa que é possível rodar outro sistema operacinoal no seu computador sem desinstalar o atual. Pode-se rodar o Linux dentro do Windows, o Windows dentro do Mac e o Mac dentro do Windows, etc.

**Passo a Passo**

Baixe o programa no site oficial da Oracle.

.. image:: _static/virtualbox1.png

Clique no ícone do Virtualox na sua pasta de downloads.

.. image:: _static/vbox2.png

Abrirá uma aba que indica o início do seu processo de instalação.
Clique em NEXT.

.. image:: _static/vbox3.png

A próxima aba indica o local em que o programa será salvo em seu computador. Mantenha as informações selecionadas ou mude a seu gosto e clique em NEXT.

.. image:: _static/vbox4.png

A aba abaixo indica se você quer um atalho para o seu Desktop ( primeiro quadrado selecionado) e para sua barra de ferramentas ( segundo quadrado selecionado). Faça suas escolhas e clique em NEXT.

.. image:: _static/vbox5.png

Essa é uma aba de atenção. Indica que para prosseguir com a instalção você será disconectado da internet. Salve o que for preciso e clique em NEXT.

.. image:: _static/vbox6.png

Finalmente, estamos prontos para iniciar o real processo de instalção. Clique em NEXT.

.. image:: _static/vbox7.png

Sua intalção está completa. Clique em FINISH.

.. image:: _static/vbox8.png

INSTALAR UBUNTU NO VIRTUALBOX
-----------------------------

Abrir o Oracle VM VirtualBox Gerenciador e clicar em Creat Virtual Machine.


.. image:: _static/ubuntu1.png

Criar:


Nome:IntroComp


Tipo:Linux


Versão:Ubuntu (64-bit)

.. image:: _static/ubuntu2.png

Selecioinar tamanho da memória: 2048.

.. image:: _static/ubuntu3.png

Criar um novo.

.. image:: _static/ubuntu4.png

Selecionar: VDI.

.. image:: _static/ubuntu5.png

Selecionar: Dinamicamente Alocado.

.. image:: _static/ubuntu6.png

Localização e tamanho do arquivo
15,12

.. image:: _static/ubuntu7.png

O Armazenamento estará vazio clique no Ide secundário Master.

.. image:: _static/ubuntu9.png

Escolha o arquivo do Ubuntu 17.10 que você baixou do site para seu computador.

.. image:: _static/ubuntu10.png

Observe se na imagem de CD aparece o nome do Ubuntu. Se sim, clique seta verde.

.. image:: _static/ubuntu11.png

Remova a janela pop up, clicando no OK.

.. image:: _static/ubuntu13.png

Espere alguns segundos até abrir a janela de instalção do Ububtu. Clique em instalar ubuntu.

.. image:: _static/ubuntuA.png

Selecione Instal Updates e clique em CONTINUE

.. image:: _static/ubuntuB.png

Selecione a primeira opção que é apagar o disco e instalar o Ubuntu. Clique em CONTINUE.

.. image:: _static/ubuntuC.png

Escolha sua Cidade.

.. image:: _static/ubuntuD.png

Escolha sua língua falada e teclado.

.. image:: _static/ubuntuE.png

Na aba "Who are you" crie respectivamente: seu nome , o nome do seu computador, seu login, sua senha, confirme sua senah e selecione requerer senha.

.. image:: _static/ubuntuF.png

Espere seu sistema instalar (pode ser que demore um longo tempo).

.. image:: _static/ubuntuG.png

Dê OK na aba e seu Ubuntu estará instalado no seu VirtualBox.

.. image:: _static/ubuntuH.png Tutorial Supygirls Connections FONOCOMP_html_1e4eb1b41bd2815c.jpg



INSTALAR UMAKER
---------------
Instalador profissional de ferramentas de desenvolvedor - idepycharm

Terminal abre: Ctrl+Shift+t

Escreva o nome do programa: umake
A informação gerada especifica se há o "ubuntu-maker" instalado no seu computador.


.. image:: _static/umaker1.jpg


Digite: sudo apt-get install ubuntu-maker
    sudo( significa que vc é administrador e tem permissões diferenciadas)
    apt (pacotes do ubuntu)
    install chama o processo de instalação


.. image:: Tutorial Supygirls Connections FONOCOMP_html_a1584d04285a2830.jpg

Atualize a biblioteca de repositórios
Digite: Sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make
        Sudo apt-get update


INSTALAR PYCHARM
----------------

Digite: umake ide pycharm
Insira a senha e pressione enter


.. image:: Tutorial Supygirls Connections FONOCOMP_html_9e7c95de9cae7aa5.jpg


Concluiu a instalação desligar janela de execução e iniciar seta verde.


**CRIAR CONTAS**
================

CONTA PROJETO PYCHARM
---------------------

Início de projeto:
file:
settings
project
interpreter
configuração
create virtual environment
Python3.5
Marcar: Inherit global site-packages
Name:
Marcar (No)
Name:SuPyJogo
OK

CONTA NO GITHUB
---------------

Username:

email:

password:

continue
continue

participar do SuPyPerson
Inca

CONTA SLACK
-----------

O que estamos fazendo:
Formando um time profissional de desenvolvimento. Não usa windows pq tem muito virus. Ubunto profissional


CONTA WAFFLE.IO
---------------

**INTEGRAR CONTAS**
===================

SINCRONIZANDO  GITHUB E PYCHARM
-------------------------------

Abra o IDE Pycharm e prima > Check out from Version Control <



.. image:: _static/sincronizar1.jpg



Ao abrir as opções, prima > GitHub < para resgatar e logar na plataforma.



.. image:: _static/sincronizar2.jpg



Insira suas informações de usuário e prima >Login<

      **Atenção:**

            Host: github.com

            Auth Type: Password

.. image:: _static/sincronizar3.jpg

Na página seguinte, selecione o repositório do projeto >Git Repository URL<  e a “pasta pai” >Parent Directory<
-Veja Imagens- Feito isso, prima >Clone<

.. image:: _static/sincronizar4.jpg

Selecione o repositório a sua escolha

.. image:: _static/sincronizar5.jpg

Selecione a pasta "pai" de seu interesse.

.. image:: _static/sincronizar6.jpg

Abrirá um pop-up perguntando se você gostaria de abrio o diretório. Clique no sim.

.. image:: _static/sincronizar7.jpg

COMO ABRIR O PROJETO NO PYCHARM
-------------------------------

Observe o lado esquerdo do seu cursor e clique na primeira pasta.

.. image:: _static/abrir1.jpg

Clique com o botão direito sobre o projeto > New > Directory> src

.. image:: _static/abrir2.jpg

Clique com o botão direito sobre src> New > Python File > “main”

.. image:: _static/abrir3.jpg

Vai aprir um pop-uppedindo para você confirmar o novo arquivo. Diga ok.

.. image:: _static/abrir4.jpg

Surge a aba do novo arquivo em Python. Porem ela vai esta na cor vermelha.

.. image:: _static/abrir5.jpg

Para que seja realmente adicionado o arquivo, clique com o botão direito em src > git > +add

.. image:: _static/abrir6.jpg

Se o arquivo mudou para a cor azul ele está corretamente adicionado.

.. image:: _static/abrir7.jpg


**DOCUMENTOS DE LEITURA**
=========================

SPHINX CHEATSHEET
-----------------

**MODELAGEM ÁGIL**
==================

USER STORIES
------------

CRC CARDS
---------

PRÉ-REQUISITOS PARA INTRODUÇÃO À COMPUTAÇÃO
===========================================

 * Abrir conta
      * Github
      * IDE Pycharm Version: 2017.3.3 ou superior
      * Slack
      * Waffle.io

