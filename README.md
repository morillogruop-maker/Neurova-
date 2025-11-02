# Neurova-
Neurova
# Neurova Group — Next.js + Tailwind + API + Postgres + RL + Turnstile + Resend + Stripe

Infraestructura web lista para producción. Landing, captura de leads, pricing con Stripe, panel admin, CI/CD con Vercel.

## Stack
- **Web**: Next.js (App Router), React, TailwindCSS
- **API**: Rutas `app/api/*`
- **DB**: Postgres (Neon). SSL requerido
- **Seguridad**: Rate-limit Upstash Redis + fallback en memoria, Cloudflare Turnstile invisible, honeypot
- **Email**: Resend (autorespuesta + alerta de lead y orden)
- **Pagos**: Stripe Checkout (suscripción o pago único con `price_*`)
- **CI/CD**: GitHub Actions + Vercel
- **SEO**: `public/robots.txt`, `public/sitemap.xml`

## Estructura
