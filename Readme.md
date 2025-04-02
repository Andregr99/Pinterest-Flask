# 🌤️ **FakePinterest - Clone do Pinterest com Flask** 🤩

Este projeto Flask implementa um clone simplificado do Pinterest, permitindo aos usuários criar contas, fazer login, postar fotos e visualizar um feed de fotos.

## ⚙️ **Funcionalidades**  

✅ **Cadastro de Usuários:** Permite que novos usuários criem contas com nome de usuário, e-mail e senha.

✅ **Login de Usuários:** Permite que usuários cadastrados façam login para acessar suas contas.

✅ **Perfil de Usuário:** Cada usuário possui um perfil onde pode visualizar suas próprias fotos e postar novas fotos.

✅ **Feed de Fotos:** Exibe um feed com as fotos postadas por todos os usuários, ordenadas por data de criação.

✅ **Pesquisa de Fotos:** Permite pesquisar fotos por descrição.

✅ **Upload de Fotos:** Permite que usuários façam upload de fotos para seus perfis.

## 🚀 **Tecnologias Utilizadas**

- **Python 3.x:** Linguagem de programação principal.
- **Flask:** Framework web para desenvolvimento do backend.
- **Flask-SQLAlchemy:** ORM para interação com o banco de dados SQLite.
- **Flask-Login:** Gerenciamento de autenticação de usuários.
- **Werkzeug:** Biblioteca para segurança e upload de arquivos.
- **Bcrypt:** Biblioteca para criptografia de senhas.
- **SQLite:** Banco de dados para armazenamento de usuários e fotos.
- **HTML/CSS/JS:** Para a interface do usuário.
- **Jinja2:** Motor de templates para renderização de páginas HTML.

## ⚙️ **Instalação e Execução**  

1️⃣  **Clone o repositório:**

    git clone https://github.com/Andregr99/Pinterest-Flask.git
    No seu terminal digite: cd fakepinterest

2️⃣  **Crie e ative um ambiente virtual:**

    python -m venv venv

    * **Windows (CMD):** `venv\Scripts\activate`
    * **Windows (PowerShell):** `venv\Scripts\Activate.ps1`
    * **Linux/macOS:** `source venv/bin/activate`

3️⃣  **Instale as dependências:**

    pip install Flask Flask-SQLAlchemy Flask-Login Werkzeug bcrypt

4️⃣  **Crie o banco de dados:**

    Execute o script `criar_banco.py` (se você tiver um) ou execute os comandos no terminal Python:
python
    from fakepinterest import database
    database.create_all()

5️⃣  **Execute o servidor:**

    python main.py

Acesse no navegador:
🔹 Clique no link "http://127.0.0.1:5000/" no seu terminal enquanto segura a tecla Ctrl 🤩🚀🚀🚀

**Como estou iniciando minha jornada neste framework, feedbacks e sugestões são muito bem-vindos guys. Para dúvidas ou colaborações, entre em contato comigo pelo LinkedIn 🤩🤝**
