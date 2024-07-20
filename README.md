# User Management API

## Descrição

Esta API foi desenvolvida usando FastAPI e permite a criação, listagem e login de usuários. Utiliza um banco de dados SQLite para armazenar informações dos usuários e inclui uma interface front-end simples para uma melhor experiência do usuário.

## Instalação

1. Clone o repositório:

    ```bash
    git clone <URL_DO_REPOSITORIO>
    cd user_management_api
    ```

2. Crie e ative um ambiente virtual:

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3. Instale as dependências necessárias:

    ```bash
    pip install fastapi uvicorn sqlalchemy sqlite3
    ```

## Execução

Para executar o projeto, use o comando abaixo. Isso iniciará o servidor de desenvolvimento do FastAPI:

```bash
uvicorn app:app --reload
