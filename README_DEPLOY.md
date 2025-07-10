# Production Deployment

## Steps

1. Clone the repo and create `.env` file based on `.env.example`
2. Run:
```bash
docker-compose -f docker/docker-compose.prod.yml up -d --build
```
3. Visit the app at `http://localhost`
