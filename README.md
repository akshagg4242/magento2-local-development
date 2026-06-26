# Magento 2 Local Development (Docker)

## Overview

This project provides a Docker-based local Magento 2 development environment configured with PHP, MariaDB, Elasticsearch, and phpMyAdmin.

---

## Technologies & Versions

| Service            | Version                      |
| ------------------ | ---------------------------- |
| Magento            | 2.4.5                        |
| Docker             | 29.5.3                       |
| Docker Compose     | v5.1.4                       |
| PHP                | 8.3.31                       |
| Composer           | 2.10.1                       |
| MariaDB            | 10.6.27                      |
| Elasticsearch      | 7.9.0                        |
| phpMyAdmin         | 5.2.3                        |
| Apache + PHP Image | webdevops/php-apache-dev:8.3 |

---

## Features

* Magento 2 local development environment
* Docker-based setup
* MariaDB database
* Elasticsearch integration
* phpMyAdmin support
* Apache + PHP container
* Isolated local environment

---

## Prerequisites

Install:

* Docker Desktop
* Git

Verify installation:

```bash
docker --version
docker compose version
```

---

## Clone Repository

```bash
git clone https://github.com/akshagg4242/magento2-local-development.git
cd magento2-local-development
```

---

## Project Structure

```text
magento2-local-development/
├── src/
├── docker-compose.yml
├── README.md
└── setup-guide.md
```

---

## Start Environment

```bash
docker compose up -d
```

Verify containers:

```bash
docker compose ps
```

---

## Stop Environment

```bash
docker compose down
```

---

## Access Services

Magento Storefront:

```text
http://localhost:8090
```

Magento Admin Panel:

```text
http://localhost:8090/admin
```

phpMyAdmin:

```text
http://localhost:8080
```

Elasticsearch:

```text
http://localhost:9200
```

---

## Database Configuration

Database Host:

```text
mysql
```

Database Port:

```text
3306
```

Database Name:

```text
magento2.4.5
```

Username:

```text
root
```

Password:

```text
root
```

---

## Setup Steps

1. Clone repository
2. Navigate into project folder
3. Start Docker containers
4. Open Magento storefront
5. Verify Admin login
6. Verify database access via phpMyAdmin
7. Confirm Elasticsearch is running

---

## Documentation

Additional setup screenshots and step-by-step installation details are included in this repository.

---

## Status

Setup completed and verified successfully for local Magento 2 development.
