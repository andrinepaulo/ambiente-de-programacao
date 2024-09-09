# Preparação de Ambiente
### Vamos preparar o ambiente para desnvolvimento de aplicações
 
#### Neste ambiente iremos instalar e configurar os seguintes recursos:
 - Máquina Virtual(Virtualbox)
 -Distribuição Linux (Ubuntu serve)
 Nasm
 - Compilador da linguagem C
 - Configurar o ip e a porta de comunicação entre a máquina real e a virtual
 - Configurar o acesso via SSH entre o VScode e o ServidorLinux
 -Instalar as extensões: Material Icon, Nasm, SSH e Linguagem C/C++
 
 
### Máquina Virtual (Virtualbox)
!["logo_virtualbox"](VM.jpg)
 
Máquina Virtual é uma ferramenta que permite a criação de novos "computadores" e a Instalação de sistemas operacinais, para estudos ou trabalho.
 
Para o nosso estudo iremos usar o Virtualbox, da Oracle.
Para instalar, basta fazer download no link a seguir:
<a href="https://www.virtualbox.org/wiki/Downloads" target= "_blank">Virtualbox</a>
 
##### Criando a Máquina virtual para nosso estudo
 
  - Configuração:
  + Nome da máquina: Servidor
  + Memória: 4 GB
  + Processador: 2
  + Capacidade: 100 GB
  + Porta do host: 127.0.0.1
  + Porta do convidado: 10.0.2.15
 
  - Tela inicial de Configuração
 
<img src=Configinit.png width=500 height= 250>
 
 - Tela inicial do Hardware
 
<img src=Configmemo.png width=500 height= 250>
 
 - Tela do Disco rígido
 
<img src=Capacidade.png width=500 height= 250>
 
 - Tela de configuração geral
 
<img src=Geral.png width=500 height= 250>
 
 - Tela de Configuração
 
<img src=Configrd.png width=500 height= 250>
 
 - Tela de IP
 
<img src=IP.png width=500 height= 250>
 
#### Distribuição Ubuntu server
- Para o nosso estudo usaremos uma distribuição Linux para servidores chamada Ubuntu, acompanhe o processo de instalação a seguir:
 
Link do Download do Ubuntu:
<a href="https://ubuntu.com/download/server">
 https://ubuntu.com/download/server
 
 
<img src=Ubuntu.png width=500 height= 250>
 
 
- Tela de inicio de instalação
 
<img src=TelainicioUB.png width=500 height= 280>
 
- Tela de idiomas (português-Brasil)
 
<img src=idiomas.png width=500 height= 250>
 
- Tipo de Teclado
 
<img src=idiomas2.png width=500 height= 250>
 
 
- Tipo de instalação
 
<img src=TipodeUB.png width=500 height= 250>
 
- IP (Rede)
 
<img src=ipUB.png width=500 height= 250>
 
- Proxy da rede
 
<img src=ProxyUB.png width=500 height= 250>
 
- Tela de pacotes de instalação
 
<img src=dwlpact.png width=500 height= 250>
 
- Instalação do SSH
 
<img src=SSH.png width=500 height= 250>
 
- Configuração do layout de do disco rígido
 
<img src=LayoutconfigHD.png width=500 height= 250>
 
- Reboot final do sistema
 
<img src=RebootF.png width=500 height= 250>
 
tem menu de contexto


reinicie o seu servidor usando o comando abaixo:

´´´
reboot
´´´

#### Instalação do compilador NASM
O compilador do NASM é uma ferramente que nos permite programar em Assembly. Assim é possível criar programas que manipulam dados que estão nos registradores do processador.

Para instalar o NASM no Ubunto, usamos o comando:
´´´
sudo apt install nasm -y
´´´
#### Instalação do compilador de Linguagem C

Em Linux, o compilador Linguagem C é o GCC, Ele é uma ferramenta importante para o desenvolvimento de programas em C.

Para instalar use o comando:
´´´
sudo apt install gcc -y
´´´

#### Conexão Servidor e VSCode via SSH

Precisamos instalar uma extensão no VSCode para acessar o nosso servidor de forma remota.

![](extensao.png)

Configuração do acesso remoto.

![](15tela_configuracao_extensao_ssh_remote.png)