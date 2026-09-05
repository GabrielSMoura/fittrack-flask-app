# 🏋️‍♂️ FitTrack Pro — Personal Fitness & Nutrition Tracker

O **FitTrack Pro** é uma aplicação web completa desenvolvida com **Flask** e **SQLite** projetada para quem deseja gerenciar rotinas de treino, registrar dietas, acompanhar evolução de carga e recordes pessoais (PRs) de forma 100% gratuita e individual.

![FitTrack Pro Banner](https://via.placeholder.com/1200x400/121212/e50914?text=FitTrack+Pro+-+Gym+%26+Nutrition+Tracker)

---

## 🚀 Funcionalidades Principais

* **🔒 Autenticação e Perfil de Usuário:** Sistema de login, cadastro com avatar/foto de perfil e isolamento total de dados por usuário.
* **🏋️ Fichas de Treino Flexíveis:** Criação e gestão de treinos personalizados (Treino A, B, C...) com contagem de séries, repetições e agrupamento muscular.
* **⏱️ Modo "Iniciar Treino":** Cronômetro e checklist em tempo real para acompanhar a execução dos exercícios durante o treino.
* **🏆 Gestão de Recordes Pessoais (PRs):** Registro da maior carga histórica levantada por exercício.
* **🥗 Controle de Dieta & Nutrição:** Registro de refeições com banco pré-cadastrado de alimentos e monitoramento de calorias e macronutrientes.
* **📊 Gráficos e Evolução:** Acompanhamento de evolução de peso corporal e metas diárias.
* **🌙 Dark Mode de Alto Contraste:** Interface moderna estilizada em preto, vermelho e branco com alternador de tema.

---

## 🛠️ Tecnologias Utilizadas

* **Backend:** Python 3, Flask, Flask-SQLAlchemy, Flask-Login, Werkzeug Security
* **Banco de Dados:** SQLite (visualizável via *SQLite Viewer* / *DB Browser*)
* **Frontend:** HTML5, CSS3 Customizado, JavaScript (ES6+), Bootstrap 5, FontAwesome 6
* **Visualização de Dados:** Chart.js

---

## 📁 Estrutura do Projeto

```text
Projeto/
├── instance/
│   └── banco.db              # Banco de dados SQLite
├── static/
│   └── css/
│       └── style.css         # Estilos customizados (Dark/Light Mode)
├── templates/
│   ├── base.html             # Template base (Navbar e Footer)
│   ├── dashboard.html        # Resumo de métricas e gráficos
│   ├── workouts.html         # Gestão de fichas e execução do treino
│   ├── diet.html             # Dieta e histórico de refeições
│   ├── progress.html         # Histórico de peso e evolução
│   ├── login.html            # Tela de login
│   └── register.html         # Tela de cadastro com avatar
├── app.py                    # Inicialização do app e rotas
├── models.py                 # Modelos do banco de dados (ORM)
└── requirements.txt          # Dependências do projeto
