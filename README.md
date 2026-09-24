# Coolify Lab

Frontend estático para el Taller 1 de PaaS. Está preparado para desplegarse en
Coolify mediante el `Dockerfile` incluido.

## Desarrollo local

```bash
python3 -m http.server 8080
```

Luego abre `http://localhost:8080`.

## Despliegue en Coolify

- Build pack: Dockerfile
- Puerto del contenedor: `80`
- Health check: `/`
