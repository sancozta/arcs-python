### Pythonarc

Projeto base para criação de apis desenvolvidas em python baseadas no framework flask. Os comandos abaixo é recomendado que sejam executados em um terminal bash.

#### Preperando o Ambiente

	pip install virtualenv
	virtualenv env

#### Instalando Dependências

	pip install -r requirements.txt

#### Determinando Path do Diretório

	export FLASK_APP=api/api.py

#### Habilitar Modo Debug

	export FLASK_DEBUG=true

#### Executando Projeto

	flask run
    flask run --host=0.0.0.0 --port 5000

#### Comandos Direcionados ao Heroku

	web: gunicorn --chdir api api:app	