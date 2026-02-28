# Al-Karamah Teach Smart

## 🌐 Live Demo
**[https://alkaramahack-production.up.railway.app/](https://alkaramahack-production.up.railway.app/)**

## Git Repo
**[https://github.com/safa678545-glitch/AL_karama_hack](https://github.com/safa678545-glitch/AL_karama_hack)**

---

# Docker Run Instructions
## Prerequisites
- Docker installed
## Option A: Docker Compose (recommended)
```bash
docker compose up --build
```
Open: `http://localhost:8080`
Stop:
```bash
docker compose down
```
## Option B: Docker build + run
```bash
docker build -t al-karamah-teach-smart .
docker run --rm -p 8080:8080 al-karamah-teach-smart
```
Open: `http://localhost:8080`
## Optional: Environment Variables
If you want real AI/image features, copy `.env.example` to `.env`, fill it, then:
```bash
docker run --rm -p 8080:8080 --env-file .env al-karamah-teach-smart
```
