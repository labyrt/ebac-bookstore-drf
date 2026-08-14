# Bookstore — EBAC

Projeto desenvolvido por **Lucy Mazzini Lessa** para o exercício de Django REST Framework do curso de Backend Python da EBAC.

## Objetivo

Partir de um projeto Django chamado `bookstore` e integrar o Django REST Framework usando Poetry.

## Alterações desta branch

A branch `drf` contém somente as mudanças necessárias para a atividade:

- inclusão de `djangorestframework` nas dependências do projeto;
- atualização do `poetry.lock` para refletir a dependência instalada;
- inclusão de `'rest_framework'` em `INSTALLED_APPS` no `settings.py`.

## Comandos do exercício

```bash
poetry add djangorestframework
poetry update
poetry run python manage.py runserver
```

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
