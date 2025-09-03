# Flask Blog

Um blog simples feito com **Flask** e **SQLite**, permitindo criar, editar e deletar posts.

## Tecnologias usadas

- Python 3
- Flask
- Flask-SQLAlchemy
- SQLite

## Estrutura do Projeto

- `app.py` → arquivo principal com toda a lógica do Flask
- `templates/` → pasta com os templates HTML (`index.html`, `edit.html`)
- `blog.sqlite3` → banco de dados SQLite criado automaticamente

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/DevPlayer02/flask_blog.git
cd flask_blog
```

2. Crie um ambiente virtual:

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. Instale as dependências:

```bash
pip install Flask Flask-SQLAlchemy
```

