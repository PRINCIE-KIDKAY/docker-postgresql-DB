# PostgreSQL + Adminer Docker Setup

This project provides a simple `docker-compose` setup for running a PostgreSQL database with Adminer (a lightweight database management tool).

## 📦 Requirements

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🚀 Getting Started

### 1. Clone this repository (or copy the `docker-compose.yml` to your project)

# bash
- git clone https://github.com/PRINCIE-KIDKAY/docker-postgresql-DB.git
- cd your-project-directory


## Start the containers
`docker-compose up -d`

## this will Start a PostgreSQL container with:

- Username: postgres
- Password: 123456
- Database: postgres
- Exposed on localhost:5532
Start Adminer on localhost:8180

# Access the services
- Adminer UI: Open your browser and go to `http://localhost:8180`

# Adminer login details:
- System: PostgreSQL
- Server: db (or localhost if connecting from host)

- Username: postgres
- Password: 123456
- Database: postgres

# Stop the containers

`docker-compose down`