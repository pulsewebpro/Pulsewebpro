# Pulsewebpro API (estructura)
Endpoints a implementar en siguiente versión:
- POST /api/blueprint → genera JSON desde 3 preguntas
- POST /api/render → inyecta JSON y crea ZIP único (subida a S3/R2)
- POST /api/stripe/webhook → entrega ZIP o publica subdominio
- POST /api/provision-subdomain → despliegue en Vercel con token
Variables en .env.example ya preparadas.
