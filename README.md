# Chat SQL Project

This project is designed to facilitate interaction with SQL databases using natural language queries. It leverages the power of [Langchain] and [SQLAlchemy](https://www.sqlalchemy.org/) to create a seamless experience for users who want to query databases without writing SQL code.

## Features

- Connect to either a local SQLite database or a MySQL database.
- Use natural language to query the database.
- Supports zero-shot learning for SQL query generation.

## Requirements

To run this project, you need the following Python packages:

- langchain
- python-dotenv
- langchain-community
- langchain-groq
- SQLAlchemy

You can install these packages using pip:

```bash
pip install -r requirements.txt
```
# Setup
1. Clone the repository:

```
git clone https://github.com/shrchrds/Chat-SQL.git
cd Chat-SQL
```

2. Configure the Database:
    For SQLite:
        Ensure Sales.db is located in the project directory.
    
    For MySQL:
        Provide the MySQL connection details in the sidebar when running the app.
3. Run the Application:Use the following command to start the application:

```
streamlit run app.py
```

