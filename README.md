# Projeto Web com Flask(Ecommerce) 

## Packages
bcrypt==4.0.1
blinker==1.6.2
click==8.1.3
dnspython==2.3.0
email-validator==2.0.0.post2
Flask==2.3.1
Flask-Bcrypt==1.0.1
Flask-Login==0.6.2
Flask-SQLAlchemy==3.0.3
Flask-WTF==1.1.1
greenlet==2.0.2
idna==3.4
importlib-metadata==6.6.0
itsdangerous==2.1.2
Jinja2==3.1.2
MarkupSafe==2.1.2
SQLAlchemy==2.0.11
typing-extensions==4.5.0
Werkzeug==2.3.1
WTForms==3.0.1
zipp==3.15.0

```
pasta instance - database(mercado.db)
arquivo forms.py - criacao de formulario da aplicação
arquivo models.py - criação dos modelos da aplicação
arquivo routes.py - criação das rotas da aplicaçào
pasta templates - pasta que contém o conteudo dos arquivos html e css
arquivo requirements.txt - pasta onde adicionei as bibliotecas utilizadas na aplicação
arquivo __init__.py - Os arquivos __init__.py são obrigatórios para fazer o Python tratar os diretórios que contem os pacotes, isto e feito para evitar diretórios com nomes em comum, tal como string, que involuntariamente se esconde nos módulos validos, aqueles que serão pesquisados no caminho. No caso mais simples, o arquivo __init__.py apenas pode ser um arquivo vazio, mas ele também executa o código de inicialização para o pacote ou defini a variável __all__, descrita mais tarde.
pasta env - ambiente virtual
pasta __pycache__ - Os arquivos da pasta pycache são bytecodes otimizados para o sistema operacional atual.
```
 
## Acessando a aplicação
cd ecommerce/
source env/bin/activate
## Rodando a aplicação
flask --app mercado run --debug



