# Django Rest Framework auth demo

Demonstração de autenticação utilizando token

* Bibliotecas usadas:
    * Django
    * Django Rest Framework
    * django-rest-auth
    * django-allauth

Há três urls:

* [POST] http://localhost:8080/auth/registration
    * Body:
        * Username
        * Email
        * Password1
        * Password2
    * Retorno:
        * Key

* [POST] http://localhost:8080/auth/login
    * Body
        * Username
        * Email
        * Password
    * Retorno
        * Key

* [POST] http://localhost:8080/auth/logout
    * Header:
        * Key
    * Retorno:
        * Vazio
