PULSEWEBPRO — Starter listo para Vercel
1) Sube /web y /api a este repositorio (Add file → Upload).
2) En Vercel crea 2 proyectos desde este repo:
   - Front (root: /web) → añade dominio pulsewebpro.com
   - API  (root: /api)
3) En Squarespace DNS:
   - CNAME www → cname.vercel-dns.com
   - CNAME *   → cname.vercel-dns.com   (wildcard)
   - A @       → 76.76.21.21
4) Prueba: https://pulsewebpro.com
5) Cuando actives Stripe, pega los Payment Links en /web/index.html y completa .env en el proyecto API.
