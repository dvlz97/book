# Book de Referencia — Daniela Andrea Racero Vélez

Portfolio profesional digital para Comunicadora Social con énfasis en Comunicación Estratégica e Institucional.

## 🚀 Publicar en GitHub Pages

### Opción 1 — Subir archivos directamente (más fácil)

1. Ve a https://github.com/dvlz97/book
2. Sube todos los archivos de esta carpeta:
   - `index.html` (en la raíz)
   - `css/style.css`
   - `js/main.js`
3. Ve a **Settings → Pages**
4. En "Source" selecciona **Deploy from a branch**
5. Rama: `main`, carpeta: `/ (root)`
6. Guarda. En ~2 minutos el sitio estará en: `https://dvlz97.github.io/book`

### Opción 2 — Git desde terminal

```bash
git clone https://github.com/dvlz97/book
cd book
# Copia los archivos aquí
git add .
git commit -m "Book de referencia - primera versión"
git push origin main
```

Luego activa Pages desde Settings como en la Opción 1.

## 📁 Estructura del proyecto

```
book/
├── index.html          ← Página principal
├── css/
│   └── style.css       ← Todos los estilos
├── js/
│   └── main.js         ← Interacciones
└── README.md
```

## ✨ Características

- Diseño mobile-first, 100% responsivo
- Filtros interactivos por sector/cliente
- Animaciones suaves al hacer scroll
- Modo claro con paleta elegante negro/dorado
- Secciones: Perfil · Experiencia · Proyectos · Herramientas · Contacto
- Compatible con todos los navegadores modernos
