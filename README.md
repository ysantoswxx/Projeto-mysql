#CRUD com Mysql + Python + Steamlit 

Este projeto e um exempo prático de CRUD usando:
- Banco de dados **Mysql**
- conexão com **mysql.connector**
-- Interface web com **Streamlit**

## Como executar

### 1. Clonar nosso repositório

``` bash
gt clone https://github.com/ysantoswxx/Projeto-mysql.git
```

### 2. Instalar dependências 
``` bash
pip install -r requirements.txt
```

### 3. Configurar as variaveis de ambiente 
crie um arquivo .env na raiz do seu projeto com:
``` bash
DB_PASSWORD=sua_senha
DB_HOST=localhost
DB_USER=seu_usuario
DB_NAME=seu_BD
```

### 4. Rodar aplicação
```bash
python -m streamlit run app.py
```

### 5. funcionalidade 
- Inserir registros no db

- Listar registros no db

- Atualizar registros no db

- Deletar registros no db

- Interface simples registros no db