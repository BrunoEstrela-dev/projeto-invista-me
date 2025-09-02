# Invista Me ![Python](https://img.shields.io/badge/python-3.11%2B-blue) ![Django](https://img.shields.io/badge/django-5.2-green) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

Sistema web para controle de investimentos, desenvolvido com Django, focado em praticidade, segurança e experiência do usuário.

---

## ✨ Funcionalidades

- Cadastro, edição e exclusão de investimentos
- Autenticação de usuários (login/logout)
- Interface responsiva com Bootstrap 5
- Confirmação de exclusão via modal (pop-up)
- Proteção de rotas com login obrigatório
- Validação de formulários

---

## 🛠️ Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/BrunoEstrela-dev/projeto-invista-me.git
   cd projeto-invista-me
   ```

2. **Crie e ative um ambiente virtual:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Realize as migrações:**
   ```bash
   python manage.py migrate
   ```

5. **Crie um superusuário:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Rode o servidor:**
   ```bash
   python manage.py runserver
   ```

Acesse em [http://localhost:8000](http://localhost:8000)

---

## 📁 Estrutura do Projeto

```
projeto-invista-me/
├── invista_me/         # App principal
├── usuarios/           # App de autenticação
├── templates/          # Templates HTML
├── static/             # Arquivos estáticos (CSS, JS, imagens)
├── requirements.txt
├── README.md
└── ...
```

---

## ⚙️ Principais Tecnologias

- [Python 3.11+](https://www.python.org/)
- [Django 5.2](https://www.djangoproject.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/)

---

## 🧑‍💻 Contribuição

Contribuições são bem-vindas!  
Abra uma issue ou envie um pull request.

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📫 Contato

- [LinkedIn](https://www.linkedin.com/in/bruno-estrelaa)
- [brunoestrela.dev@gmail.com](mailto:brunoestrela.dev@gmail.com)

---

> Projeto desenvolvido para portfólio pessoal e estudos de Django.