# Projeto To-Do List com Django

![Python Version](https://img.shields.io/badge/Python-3.13-blue.svg)
![Django Version](https://img.shields.io/badge/Django-5.2-0C4B33.svg?logo=django)
![License](https://img.shields.io/badge/License-MIT-green.svg)

> **Status:** Em Desenvolvimento 🚧

---

## 1. Descrição

Este projeto é uma aplicação web completa de **Lista de Tarefas (To-Do List)** desenvolvida em Python com o framework Django. O objetivo é aplicar na prática os conceitos fundamentais do Django, desde a configuração do ambiente até a implementação de um CRUD (Create, Read, Update, Delete) funcional.

Este repositório serve como um projeto de portfólio e um registro de aprendizado, baseado no curso "Crie um projeto completo com Django" da [TreinaWeb](https://www.youtube.com/watch?v=MsUL3Pgofl4).

## 2. Funcionalidades (Features)

A aplicação permite que o usuário gerencie suas tarefas diárias através das seguintes funcionalidades:

- **Criação de Tarefas:** Adicionar novas tarefas com título e data de entrega.
- **Listagem de Tarefas:** Visualizar todas as tarefas pendentes, ordenadas por data.
- **Atualização de Tarefas:** Editar informações de uma tarefa existente.
- **Exclusão de Tarefas:** Remover uma tarefa da lista.
- **Marcar como Concluída:** Mudar o status de uma tarefa para "concluída".

## 3. Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias e conceitos:

- **Backend:** Python 3.13, Django 5.2
- **Frontend:** HTML5, CSS3, Bootstrap 5
- **Gerenciamento de Forms:** `django-crispy-forms`
- **Arquitetura:** Model-Template-View (MTV) e Class-Based Views (CBVs)
- **Ambiente:** `venv` (Ambiente Virtual Python)
- **Versionamento:** Git & GitHub

## 4. Como Executar o Projeto

Siga os passos abaixo para executar o projeto localmente:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/rafaelvanhoni/to-do-list-django.git](https://github.com/rafaelvanhoni/to-do-list-django.git)
    cd to-do-list-django
    ```

2.  **Crie e ative o ambiente virtual:**
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3.  **Instale as dependências:**
    (Ao final do projeto, as dependências estarão listadas em `requirements.txt`. Se ele já existir, use o comando abaixo.)
    ```bash
    pip install -r requirements.txt
    ```
    *(Nota: Se o arquivo `requirements.txt` ainda não existir, instale o Django manualmente conforme o curso: `pip install Django`)*

4.  **Aplique as migrações do banco de dados:**
    (Este comando cria o arquivo de banco de dados `db.sqlite3` com as tabelas necessárias.)
    ```bash
    python manage.py migrate
    ```

5.  **Execute o servidor de desenvolvimento:**
    ```bash
    python manage.py runserver
    ```

6.  Acesse o projeto em `http://127.0.0.1:8000/` no seu navegador.

## 5. Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.