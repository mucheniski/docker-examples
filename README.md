# docker-examples

# Repositório com exemplo de utilização do Docker Compose
O site utilizado para teste neste exemplo foi retirado do repositório público da Gláucia Lemos, com a permissão da mesma: https://github.com/glaucia86/projeto.crud.php

O site em questão é um CRUD simples, uma espécie de agenda online. Na aula prática de Docker Compose, levantamos esse site utilizando 3 containers: Um container do PHP, um do NGINX e um do MySQL.


## WSL2 docker no windows  
### Tutorial oficial: 
https://docs.microsoft.com/en-us/windows/wsl/install-win10  

### Passo 1 (PowerShell Admin):   
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart  

### Passo 2 (PowerShell Admin):  
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart  

### Passo 3  
REINICIE O COMPUTADOR  

### Passo 4 (Download the Linux kernel update package):  
https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi  

### Passo 5 (PowerShell Admin):  
wsl --set-default-version 2  

### Passo 7 (Instale o docker):  
Tutorial: https://docs.docker.com/docker-for-windows/install/  
