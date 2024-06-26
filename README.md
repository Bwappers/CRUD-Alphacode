# Crud de uma Sorveteria

Este é um projeto desenvolvido para a disciplina de Programação Orientada. O objetivo é criar um sistema CRUD para uma sorveteria.

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- Vue.JS: Um framework JavaScript progressivo para construir interfaces de usuário.
- PrimeVue: Uma biblioteca de componentes rica para Vue.js com mais de 70 componentes de código aberto.
- Laravel: Um framework PHP para desenvolvimento web, que é totalmente gratuito e de código aberto.
- Composer: Gerenciador de dependências do PHP.
- NPM: Um gerenciador de pacotes para o ambiente de execução Node.js.
- Módulo de linguagem pt_BR (português brasileiro) para Laravel: Traduções em PT-BR para o Laravel.

## Como rodar

Uma versão do PHP será necessária, para Windows é recomendado baixar o XAMPP. No php.ini do XAMPP, geralmente localizado em `C:\xampp\php`, habilite as extensões php_curl, php_openssl e opcionalmente para instalar o projeto mais rápido a extensão de zip.

Certifique o Composer e NPM estão instalados corretamente. Depois, rode os seguintes comandos:

```
$ cd sorveteria_trab
$ composer install
$ npm install
```

Crie um arquivo `.env` baseado no `.env.example`, e certifique-se de que este está com as credenciais desejadas. Após isso, migre o banco de dados e inicie o servidor com:

```
$ php artisan migrate
$ php artisan key:generate
$ npm run build
$ php artisan serve
```
