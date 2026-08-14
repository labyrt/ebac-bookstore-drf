# Bookstore — EBAC

Projeto desenvolvido por **Lucy Mazzini Lessa** para o exercício de Django REST Framework do curso de Backend Python da EBAC.

## Objetivo

Partir de um projeto Django chamado `bookstore` e integrar o Django REST Framework usando Poetry.

## Estrutura inicial

Nesta branch base, o projeto contém apenas a configuração padrão do Django necessária para o exercício. A integração com o DRF é realizada na branch `drf` e apresentada no Pull Request da atividade.

## Requisitos

- Python 3.12+
- Poetry

## Execução local

```bash
poetry install
poetry run python manage.py migrate
poetry run python manage.py runserver
```

O servidor de desenvolvimento fica disponível em `http://127.0.0.1:8000/`.
