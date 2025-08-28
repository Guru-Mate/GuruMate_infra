# GuruMate_infra

# infra
Organization-wide infra repo (Docker Compose, IaC, monitoring, deploy scripts).

## Run (local)
```bash
docker compose -f docker-compose.yml -f compose.override.local.yml up -d --build
