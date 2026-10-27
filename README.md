# Docker Practice

Part of my Generative AI Engineer learning journey.

## What I practiced
- Wrote a Dockerfile for a small FastAPI app
- Layer order: install dependencies first, then copy code
- Used .dockerignore to keep secrets and notebooks out

## Run
docker build -t docker-demo .
docker run -p 8000:8000 docker-demo
