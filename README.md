# SQL Server to PostgreSQL Migration Pipeline

## Overview
This project demonstrates an end-to-end data migration pipeline for transferring enterprise data from **Microsoft SQL Server** to **PostgreSQL** using **Python and SQL**.

The goal is to design a reproducible, scalable, and production-oriented workflow that handles:
- Data extraction from SQL Server
- Schema and data transformation
- Loading into PostgreSQL
- Basic validation and integrity checks

This mirrors real-world database migration tasks commonly encountered in analytics engineering and data platform modernization projects.

---

## Tech Stack
- **Python 3.11**
- **SQL Server**
- **PostgreSQL**
- **SQLAlchemy**
- **pyodbc**
- **psycopg2**
- **Pandas**
- **Jupyter Notebook**

---

## Project Architecture
SQL Server
↓
[Extract] → Python (SQLAlchemy + pyodbc)
↓
[Transform] → Data type mapping, schema normalization
↓
[Load] → PostgreSQL (psycopg2)


---

## Key Features
- Secure connection handling using environment variables
- Modular ETL design (Extract, Transform, Load)
- SQL Server → PostgreSQL data type compatibility handling
- Reusable migration scripts for multiple tables
- Designed with production data pipelines in mind


