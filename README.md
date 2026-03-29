# CodeDeployer 2

> CI/CD automation with staging environments and rollback support

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Node.js, TypeScript, Bull, Redis

## 🏗️ Architecture
Backend service with Node.js, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/codedeployer-2
cd codedeployer-2

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
