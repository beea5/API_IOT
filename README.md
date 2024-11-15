# API para Sensor BME280

## Descrição
Esta API foi desenvolvida para integrar com o sensor **BME280**, utilizando os dados de **temperatura** e **umidade** coletados pelo dispositivo. O projeto utiliza o banco de dados **PostgreSQL**, gerenciado através do **pgAdmin**.

---

## Pré-requisitos
Para executar o projeto, é necessário:
- **Python** instalado no sistema.
- Instalar as bibliotecas listadas na seção de dependências.

---

## Instalação

### 1. Baixe e instale o Python
- Acesse o [site oficial do Python](https://www.python.org/) e instale a versão mais recente compatível com seu sistema operacional.

### 2. Instale as dependências
Execute os comandos abaixo no terminal para instalar as bibliotecas necessárias:

```bash
pip install flask
pip install flask-sqlalchemy
pip install flask-login
pip install flask-wtf
pip install bootstrap-flask
pip install psycopg2-binary
pip install flask-mail
pip install flask-jwt-extended
pip install cryptography
pip install flask-restful
pip install numpy
pip install pandas
pip install scikit-learn
pip install notebook
pip install matplotlib

----

### 3. Configure o Banco de Dados

O banco de dados utilizado no projeto é o **PostgreSQL**, gerenciado através do **pgAdmin**. Siga os passos abaixo para configurar:

1. Instale o **PostgreSQL** e o **pgAdmin** em seu sistema.
2. Crie um banco de dados específico para o projeto.
3. Ajuste as credenciais de acesso no código da aplicação para conectar ao banco criado.

---

## Como Executar

1. Certifique-se de que todas as dependências estão instaladas e o banco de dados está configurado corretamente.
2. Inicie a aplicação executando o arquivo principal com o comando:

   ```bash
   python app.py

---
Tecnologias Utilizadas
Python - Linguagem de programação.
Flask - Framework web.
PostgreSQL - Banco de dados relacional.
pgAdmin - Interface para gerenciamento do banco de dados.

---
Tecnologias Utilizadas
Python - Linguagem de programação.
Flask - Framework web.
PostgreSQL - Banco de dados relacional.
pgAdmin - Interface para gerenciamento do banco de dados.

---
