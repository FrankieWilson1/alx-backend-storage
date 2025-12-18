# 🗄️ ALX Backend Storage

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg?style=flat&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Advanced-orange.svg?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-NoSQL-green.svg?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-In--Memory-red.svg?style=flat&logo=redis&logoColor=white)

This repository contains projects and exercises for the **ALX Software Engineering Program**, specifically focusing on backend storage technologies. It covers the implementation, management, and interaction with Relational Databases (MySQL), NoSQL Databases (MongoDB), and In-memory Data Stores (Redis) using **Python**.

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
  - [MySQL Advanced](#mysql-advanced)
  - [NoSQL (MongoDB)](#nosql-mongodb)
  - [Redis Basic](#redis-basic)
- [Installation & Setup](#installation--setup)
- [Learning Objectives](#learning-objectives)
- [Author](#author)

## 🔍 Project Overview
The goal of this repository is to demonstrate proficiency in backend data management. It progresses from advanced SQL concepts (optimization and automation) to modern NoSQL document storage, and finally to high-performance caching mechanisms using Redis.

## 🛠️ Technologies Used
- **Language:** Python 3.x
- **DBMS:** MySQL 5.7 / 8.0
- **NoSQL:** MongoDB
- **Cache:** Redis
- **Libraries:**
  - `mysql-connector-python`
  - `pymongo`
  - `redis`

## 📂 Project Structure

### 1. MySQL Advanced
Focuses on optimizing database performance and automating tasks within the database engine.
- **Key Concepts:**
  - **Constraints:** Ensuring data integrity.
  - **Indexes:** Optimizing query performance.
  - **Stored Procedures & Functions:** Encapsulating logic on the DB side.
  - **Views:** Creating virtual tables for simplified access.
  - **Triggers:** Automating responses to data changes.

### 2. NoSQL (MongoDB)
Introduction to non-relational databases and document storage.
- **Key Concepts:**
  - ACID vs BASE models.
  - CAP Theorem.
  - Creating, Reading, Updating, and Deleting (CRUD) documents.
  - Advanced querying and aggregation in MongoDB.

### 3. Redis Basic
Implementation of caching and basic data structure manipulation in memory.
- **Key Concepts:**
  - Redis strings, lists, sets, and hashes.
  - Caching strategies.
  - Python integration using `redis-py`.

## ⚙️ Installation & Setup

To run the scripts in this repository, ensure you have the necessary services running and Python libraries installed.

### Prerequisites
```bash
# Update package lists
sudo apt-get update

# Install Python 3 and pip
sudo apt-get install python3 python3-pip
```

### Install Dependencies
```bash
pip3 install mysql-connector-python pymongo redis
```

### Service Setup (Linux/Ubuntu)
```bash
# MySQL
sudo service mysql start

# MongoDB
sudo service mongod start

# Redis
sudo service redis-server start
```

## 🧠 Learning Objectives
By the end of these projects, the following concepts are mastered:
1.  **Relational vs. Non-Relational:** Understanding when to use SQL vs. NoSQL.
2.  **Optimization:** How to make queries faster using indexes and caching.
3.  **Data Integrity:** Enforcing rules directly at the database level.
4.  **Automation:** Using triggers and stored procedures to reduce application-side logic.

### Note:
Migrated from early ALX backend specialization (2024). Demonstrates practical implementations organized into three main modules: MySQL Advanced (covering constraints, indexes, stored procedures, views, and triggers), NoSQL fundamentals (covering NoSQL concepts, document storage, MongoDB), and Redis basic operations

## 👤 Author
**Frankie Wilson**
- GitHub: [@realFrankieWilson](https://github.com/realFrankieWilson)
