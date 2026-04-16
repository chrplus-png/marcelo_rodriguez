# Marcelo A. Rodriguez - Portfolio Audiovisual

Portfolio profesional de Editor Audiovisual y Postproductor con más de 20 años de experiencia en televisión y cine.

## Stack

- HTML5 semántico
- CSS3 (sin frameworks)
- JavaScript vanilla
- Font Awesome 6 para iconos

## Estructura del Proyecto

```
marcelo-portfolio/
├── index.html          # Página principal
├── README.md           # Este archivo
├── LICENSE             # Licencia MIT
└── assets/
    ├── videos/         # Carpeta para videos (agregar aquí)
    └── IMG_2438.jpg    # Foto de perfil
```

## Agregar Videos

1. Colocar los archivos de video en `assets/videos/`
2. Actualizar la variable `videoPath` en `index.html` si es necesario:
   ```javascript
   const videoPath = './assets/videos/';
   ```
3. Los formatos soportados son: `.mp4`, `.webm`, `.ogg`

## Generar Miniaturas

El portfolio incluye un sistema de captura de miniaturas. Para generar las miniaturas de los videos:

1. Abrir `index.html` en un navegador
2. Hacer clic en el botón "Generar Miniaturas" que aparece en la sección Trabajos
3. Se capturará automáticamente un frame de cada video
4. Las miniaturas se guardan en el navegador (localStorage) y se reutilizan

**Nota:** Es necesario reproducir brevemente cada video para capturar el frame.

## Personalización

### Colores
Modificar las variables CSS en `:root`:
```css
:root {
    --bg-primary: #0a0a0a;
    --accent-gold: #c9a227;
    /* etc */
}
```

### Datos de Contacto
Buscar y reemplazar en `index.html`:
- Email: `chrplus@gmail.com`
- Teléfono: `+54 11-5709-0608`
- Instagram: `@marceloa._rodriguez`

## Deployment

Este sitio puede hospedarse gratuitamente en:
- **GitHub Pages**: Settings > Pages > Deploy from branch
- **Netlify**: Arrastrar la carpeta completa
- **Vercel**: `vercel deploy`

## Licencia

MIT License - Libre uso para fines personales y comerciales.
