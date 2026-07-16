# 📖 AWESOME_TOOLS.md - Curated Developer Tools

**Your complete reference for dev tools & commands**

---

## 🎯 Quick Navigation

- [Frontend](#frontend-tools)
- [Backend](#backend-tools)
- [DevOps](#devops-tools)
- [AI & Code Intelligence](#ai--code-intelligence)
- [Databases](#database-tools)
- [Testing](#testing-tools)
- [Productivity](#productivity-tools)
- [Commands](#useful-commands-cheatsheet)

---

## 🎨 Frontend Tools

### Framework Starters

```bash
# Next.js (Recommended)
npx create-next-app@latest --typescript

# Vite + React
npm create vite@latest my-app -- --template react

# Vue + Nuxt  
npx nuxi@latest init my-app
```

### Essential npm Packages

```json
{
  "dependencies": {
    "react": "^18.2.0",
    "next": "^14.0.0",
    "tailwindcss": "^3.3.0",
    "zod": "^3.22.0",
    "react-hook-form": "^7.46.0",
    "zustand": "^4.4.0",
    "@tanstack/react-query": "^5.0.0",
    "axios": "^1.5.0"
  },
  "devDependencies": {
    "typescript": "^5.2.0",
    "eslint": "^8.49.0",
    "prettier": "^3.0.0",
    "vitest": "^0.34.0"
  }
}
```

---

## 🔧 Backend Tools

### Node.js Frameworks

```javascript
// Express
const express = require('express');
const app = express();
app.listen(3000);

// NestJS
import { Controller, Get } from '@nestjs/common';
@Controller('api')
export class AppController { }

// Fastify
const fastify = require('fastify')()
fastify.listen({ port: 3000 })
```

### Python Packages

```bash
# FastAPI
pip install fastapi uvicorn sqlalchemy psycopg2-binary

# Django
pip install django djangorestframework

# Data Science
pip install pandas numpy scikit-learn tensorflow
```

### Go Setup

```bash
# Gin
go get -u github.com/gin-gonic/gin

# Fiber
go get -u github.com/gofiber/fiber/v2

# Database
go get github.com/lib/pq
go get gorm.io/gorm
```

---

## 🚀 DevOps Tools

### Docker Commands

```bash
# Build
docker build -t myapp:1.0 .

# Run
docker run -p 3000:3000 myapp:1.0

# Compose
docker-compose up -d
docker-compose down

# Logs
docker logs -f container_id
```

### Kubernetes Commands

```bash
# Deploy
kubectl create deployment myapp --image=myapp:1.0

# Scale
kubectl scale deployment myapp --replicas=3

# Service
kubectl expose deployment myapp --type=LoadBalancer
```

### Terraform Example

```hcl
resource "aws_instance" "app" {
  ami           = "ami-0c55b159cbfafe1f0"
  instance_type = "t2.micro"
  tags = {
    Name = "antigravity-app"
  }
}
```

---

## 🤖 AI & Code Intelligence

### Graphify Installation

```bash
# Clone
git clone https://github.com/Graphify-Labs/graphify.git
cd graphify

# Install
npm install

# Index codebase
npx graphify index /path/to/codebase
```

### Cursor Setup

```bash
# Download from https://cursor.so
# Install and authenticate
# Use Ctrl+K for AI edit
```

### Tabnine Extension

```bash
# VS Code
code --install-extension TabNine.tabnine-vscode

# Configure
{
  "tabnine.experimentalAutoImports": true
}
```

---

## 📦 Database Tools

### PostgreSQL

```bash
# Connect
psql -U username -d database_name -h localhost

# Create DB
CREATE DATABASE mydb;

# Create table
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  email VARCHAR(255) UNIQUE,
  created_at TIMESTAMP DEFAULT NOW()
);
```

### MongoDB

```bash
# Shell
mongosh

# Create DB
use mydb

# Insert
db.users.insertOne({ email: "test@example.com" })

# Query
db.users.find()
```

### Prisma Migration

```bash
# Init
npx prisma init

# Migrate
npx prisma migrate dev --name init

# Generate
npx prisma generate
```

---

## ✅ Testing Tools

### Jest Setup

```bash
npm install --save-dev jest @testing-library/react

# jest.config.js
module.exports = {
  testEnvironment: 'jsdom',
  moduleNameMapper: {
    '\\.(css)$': 'identity-obj-proxy',
  },
};
```

### Pytest Setup

```bash
pip install pytest pytest-cov

# Run
pytest -v
pytest --cov
```

### Cypress E2E

```bash
npm install --save-dev cypress
npx cypress open
```

---

## 🎯 Productivity Tools

### Git Aliases

```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.unstage 'reset HEAD --'
```

### VS Code Top Extensions

- GitHub Copilot
- ESLint
- Prettier
- Python
- Go
- Docker
- Kubernetes Tools

---

## 📋 Useful Commands Cheatsheet

### Docker
```bash
docker ps                     # List containers
docker images                 # List images
docker logs -f <container>    # Follow logs
docker exec -it <c> bash      # Shell into
```

### Git
```bash
git status                    # Status
git log --oneline             # Compact log
git branch -a                 # All branches
git stash                     # Temporary save
```

### Node.js
```bash
node --version                # Check version
npm list -g                   # Global packages
npm outdated                  # Check outdated
```

### Python
```bash
python -m venv venv           # Create env
source venv/bin/activate      # Activate
pip freeze > requirements.txt # Export deps
```

---

**Last Updated:** July 2024
