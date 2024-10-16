# Simple CRUD

![let's code](https://media.giphy.com/media/HscDLzkO8EOTmgkhQP/giphy.gif?cid=ecf05e47heqzh377n09mrb4emybd32kulxg8ho8mdutap8e2&ep=v1_gifs_search&rid=giphy.gif&ct=g)

This repository contains a simple CRUD project built using Java Spring. The aim of this repository is to practice and
share how you can build all CRUD Methods using Java Spring.

This project was build during a [live in my Youtube Channel](https://www.youtube.com/watch?v=tP6wtEaCnSI).

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [API Endpoints](#api-endpoints)
- [Database](#database)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Maria-Eduarda-Rodrigues-Schwinn/spring-boot-crud-migrations.git
```

2. Install dependencies with Maven

## Usage

1. Start the application with Maven
2. The API will be accessible at http://localhost:8080

## API Endpoints

The API provides the following endpoints:

```markdown
GET / - Retrieve a list of all data.

POST / - Register a new data.

PUT / - Alter data.

DELETE / - Delete data.
```

## Database

The project utilizes PostgresSQL as the database. The necessary database migrations are managed using Flyway.

To [install PostgresSQL])(https://www.postgresql.org/download/) you can install here.
