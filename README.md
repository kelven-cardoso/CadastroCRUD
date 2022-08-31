# CadastroCRUD
 Cadastro-CRUD com Python e Django

Como utilziar:
## No terminal vá em:
~~~
cd venv\Scripts
activate
~~~
para ativar o ambiente virtual

Em seguida volte para a pasta raiz.

## Instale as depedencia com:
~~~
pip install -r requirements.txt
~~~
#### Pode ser que precise instalar o cliente do Mysql
~~~
pip install mysqlclient-1.4.6-cp39-cp39-win_amd64.whl
~~~

Crie um banco de dado vazio Mysql e altere as informações em  	`\prejeto_kelven\settings.py`, e em seguida edite o 'DATABASES' com as informações. 

## Utilize o comando para migrar o banco de dados:
~~~
python manage.py migrate
~~~
## E rode o sistema com o comando: 
~~~
python manage.py runserver
~~~~
