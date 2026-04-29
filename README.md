# respondeya-legal

Documentos legales de RespondeYA, servidos en `legal.respondeya.es`.

## 📄 Contenido

- `aviso-legal.html` — Aviso Legal (LSSI Art. 10)
- `privacidad.html` — Política de Privacidad (RGPD Art. 13-14)
- `cookies.html` — Política de Cookies (LSSI Art. 22)
- `terminos.html` — Términos y Condiciones del Servicio
- `reembolsos.html` — Política de Reembolsos
- `dpa.html` — Acuerdo de Encargado del Tratamiento (RGPD Art. 28)
- `index.html` — Página de listado

## 🚀 Despliegue

Auto-deploy en Vercel con cada push a `main`.

**Configuración Vercel** (`vercel.json`):
- `cleanUrls: true` → URLs sin `.html`
- Security headers (HSTS, X-Content-Type-Options, etc.)

**Dominio**: `legal.respondeya.es` (CNAME → cname.vercel-dns.com)

## ✏️ Cómo modificar un documento

1. Edita el archivo `.html` correspondiente
2. Commit + push
3. Vercel redeploya automáticamente

## ⚖️ Información legal

- **Titular**: Xavier Julià Giménez
- **NIF**: 77114546P
- **Dirección**: C. Sant Tomàs, 10, 08730 Santa Margarida i els Monjos, Barcelona
- **Email**: hola@respondeya.es

## 📅 Historial

- **v1.0 — 29 de abril de 2026**: documentos iniciales pre-Stripe LIVE.
