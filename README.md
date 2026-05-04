# henkancx-site

Sitio web oficial de **HenkanCX** — _AI-powered customer experience solutions_.

> Este repositorio contiene la versión **mockup / sitio en construcción** que se muestra públicamente mientras se desarrolla el rediseño v2.0 del sitio principal.

---

## 🟠 Estado actual

**Sitio en construcción / Coming soon page**

Página estática única (`index.html`) con:

- Estética editorial dark con acento tangerine (`#FF6B35`)
- Tipografía: Fraunces (display) + JetBrains Mono (UI)
- Toggle bilingüe **ES / EN** con persistencia en `localStorage`
- Reloj en tiempo real (timezone Panamá)
- Barra de progreso animada del rediseño
- Grain texture + vignette para profundidad
- Responsive (mobile-first)
- Cumple `prefers-reduced-motion`

---

## 📁 Estructura

```
henkancx-site/
├── index.html      # Sitio en construcción (single-file, sin dependencias)
├── .nojekyll       # Desactiva Jekyll en GitHub Pages
├── CNAME           # (opcional) dominio custom
└── README.md
```

Sin build step. Sin frameworks. Sin dependencias. Vanilla HTML + CSS + JS.

---

## 🚀 Deploy en GitHub Pages

1. **Settings → Pages**
2. **Source**: Deploy from a branch
3. **Branch**: `main` / root (`/`)
4. (Opcional) **Custom domain**: `henkancx.com` o `coming.henkancx.com`

Una vez activado, el sitio queda disponible en:

```
https://henkancx.github.io/henkancx-site/
```

O en el dominio custom configurado en el archivo `CNAME`.

---

## 🛠️ Desarrollo local

No necesita servidor — abre `index.html` directamente en el navegador.

Para evitar problemas de CORS con fonts en algunos navegadores:

```bash
# Python 3
python3 -m http.server 8080

# Node
npx serve .
```

Luego visita `http://localhost:8080`.

---

## 🎨 Logo

> **Pendiente:** subir el archivo `logo-henkancx.png` (o `.svg`) al directorio raíz para reemplazar el wordmark inline actual.

El sitio en construcción usa por ahora un wordmark tipográfico (`henkan / cx`) construido con Fraunces. Cuando se suba el asset oficial, basta con reemplazar el bloque `.brand` en `index.html`.

---

## 📞 Contacto

- **Email:** [info@henkancx.com](mailto:info@henkancx.com)
- **WhatsApp:** [+507 6467 1392](https://wa.me/50764671392)
- **LinkedIn:** [linkedin.com/company/henkancx](https://linkedin.com/company/henkancx)
- **Instagram:** [@henkancx](https://instagram.com/henkancx)

---

© 2026 HenkanCX · Panamá
