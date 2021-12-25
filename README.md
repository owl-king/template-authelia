# Authelia for single server

Note: This setup is for single server only which no HA in place. Please consider Kubernetes or Docker swarm to have more resilience on your setup

This module includes:

- Authelia with basic setup
- Redis
- Local file as storage ( Please consider Remote DB if you already have one)
- Configs with traefik ( Basic setup with traefik can be found [Template Traefik](https://github.com/owl-king/template-traefik) )

## Deployment

```bash
# Deploy traefik repo first
# Create .env from .env.example
docker-compose up -d 			# Deploy containers
```
