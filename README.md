
0x3a18cc2cb4b05607af63a145a18ad4a831672cab


OLA TUDO BEM AQUI VOCE IRAR APRENDER COMO MINERAR MONERO PELO XMRIG EM VPS NO LINUX  DE FOMA FACIL E SEM ENROLAÇAO 

PARA ISSO ENTRE NO MODO ROOT 

sudo su root

COPIE E COLE O COMANDO ABAIXO

sudo apt update && sudo apt install git build-essential cmake libuv1-dev libmicrohttpd-dev libssl-dev hwloc libhwloc-dev -y && cd && sudo git clone https://github.com/noobflix/monero.git xmrig && cd xmrig && sudo cmake . && sudo make
  

ESSE COMANDO ABAIXO E PARA COLOCAR SUA CARTEIRA DE MONERO E INICIA A MINERAÇAO

obs APAGUE AS ASPAS E COLOQUE SUA CONTA DO MONERO . NAS BARAS COLOQUE UM NOME PARA IDENTIFICAR SUA MAQUINA


nohup sudo ./xmrig -a  cryptonight -o pool.supportxmr.com:3333 -u 'APAGUE AS ASPAS E COLOQUE SUA CONTA DE MONERO' -p (APAGUE AS BARAS E COLOQUE UM NOME) -t  --donate-level=1 &


AGORA ABRA O SAITE AQUI NO LINK E OLHE SEU REDIMENTO 

link: https://supportxmr.com/

DENTRO DO SAITE COLE SUA CARTEIRA PARA VER OS REDIMENTO

