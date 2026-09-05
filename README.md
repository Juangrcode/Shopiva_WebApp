# Shopiva — Landing

Sitio web oficial de **Shopiva** (*Lo que quieres, donde quieras*). Tienda online en Colombia con pago contra entrega.

Es un sitio **estático** (un solo `index.html` + imágenes en `assets/`). No necesita build ni framework.

```
SHOPIVA/
├─ index.html          ← la landing
├─ assets/
│  ├─ isotipo.png      ← logo (nav, hero, favicon)
│  ├─ shopiva-cover.png← portada (og:image para redes)
│  └─ shopiva-logo.png ← logo completo
└─ README.md
```

## ✅ Antes de publicar — reemplaza estos datos

Abre `index.html` y cambia (busca el texto):

- **WhatsApp:** `+57 300 000 0000` y el enlace `https://wa.me/57XXXXXXXXXX` (pon tu número real, formato `57` + número sin espacios).
- **Correo:** `hola@shopiva.co`
- **Ciudad:** `Ciudad, Colombia`
- (Opcional) precios y descripciones de los productos.

## 🚀 Subir a GitHub + Vercel

**1. Crear el repo en GitHub**
```bash
cd ~/projects/SHOPIVA
git init
git add .
git commit -m "Shopiva landing"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/shopiva.git
git push -u origin main
```

**2. Deploy en Vercel**
- Entra a [vercel.com](https://vercel.com) → **Add New → Project** → importa el repo `shopiva`.
- Framework Preset: **Other** (es estático). Root Directory: `/`. No hay build command.
- **Deploy.** Vercel te da una URL tipo `https://shopiva.vercel.app`.

**3. (Opcional) dominio propio**
- En Vercel → Project → **Settings → Domains** → agrega tu dominio (ej. `shopiva.co`).

## 📌 Para recuperar la cuenta de WhatsApp restringida

1. Verifica que la URL cargue en **incógnito** (sin login ni error).
2. En Meta → perfil comercial de **Shopiva** → **Sitio web** → pega la URL de Vercel.
3. Solicita revisión. Espera 24–72 h.
