# PROFE ADMIN

Sitio web oficial de **Profe Admin**: educación en administración de empresas. Clases personalizadas, asesorías y herramientas para entender, resolver y aplicar temas de administración.

## Despliegue en GitHub Pages

1. Sube esta carpeta a un repositorio en GitHub.
2. Ve a **Settings > Pages** y selecciona la rama `main` y la carpeta `/ (root)`.
3. Tu sitio estará disponible en `https://tuusuario.github.io/nombre-repo/`.

También puedes abrirlo localmente abriendo `index.html` directamente en el navegador.

## Estructura de archivos

```text
portfolio/
├── index.html              # Página principal (hero, servicios, sobre mí, contacto)
├── foto.jpg                # Fotografía para la sección "Sobre Profe Admin"
├── servicios/
│   ├── clases.html         # Servicio 01: Clases de Administración
│   ├── asesorias.html      # Servicio 02: Asesorías de Administración
│   ├── conferencias.html   # Servicio 03: Conferencias de Administración
│   ├── sistemas.html       # Servicio 04: Sistemas de Administración
│   ├── herramientas.html   # Servicio 05: Herramientas de Administración
│   └── plantillas.html     # Servicio 06: Plantillas de Administración
├── assets/
│   ├── css/
│   │   └── style.css       # Todos los estilos (identidad visual, responsive)
│   ├── js/
│   │   └── script.js       # Menú móvil, animaciones, scrollspy
│   └── img/                # Carpeta para futuras imágenes
└── README.md
```

## Secciones del sitio

- **Inicio (hero):** presentación con acceso directo a servicios y WhatsApp.
- **Servicios:** 6 tarjetas (Clases, Asesorías, Conferencias, Sistemas, Herramientas y Plantillas), cada una con su página propia.
- **Sobre Profe Admin:** presentación personal con fotografía.
- **Contacto:** botón y número de WhatsApp Business.

## Personalización rápida

- **Número / enlace de WhatsApp:** busca y reemplaza `573180335255` en todos los archivos `.html`.
- **Mensajes precargados de WhatsApp:** busca las URLs que empiezan con `https://wa.me/` y modifica el parámetro `text=`.
- **Textos y servicios:** edita el contenido directamente en los archivos `.html`.
- **Foto de perfil:** reemplaza `foto.jpg` en la raíz manteniendo el mismo nombre.
- **Estilos y colores:** variables CSS al inicio de `assets/css/style.css`.

## Notas

- Sitio 100% estático: HTML, CSS y JavaScript puro. No necesita servidor PHP.
- Todas las rutas internas son relativas: compatible con GitHub Pages en subcarpeta (`usuario.github.io/nombre-repo/`).
- Compatible también con Netlify, Vercel o cualquier hosting estático.
- No utiliza base de datos ni framework externo.
- Las redes sociales aparecen como espacios reservados, sin URLs inventadas.
