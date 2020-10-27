# [SecurityOP](#)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/black-dashboard-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/black-dashboard-django/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/black-dashboard-django.svg?maxAge=2592000)](https://github.com/creativetimofficial/black-dashboard-django/issues?q=is%3Aissue+is%3Aclosed) [![Join the chat at https://gitter.im/NIT-dgp/General](https://badges.gitter.im/NIT-dgp/General.svg)](https://gitter.im/creative-tim-general/Lobby) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)

![Black Dashboard Django - Admin Dashboard coded in Django.](https://github.com/creativetimofficial/black-dashboard-django/blob/master/media/black-dashboard-django-intro.gif)

<br />



## Tabela de Índice

* [Demonstração](#demo)
* [Começando](#quick-start)
* [Documentação](#documentation)
* [Estrutura de arquivos](#file-structure)
* [Suporte de navegadores](#browser-support)
* [Resources](#resources)
* [Reportar Issues](#reporting-issues)
* [Suporte Tecnico ou questões](#technical-support-or-questions)
* [Licença](#licensing)
* [Links Uteis](#useful-links)

<br />

## Demo

> Para autenticar use as credenciais de testes ***test / ApS12_ZZs8*** ou crie um novo usuario em [Pagina de registro](https://creativetim-django-dashboard-black-pro.appseed.us/register/).

- **SecurityOP** [Pagina de Login]()

<br />

## Começando

> Clone o repositório privado. Depois de obter o código, abra um terminal e navegue até o diretório de trabalho, com o código-fonte do produto.

```bash
$ # Pegue o Código
$ git clone https://github.com/
$ cd SecurityOP
$
$ # Instalação dos Módulos Virtualenv (Sistemas baseados em Unix)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Sistemas baseados em Windows)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Instalar Módulos - SQLite
$ pip3 install -r requirements.txt
$
$ # Criar Tabelas
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Começar a Aplicação SecurityOP (Modo desenvolvedor)
$ python manage.py runserver # Padrão porta 8000
$
$ # Começar a aplicação com portas diferentes - porta alternativa
$ # python manage.py runserver 0.0.0.0:<Sua_porta>
$
$ # Acessar na Web: http://127.0.0.1:8000/
```

> Nota: Para usar o aplicativo, acesse a página de registro e crie um novo usuário. Após a autenticação, o aplicativo irá desbloquear as páginas privadas.

<br />

## Documentação
Para a documentação do  **SecurityOP** está Hospedado em [website]().

<br />

## Estrutura de Arquivos
Depois de Fazer o download do projeto, você vai encontrar os seguintes arquivos:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implementa a lógica do app e fornece os ativos static
   |    |-- settings.py                    # Django app bootstrapper
   |    |-- wsgi.py                        # Coemço do app em produção
   |    |-- urls.py                        # Define a URLs que vai servir todo app/nodes
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS arquivos, Javascripts arquivos
   |    |
   |    |-- templates/                     # Templates usados pra renderizar paginas
   |         |
   |         |-- includes/                 # HTML e componentes
   |         |    |-- navigation.html      # Menu do top e Componentes
   |         |    |-- sidebar.html         # Sidebar Componentes
   |         |    |-- footer.html          # Footer do App
   |         |    |-- scripts.html         # Scripts de todas as paginas
   |         |
   |         |-- layouts/                  # Pagina master
   |         |    |-- base-fullscreen.html # Usado pra autenticas paginas
   |         |    |-- base.html            # Usado para opaginas normais
   |         |
   |         |-- accounts/                 # Autenticação de paginas
   |         |    |-- login.html           # Pagina de Login
   |         |    |-- register.html        # Pagina de Registro
   |         |
   |      index.html                       # Pagina principal
   |     page-404.html                     # Error 404 Pagina
   |     page-500.html                     # Error 404 Pagina
   |       *.html                          # Todas as outras paginas em HTML
   |
   |-- authentication/                     # Lida com rotas de autenticação (login e registro)
   |    |
   |    |-- urls.py                        # Definir rotas de autenticação
   |    |-- views.py                       # Lida com login e registro  
   |    |-- forms.py                       # Definir formulários de autenticação
   |
   |-- app/                                # O simples App que serve os arquvios html
   |    |
   |    |-- views.py                       # Servir páginas HTML para usuários autenticados
   |    |-- urls.py                        # Defina algumas rotas super simples  
   |
   |-- requirements.txt                    # Módulos de desenvolvimento - armazenamento SQLite
   |
   |-- .env                                # Configuração de injeção via ambiente
   |-- manage.py                           # Inicie o aplicativo - script de início padrão do Django
   |
   |-- ************************************************************************
```

<br />

## Suporte do Browser 

No momento, pretendemos oficialmente oferecer suporte às duas últimas versões dos seguintes navegadores:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

<br />

## Resources

- Demo: <>
- Download Page: <>
- Documentation: <>
- License Agreement: <>
- Support: <>
- Issues: [Github Issues Page]()

<br />

## Reportando Issues



<br />

## Suporte Tecnico ou questões 

Se você tiver dúvidas ou precisar de ajuda para integrar o produto [Contato]() em vez de abrir um problema.

<br />

## Licenciamento

- Copyright 2020 - present 
- Licenciado sob MIT

<br />

## Links Úteis

- [Tutorials]()

<br />

## Redes Sociais

- Twitter: <>
- Facebook: <>
- Dribbble: <>
- Instagram: <>

<br />

---
[SecurityOP]() - 
