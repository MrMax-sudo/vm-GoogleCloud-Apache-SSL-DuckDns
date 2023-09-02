# vm-GoogleCloud-Apache-SSL-DuckDns

 * Subindo Instância Ubuntu 22.04 no GoogleCloud, aproveitando o período gratuito de 90 dias.
 
 * Conectando via Putty
 
 * Instalando o Apache
 
 * Configurando URL com DuckDns
 
 * Ativando HTTPS pelo certbot
 
  [Assista aqui a parte 1!](https://www.youtube.com/watch?v=mxWp0pCDnok&t=112s)
  [Assista aqui a parte 2!](https://www.youtube.com/watch?v=omxqNrv2Ros&t=155s)
 
 # Comandos:
   
    sudo -i 
    apt update && apt upgrade -y
    apt install apache2
    apt install certbot python3-certbot-apache
    certbot --apache

