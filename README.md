# Projeto Django REST - AP1

## Objetivo
Criação de uma nova classe Categoria relacionada com Produto e exposição via API, com deploy na AWS Elastic Beanstalk.

## Como executar localmente

git clone https://github.com/ydurra/resteb2.git

cd resteb2

py -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

py manage.py migrate

py manage.py runserver

## Aplicação em produção

http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/

## Endpoints

Produtos:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/api/produtos/

Categorias:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/api/categorias/

## Etapas realizadas

- Criação da model Categoria
- Relacionamento com Produto
- Criação de serializers
- Criação de views (ModelViewSet)
- Configuração de rotas
- Testes locais
- Deploy na AWS Elastic Beanstalk
