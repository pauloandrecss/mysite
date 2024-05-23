## Blog 

Este projeto é um blog simples utilizando Django como uma Framework Full-Stack

É possivel a criação de posts e a adição de comentarios aos posts ja criados, os comentarios necessitam de aprovação de administradores, gerando mais segurança aos conteudos publicados.

<br>

![Captura de tela 2024-05-23 192212](https://github.com/pauloandrecss/mysite/assets/107274857/ced5e304-d2e2-4039-af09-81ae48309a4e)
![Captura de tela 2024-05-23 192526](https://github.com/pauloandrecss/mysite/assets/107274857/4f3679c6-f95a-4453-a112-df8af67cd9b3)


### Como executar:
<br>

* Clone o repositório utilizando o seguinte comando:

```bash
$ git clone https://github.com/pauloandrecss/mysite.git
```

* Vamos entrar em nossa pasta do projeto e criar um ambiente virtual:

```bash
$ cd mysite
$ python -m venv venv
```

* Agora podemos iniciar nosso ambiente virtual e instalar as bibliotecas necessarias:
  
```bash
$ venv/Scripts/Activate
$ pip install -r requirements.txt
```

* Com tudo instalado podemos criar a estrutura no nosso banco de dados:

```bash
$ python manage.py migrate
```

* E criar um super usuario para termos controles de administrador em nosso Blog:

```bash
$ python manage.py createsuperuser
```

Siga os passos e preencha as informações do seu super usuario que usaremos depois

* Agora com tudo pronto inicie o servidor utilizando o comando:

```bash
$python manage.py runserver
```
<br>
Acesse http://127.0.0.1:8000/ ou digite localhost:8000 em seu navegador e utilize nosso Blog.
<br>
<br>
Acesse http://127.0.0.1:8000/admin ou localhost:8000/admin com o super usuario anteriormente criado para ter acesso a parte de administração do Blog.
