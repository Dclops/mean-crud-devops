# MEAN Stack CRUD Application with DevOps Pipeline

## Live Deployment

**Frontend:** http://16.112.109.177:4200
**Backend API:** http://16.112.109.177:8080/api/tutorials

## Features

- Full CRUD Operations (Create, Read, Update, Delete)
- RESTful API with MongoDB
- Docker Containerization
- AWS EC2 Deployment
- GitHub Actions CI/CD Pipeline

## API Endpoints

- GET /api/tutorials - Get all tutorials
- POST /api/tutorials - Create new tutorial
- GET /api/tutorials/:id - Get tutorial by ID
- PUT /api/tutorials/:id - Update tutorial
- DELETE /api/tutorials/:id - Delete tutorial

## Quick Test

\`\`\`bash
# Test API
curl http://16.112.109.177:8080/api/tutorials

# Test Frontend
curl http://16.112.109.177:4200
\`\`\`

## Technology Stack

- Frontend: Angular, HTML5, CSS3, nginx
- Backend: Node.js, Express.js, MongoDB
- DevOps: Docker, Docker Compose, AWS EC2, GitHub Actions
