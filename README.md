# User API

## Descrição
Este é um projeto de API de gerenciamento de usuários usando FastAPI e SQLite. Ele permite o registro de usuários, login e listagem de usuários.

## Estrutura do Projeto
- `app.py`: Contém a lógica principal da aplicação FastAPI.
- `models.py`: Define o modelo de banco de dados do usuário.
- `schemas.py`: Define os esquemas para validação de dados.
- `templates/`: Contém os arquivos HTML para renderização das páginas.
- `static/`: Contém os arquivos CSS e JS para estilização das páginas.
- `database.db`: Arquivo de banco de dados SQLite.
- `venv/`: Ambiente virtual Python.
- `__pycache__/`: Arquivos de cache do Python.

## Arquivos Ignorados
O arquivo `.gitignore` está configurado para ignorar os seguintes arquivos e pastas:

- `__pycache__/`: Contém arquivos de cache gerados pelo Python. Não é necessário versioná-los.
- `venv/`: Contém o ambiente virtual Python. Cada desenvolvedor deve criar seu próprio ambiente virtual localmente.
- `database.db`: Arquivo de banco de dados SQLite. Cada desenvolvedor pode criar seu próprio banco de dados para desenvolvimento e testes.

## Como Executar

### Pré-requisitos
- Python 3.7+
- FastAPI
- Uvicorn
- SQLAlchemy

### Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu_usuario/user_management_api.git
    cd user_management_api
    ```

2. Crie e ative um ambiente virtual:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Execute a aplicação:
    ```bash
    uvicorn app:app --reload
    ```

### Uso

- Acesse `http://127.0.0.1:8000/register` para registrar um novo usuário.
- Acesse `http://127.0.0.1:8000/login` para fazer login.
- Acesse `http://127.0.0.1:8000/users` para ver a lista de usuários (após fazer login).

## Contribuição
Sinta-se à vontade para abrir issues e enviar pull requests.

## Licença
Este projeto está licenciado sob a licença MIT.
