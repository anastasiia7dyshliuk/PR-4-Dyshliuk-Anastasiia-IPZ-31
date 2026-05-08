# Task Manager — Docker Compose Lab

REST API + PostgreSQL + Frontend, all running in Docker containers.

## Stack
- **Frontend** — HTML/CSS/JS served by nginx
- **API** — Python Flask REST API
- **Database** — PostgreSQL 16

## Project Structure
## Quick Start

1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

2. Create `.env` file
```bash
cp .env.example .env
```

3. Run
```bash
docker compose up -d --build
```

4. Open in browser
- Frontend: http://localhost:8080
- API: http://localhost:5000
- pgAdmin: http://localhost:8888

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /health | Health check |
| GET | /tasks | Get all tasks |
| POST | /tasks | Create task |
| GET | /tasks/:id | Get task by id |
| PUT | /tasks/:id | Update task |
| DELETE | /tasks/:id | Delete task |

## Stop
```bash
docker compose down
```
## Demo
See `video-site` for a recorded demo of the working application.
