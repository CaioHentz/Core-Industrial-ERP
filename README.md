# Core

**Slogan:** Simplify. Organize. GROW.

## Descrição do Projeto

O **Core** é um sistema ERP desenvolvido para otimizar e integrar os processos internos de empresas, oferecendo uma interface simples, responsiva e intuitiva.  
O foco do projeto é fornecer uma solução escalável e moderna para gestão empresarial, mantendo o equilíbrio entre eficiência e usabilidade.

## Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3  
- **Backend:** Python 3.x, Django Framework  
- **Banco de Dados:** SQLite (desenvolvimento) / PostgreSQL (produção)  
- **Outras ferramentas:** Git, Virtualenv

## Funcionalidades

- Painel inicial com KPIs e atalhos rápidos
- Sistema de autenticação de usuários
- Gestão de clientes, produtos e pedidos
- Relatórios gerenciais
- Interface responsiva e amigável

## Instalação e Execução

1. **Clonar o repositório**
   ```bash
   git clone https://github.com/seuusuario/core.git
   cd core
   ```

2. **Criar e ativar o ambiente virtual**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate    # Windows
   ```

3. **Instalar dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar o banco de dados**
   ```bash
   python manage.py migrate
   ```

5. **Executar o servidor**
   ```bash
   python manage.py runserver
   ```

6. **Acessar no navegador**
   ```
   http://127.0.0.1:8000
   ```


