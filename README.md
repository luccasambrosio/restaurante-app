# Projeto Fullstack - Restaurante (Java + React + Docker)

Aplicação fullstack para gerenciamento de restaurante utilizando **Java Spring Boot** no backend, **Next.js** com **React** e **PostgreSQL** como banco de dados. O projeto é **totalmente containerizado** com **Docker** e **Docker Compose**, proporcionando um ambiente de desenvolvimento isolado e de fácil replicação.

## Tecnologias
- Backend: Java Spring Boot
- Frontend: Next.js + React + Tailwind
- Banco: PostgreSQL + Flyway
- Containerização: Docker e Docker Compose

## Dockerização e remodelação e união dos projetos filhos
- restaurante-next (frontend)
- restauranteAPI Private (backend)
- Restaurante (aplicação monolítica versão antiga)

## Bash rodar a aplicação com Docker Compose:

```
git clone https://github.com/luccasambrosio/restaurante-app.git
cd restaurante-app
cp .env.example .env  # (editar o .env se necessário)
docker-compose -f docker-compose.prod.yml up -d --build
```
---

