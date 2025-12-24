# 📊 Data Pipeline Project with MySQL & Flask

🚀 *End-to-end data processing, storage, calculation and API exposure*

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)
![Flask](https://img.shields.io/badge/Flask-API-black?logo=flask)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌎 Languages

* 🇧🇷 [Português](#-descrição-do-projeto)
* 🇺🇸 [English](#-project-description)

---

# 🇧🇷 Descrição do Projeto

Este projeto tem como objetivo o desenvolvimento de um **pipeline de dados completo**, abrangendo todas as etapas desde a **limpeza e tratamento dos dados brutos**, passando pela **persistência em um banco de dados MySQL**, até a **realização de cálculos a partir desses dados**.

Como etapa final, é criada uma **API REST utilizando Flask**, facilitando a **inserção de dados**, **consulta de informações** e **execução de cálculos**, tornando o sistema mais modular, escalável e acessível.

---

## 🎯 Objetivos

* 🧹 Limpar e tratar dados brutos
* 🗄️ Armazenar os dados em um banco de dados MySQL
* 📊 Recuperar os dados para realização de cálculos
* 🔌 Criar uma API REST com Flask para:

  * Inserção de dados
  * Consulta de dados
  * Execução de cálculos automatizados

---

## 🛠️ Tecnologias Utilizadas

* 🐍 Python
* 🐬 MySQL
* 🌐 Flask
* 📈 Pandas
* 🧮 SQL
* 🔧 Git

---

## 📂 Estrutura do Projeto

```bash
├── data/
│   ├── raw/                # Dados brutos
│   └── processed/          # Dados tratados
│
├── database/
│   ├── connection.py       # Conexão com o MySQL
│   └── schema.sql          # Estrutura do banco
│
├── scripts/
│   ├── data_cleaning.py    # Limpeza e tratamento
│   ├── data_insert.py      # Inserção no banco
│   └── calculations.py    # Lógica de cálculos
│
├── api/
│   ├── app.py              # Aplicação Flask
│   └── routes.py           # Rotas da API
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🔄 Fluxo do Projeto

1. 📥 Coleta dos dados brutos
2. 🧹 Limpeza e padronização
3. 🗄️ Inserção no MySQL
4. 📊 Consulta e cálculo
5. 🌐 Disponibilização via API Flask

---

## 🚀 Como Executar

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
pip install -r requirements.txt
python api/app.py
```

A API estará disponível em:

```
http://localhost:5000
```

---

## 🔮 Melhorias Futuras

* 🔐 Autenticação na API
* 🧪 Testes automatizados
* 🐳 Dockerização
* ☁️ Deploy em nuvem
* 📄 Documentação com Swagger

---

---

# 🇺🇸 Project Description

This project aims to build a **complete data pipeline**, covering all stages from **raw data cleaning and processing**, through **data persistence in a MySQL database**, to **performing calculations based on stored data**.

As a final step, a **REST API using Flask** is developed to simplify **data insertion**, **data retrieval**, and **calculation execution**, making the system more modular, scalable, and user-friendly.

---

## 🎯 Objectives

* 🧹 Clean and preprocess raw data
* 🗄️ Store processed data in a MySQL database
* 📊 Retrieve data to perform calculations
* 🔌 Build a Flask REST API to:

  * Insert data
  * Query stored data
  * Execute automated calculations

---

## 🛠️ Tech Stack

* 🐍 Python
* 🐬 MySQL
* 🌐 Flask
* 📈 Pandas
* 🧮 SQL
* 🔧 Git

---

## 🔄 Project Workflow

1. 📥 Data ingestion
2. 🧹 Data cleaning and transformation
3. 🗄️ Data storage in MySQL
4. 📊 Data querying and calculations
5. 🌐 API exposure via Flask

---

## 🔌 API Features (Example)

* **POST** `/insert-data` → Insert data into database
* **GET** `/data` → Retrieve stored data
* **GET** `/calculate` → Perform calculations

---

## 👤 Author

Developed by **Miguel Soares Da Silva**
📧 Email: [your-email@email.com](mailto:use.if1001guidovanrossum63print@gmail.com)
🔗 GitHub: [https://github.com/your-username](https://github.com/Ikkou-migs23)
