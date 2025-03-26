# Product Landing Page

## Descripción
Este proyecto es una página de aterrizaje para un producto, implementando HTML5 semántico y CSS con Flexbox para una estructura adaptable y accesible.

## Estructura del Proyecto
```
product-landing-page/
├── index.html
├── css/
│   └── styles.css
├── img/
└── README.md
```

## Tecnologías Utilizadas
- HTML5 Semántico
- CSS3 con Flexbox
- Media Queries para adaptabilidad

## Media Queries Implementadas
Se han definido los siguientes `breakpoints` en `styles.css` para mejorar la adaptabilidad:

```css
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
        align-items: center;
    }
    
    .gallery-container {
        flex-direction: column;
        align-items: center;
    }
    
    .testimonials-container {
        flex-direction: column;
        align-items: center;
    }
}
```

## Accesibilidad
- Uso de etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- Atributos `alt` en todas las imágenes.


