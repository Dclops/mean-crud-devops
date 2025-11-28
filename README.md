# MEAN Stack CRUD Application with DevOps Pipeline

![MEAN Stack](https://img.shields.io/badge/MEAN-Stack-green)
![Docker](https://img.shields.io/badge/Docker-Containers-blue)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub%20Actions-yellow)

A complete full-stack MEAN (MongoDB, Express.js, Angular, Node.js) application with full CRUD operations, containerized with Docker, and deployed to AWS EC2 with automated CI/CD pipeline.

## 🏗️ Architecture

```
Frontend (Angular) → Backend (Express.js) → Database (MongoDB)
       ↓                   ↓                       ↓
   Docker Container ← Docker Compose → Docker Container
       ↓                   ↓                       ↓
        AWS EC2 Instance (16.112.109.177)
```

## 🚀 Quick Start

### Access the Deployed Application

**Frontend (Web Interface):**
```
http://16.112.109.177:4200
```

**Backend API:**
```
http://16.112.109.177:8080/api/tutorials
```

### API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/tutorials` | Get all tutorials |
| GET | `/api/tutorials/:id` | Get tutorial by ID |
| POST | `/api/tutorials` | Create new tutorial |
| PUT | `/api/tutorials/:id` | Update tutorial |
| DELETE | `/api/tutorials/:id` | Delete tutorial |
| GET | `/api/tutorials/published` | Get published tutorials |

### Example API Usage

```bash
# Get all tutorials
curl http://16.112.109.177:8080/api/tutorials

# Create new tutorial
curl -X POST http://16.112.109.177:8080/api/tutorials \
  -H "Content-Type: application/json" \
  -d '{"title": "New Tutorial", "description": "Tutorial description"}'
```
