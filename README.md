# El Kybalión — Manual del Cambio Mental 🔮

**PWA interactiva sobre los 7 Principios Herméticos del Kybalión**

Desarrollada por **Vibras Positivas HM**

---

## ¿Qué es esta app?

Una Progressive Web App (PWA) auto-instalable que presenta las 7 Leyes Herméticas del Kybalión como un **manual práctico de transformación mental**. Funciona offline, es instalable desde el navegador y está optimizada para móvil.

## Contenido

- 📖 **Introducción** al Kybalión y su origen hermético
- ⚖️ **7 Leyes Herméticas completas** con explicación, axiomas, aplicación práctica y mantras
  1. El Mentalismo — *El Todo es Mente*
  2. La Correspondencia — *Como es arriba, es abajo*
  3. La Vibración — *Todo se mueve, todo vibra*
  4. La Polaridad — *Todo tiene dos polos*
  5. El Ritmo — *Todo fluye y refluye*
  6. Causa y Efecto — *Todo tiene su causa*
  7. El Género — *La unión creadora*
- 🔮 **Herramienta de Reflexión Guiada** — preguntas por ley
- ✨ **Afirmaciones Herméticas** — una por cada ley
- 📲 **Instalable como app** (PWA auto-instalable)
- 🌐 **Funciona offline** con Service Worker

## Instalación y Despliegue

```bash
# Subir los archivos a Netlify o GitHub Pages
# No requiere build — es HTML puro

# Estructura de archivos:
# /index.html       → App principal
# /manifest.json    → Configuración PWA
# /sw.js            → Service Worker (offline)
# /icons/           → Íconos de la app
# /README.md        → Este archivo
```

### Netlify (Recomendado)
1. Arrastra la carpeta completa a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Configurar dominio personalizado si lo deseas

### GitHub Pages
1. Subir todos los archivos al repositorio
2. Activar GitHub Pages en Settings → Pages

## Tecnologías

- HTML5 / CSS3 / Vanilla JS puro
- Google Fonts (Cinzel Decorative, Cinzel, Crimson Pro)
- PWA: Web App Manifest + Service Worker
- Intersection Observer API (animaciones)
- Sin dependencias externas

## Personalización

Ajusta en `index.html`:
- `--gold`, `--crimson`, `--black` → paleta de colores
- Contenido de reflexiones en el objeto `reflections`
- Afirmaciones en las tarjetas `.affirmation-card`

---

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**  
📞 3117700431 | haroldco45@gmail.com
