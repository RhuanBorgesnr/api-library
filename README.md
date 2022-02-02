# Sobre o Projeto

É uma api desenvolvida baseada em uma biblioteca em que você pode cadastrar, alterar e excluir livros.

## Tecnologias Utilizadas
- Python 3.7
- Django 3.2
- Django Rest Framework
- Docker
- Postgresql


## Executando o Projeto
```
docker-compose up --build
```
## Não se esqueça das migrações
```
docker-compose exec web python manage.py migrate
```
## Rode a API
```
docker-compose exec web python manage.py runserver
```
- Basta acessar pelo navegar através deste link: http://127.0.0.1:8000/books/
é criar os livros de sua preferência.

- Para a vizualização em Json acesse :http://127.0.0.1:8000/books/?format=json
- Para a vizualização em Xml acesse :http://127.0.0.1:8000/books/?format=xml

## Put e Delete

- Para realizar o put e delete copie o id_book e cole na frente do link conforme o exemplo: http://127.0.0.1:8000/books/0af1bf47-311c-46d1-924b-fdb2a40c00a8
