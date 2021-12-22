# Vers�o inicial curso Rest Api com Laravel 8

## Pr�-requisitos
1. PHP 8
2. Composer

## Como instalar

1. Clone ou fa�a download deste reposit�rio
2. Renomeie o arquivo .env.example para .env
2. Na pasta do projeto clonado, execute os seguintes comandos
   2.1 "composer install"
       2.1.1 Obs: Caso ocorra algum erro por vers�o do php ou falta de componentes, voc� pode rodar o comando composer install --ignore-platform-reqs
   2.2 php artisan migrate
   2.3 php artisan key:generate

## Como rodar

1. Na pasta do projeto, execute o comando php artisan serve

ou

2. Na pasta /public do projeto, execute o comando:  php -S localhost:8080 

## Como rodar com vers�es diferentes do PHP sem usar vari�veis de ambiente.

Voc� pode rodar, na linha de comando e estando na pasta do projeto, o caminho do php completo entre aspas. Exemplo: "c:\php8\php.exe" -S localhost:8080 

