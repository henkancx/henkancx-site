# HenkanCX — Sitio principal

Sitio web oficial de **HenkanCX**, copiloto de IA y automatización para Latinoamérica.

🌐 **Live:** [henkancx.com](https://henkancx.com)

## Estética

Single-page editorial dark con paleta del brand book oficial:

- **Midnight Navy** `#0D1B2A` (background dominante)
- **Royal Purple** `#833AE0` + **Magenta Pulse** `#CB6CE6` (acentos / gradientes)
- **Cloud** `#F5F6F8` + **Paper Warm** `#F2F1EE` (secciones intercaladas)

Tipografías:

- **Poppins** (display)
- **Inter** (body)
- **Fira Code** (datos / mono)
- **Instrument Serif** (italic editorial accents)
- **Caveat** (handwritten — para anotaciones humanas)

## Toque humano

- Reloj vivo de Panamá (`PTY HH:MM`) en nav y footer
- Pull quotes editoriales gigantes (Instrument Serif italic) por industria
- Founder note con avatar + firma manuscrita (Caveat)
- Hand-drawn arrow + post-it note flotante en hero
- Microcopia cálida en español latino: "Conversemos", "pinky promise 🤝", "hecho con cariño en Ciudad de Panamá ☀️"
- Avatares del equipo con gradientes magenta/purple

## Estructura

```
henkancx-site/
├── index.html      # Sitio completo (single-file)
├── .nojekyll       # Desactiva Jekyll en GitHub Pages
├── CNAME           # henkancx.com
├── .gitignore
└── README.md
```

Sin build step. Sin frameworks. Sin dependencias externas (solo Google Fonts).

## Secciones

1. **Nav sticky** con backdrop-blur · logo · links · clock PTY · toggle ES/EN · CTA
2. **Hero** dark con statement editorial + CTAs + hand-drawn note
3. **Manifiesto** light con founder card + firma
4. **Soluciones** dark — bento grid de 6 productos
5. **Voces** light — testimonios anónimos por rol/industria estilo editorial
6. **Industrias** dark slim — marquee de sectores
7. **Cómo trabajamos** light — proceso 4 pasos
8. **Resultados** dark — 4 métricas headline
9. **El equipo detrás** light warm — 4 cards humanos
10. **CTA final** dark — "conversamos?"
11. **Footer** dark — links + clock + sociales + "hecho con cariño en Panamá"

## i18n

- Default: ES (auto-detect navegador, fallback ES)
- Toggle ES/EN en nav, persistente con `localStorage` (key: `henkancx_lang`)
- Cubre 130+ strings — toda la UI, copy editorial y testimonios

## Deploy en GitHub Pages

1. **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main` / root (`/`)
4. **Custom domain:** `henkancx.com` (lee del CNAME)
5. **Enforce HTTPS:** ✓

DNS:
```
Tipo:   A (apex)
Nombre: @
Valor:  185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153

Tipo:   CNAME
Nombre: www
Valor:  henkancx.github.io
```

## Contacto

- **Email:** [info@henkancx.com](mailto:info@henkancx.com)
- **WhatsApp:** [+507 6467 1392](https://wa.me/50764671392)
- **LinkedIn:** [linkedin.com/company/henkancx](https://linkedin.com/company/henkancx)
- **Demo Portal:** [demo.henkancx.com](https://demo.henkancx.com)

---

© 2026 HenkanCX · Hecho con cariño en Ciudad de Panamá ☀️
