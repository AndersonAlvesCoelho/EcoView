# EcoView: Monitoramento Ambiental 🌍  

O **EcoView** é um projeto de monitoramento ambiental utilizando Django como backend para APIs e Vue.js como frontend, com suporte a mapas interativos implementados com Leaflet e Mapbox.

## 🚀 Tecnologias  
- **Backend**: Django, Django Rest Framework (DRF)  
- **Frontend**: Vue.js, Vite  
- **Mapas**: Leaflet, Mapbox  
- **Banco de Dados**: PostgreSQL com PostGIS  

## 🛠️ Configuração Inicial  

### Pré-requisitos  
Certifique-se de ter instalado:  
- **Python** (3.10+ recomendado)  
- **Node.js** (16+ recomendado)  
- **Yarn** (gerenciador de pacotes para o Vue)  
- **PostgreSQL** com a extensão PostGIS  

### Passos para Configuração  

#### 1. Backend (Django)
1. Certifique-se de ter Python 3.10+ instalado.
2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv env
   source env/bin/activate  # Linux/Mac
   env\Scripts\activate     # Windows
   ```
3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure o banco de dados no settings.py:
    - Configure o PostgreSQL e o PostGIS, conforme a documentação do Django.
    - Execute as migrações
    ```bash
    python manage.py migrate
    ```

5. Inicie o servidor de desenvolvimento:
    ```bash
    python manage.py runserver
    ```
    Acesse http://127.0.0.1:8000 para verificar.
---
#### 2. Configurar o Frontend (Vue.js)
1. Instale as dependências do Vue:
    ```bash
    cd frontend
    yarn install
    ```
2. Configure a integração com o backend (como URL base da API) em um arquivo ````.env.local````:
    ```bash
    VITE_API_URL=http://127.0.0.1:8000/api/
    ```
3. Inicie o servidor de desenvolvimento do Vue:
    ```bash
    yarn dev
    ```
    Acesse http://localhost:5173 para verificar.
---
  
