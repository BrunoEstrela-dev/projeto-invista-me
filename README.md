# Invista Me

Sistema de controle de investimentos desenvolvido em Django.

## Funcionalidades

- Cadastro, edição e exclusão de investimentos
- Autenticação de usuários (login/logout)
- Interface responsiva com Bootstrap
- Confirmação de exclusão via modal

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/projeto-invista-me.git
   cd projeto-invista-me
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Realize as migrações:
   ```bash
   python manage.py migrate
   ```

5. Crie um superusuário:
   ```bash
   python manage.py createsuperuser
   ```

6. Rode o servidor:
   ```bash
   python manage.py runserver
   ```

Acesse em [http://localhost:8000](http://localhost:8000)

## Estrutura

- `invista_me/` - app principal
- `usuarios/` - app de autenticação
- `templates/` - templates HTML

## Licença

Este projeto está sob a licença MIT.