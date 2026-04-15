# Projeto Django REST - AP1

## Domínio da API na AWS

http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/

---

## Navegação

- admin:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/admin/

- api:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/api/

- api produtos:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/api/produtos/

- api categorias:
http://ap1-django-env.eba-huvngg2a.us-east-1.elasticbeanstalk.com/api/categorias/

---

## Tecnologias utilizadas

- Python 3.14 / Django 6.0
- Django REST Framework
- Gunicorn
- SQLite
- AWS Elastic Beanstalk

---

## Como executar localmente

1. Clonar o repositório  
git clone https://github.com/yadura/resteb2.git  

2. Acessar a pasta  
cd resteb2  

3. Criar ambiente virtual  
py -m venv venv  

4. Ativar ambiente  
venv\Scripts\activate  

5. Instalar dependências  
pip install -r requirements.txt  

6. Rodar migrações  
py manage.py migrate  

7. Executar servidor  
py manage.py runserver  

---

## Etapas realizadas

- Criação da model Categoria  
- Relacionamento com Produto  
- Criação de serializers  
- Criação de views  
- Configuração de rotas  
- Testes locais  
- Deploy na AWS Elastic Beanstalk  

---

## Observação

O login do admin pode não funcionar corretamente na aplicação em produção.
