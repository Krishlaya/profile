# 🚀 Portfolio Website (Dockerized)

## 📌 Features
- Fully responsive portfolio (HTML + CSS)
- Dockerized using nginx:alpine
- Live reload using docker-compose

## 🐳 Run with Docker
```bash
docker build -t portfolio:v1 .
docker run -d -p 8080:80 portfolio:v1
