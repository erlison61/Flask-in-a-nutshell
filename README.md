## Olá, programador 👋

esse texto foi criado pelo professor Rhavy maia, estou apenas facilitando a leitura para os que tem interesse em buscar conhecimento em Flask e programação na web. 


# Instalando Virtual Environment

- Python 3.8
- Pip
  - Verificar se o gerenciador de pacotes do Python está instalado:
    ```
    $ pip -V
    ```
  - Caso não esteja instalado:
    ```
    $ sudo apt-get install python3-pip
    ```

- Virtual Environment
  - Instalando
    ```
    $ sudo apt-get install -y python3-virtualenv
    ```
    ou
    ```
    $ sudo pip3 install virtualenv
    ```
  - Criar venv
    ```
    $ virtualenv venv
    ```
  - Ativação e Desativação
    ```
    $ source venv/bin/activate
    $ deactivate
    ```
  - No Windows:
    ```
    $ python -m venv venv
    $ .\venv\Scripts\Activate.ps1
    ```

- Requirements.txt
  - [Repositório GitHub](https://github.com/miguelgrinberg/REST-tutorial/blob/master/requirements.txt)
  - Instalando as dependências
    ```
    $ pip install -r requirements.txt
    ```

- Ajustar venv para Python 3
  - [Referência](https://stackoverflow.com/questions/23842713/using-python-3-in-virtualenv)

# DB Browser

- [Instalação do DB Browser no Ubuntu](https://linuxhint.com/install-sqlite-browser-ubuntu/)




# Exemplos de Aplicações em Flask

- [Exemplo 1](https://github.com/rhavymaia/flask_vseducitec)
- [Exemplo 2](https://auth0.com/blog/developing-restful-apis-with-python-and-flask/)
- [Exemplo 3](https://parzibyte.me/blog/en/2020/11/12/creating-api-rest-with-python-flask-sqlite3/)
- [Exemplo 4](https://levelup.gitconnected.com/full-stack-web-app-with-python-react-and-bootstrap-backend-8592baa6e4eb)

# Endpoints

- [Visualizar Endpoints](https://drive.google.com/file/d/1SgTQ43SAdAN-GcafCzrxSG6FSVgPi4rE/view?usp=sharing)

# Flask

- [Como Usar um Banco de Dados SQLite em uma Aplicação Flask](https://www.digitalocean.com/community/tutorials/how-to-use-an-sqlite-database-in-a-flask-application)

# Flask-Restful

- [Documentação Básica](https://flask-restful.readthedocs.io/en/latest/fields.html#basic-usage)
- Variável de ambiente



# Reqparser

- [Documentação Reqparser](https://flask-restful.readthedocs.io/en/latest/reqparse.html)

# SQLAlchemy

- [Início Rápido do SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/)
- [Como Usar um Banco de Dados SQLite em uma Aplicação Flask](https://www.digitalocean.com/community/tutorials/how-to-use-an-sqlite-database-in-a-flask-application)
- [Tutorial Avançado do SQLAlchemy](https://tonyj.me/blog/building-rest-apis-with-python-and-flask-part-1/)
- Adicionar ao código do app



# Migrate

- [Documentação Flask-Migrate](https://flask-migrate.readthedocs.io/en/latest/)

# Comandos Git

- [Guia Prático do Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
- [Adicionando Código Local ao GitHub](https://docs.github.com/pt/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github)
- [Instalação do GitHub CLI](https://www.techiediaries.com/install-github-cli-ubuntu-20/)
- Comandos:
  ```
  $ git config --global user.email "you@example.com"
  $ git config --global user.name "Your Name"
  ```

# Postgres

- [Instalação do PostgreSQL e PgAdmin no Ubuntu](https://www.tecmint.com/install-postgresql-and-pgadmin-in-ubuntu/)

# Repositório da Aplicação

- [Repositório GitHub](https://github.com/rhavymaia/sqlalchemy_app)

# Lista de Dependências

- aniso8601==9.0.1
- click==8.0.3
- Flask==2.2.1
- Flask-HTTPAuth==4.5.0
- Flask-RESTful==0.3.9
- itsdangerous==2.0.1
- Jinja2==3.1.2
- MarkupSafe==2.1.1
- pytz==2021.3
- six==1.16.0
- Werkzeug==2.2.0
- Flask-Cors==3.0.10
- Flask-SQLAlchemy==3.0.3

- [Como Usar o Flask-SQLAlchemy para Interagir com Bancos de Dados em uma Aplicação Flask](https://www.digitalocean.com/community/tutorials/how-to-use-flask-sqlalchemy-to-interact-with-databases-in-a-flask-application)
- [Autenticação RESTful com Flask](https://blog.miguelgrinberg.com/post/restful-authentication-with-flask)
- [Como Criar Relacionamentos Um-para-Um com Declarative no SQLAlchemy](https://stackoverflow.com/questions/3464443/how-to-create-one-to-one-relationships-with-declarative)
- [Usando o Flask-SQLAlchemy com o PostgreSQL](https://vsupalov.com/flask-sqlalchemy-postgres/)
- [Configuração do Ambiente Virtual e Ativação](https://gist.github.com/rmax/fe565b94743e1a413280de0d51c18622)
- [Exemplo de Aplicação usando Flask e SQLAlchemy](https://github.com/marcellacg/pongs)
- [Template Admin Gratuito com React e Bootstrap](https://coreui.io/product/free-react-admin-template/#pricing-tables)
