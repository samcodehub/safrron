# Azafrán Premium Argentina - Website

Este es un sitio web de muestra para la venta de productos de azafrán en Argentina. El sitio está diseñado para ser atractivo visualmente y proporcionar toda la información necesaria sobre productos de azafrán premium.

## Características

- Diseño moderno y responsivo
- Secciones para mostrar productos, beneficios, recetas y más
- Formulario de contacto
- Suscripción a boletín informativo
- Navegación suave
- Compatibilidad con dispositivos móviles

## Estructura de Archivos

- `index.html` - Estructura principal del sitio web
- `styles.css` - Estilos y diseño visual
- `script.js` - Funcionalidades interactivas
- `README.md` - Este archivo de documentación

## Personalización

### Productos

Para añadir o modificar productos, edita la sección con el ID `productos` en el archivo `index.html`. Cada producto está contenido en un elemento con la clase `product-card`. Puedes duplicar estos elementos para añadir más productos.

```html
<div class="product-card">
    <div class="product-image">
        <img src="ruta-a-la-imagen" alt="Nombre del Producto">
    </div>
    <div class="product-info">
        <h3>Nombre del Producto</h3>
        <p class="product-description">Descripción del producto.</p>
        <p class="product-price">$Precio ARS</p>
        <a href="#" class="btn btn-secondary">Comprar Ahora</a>
    </div>
</div>
```

### Imágenes

Actualmente, el sitio utiliza imágenes de marcador de posición de [placeholder.com](https://placeholder.com/). Para una versión de producción, deberías reemplazar estas imágenes con fotografías reales de tus productos de azafrán.

```html
<!-- Reemplaza esto: -->
<img src="https://via.placeholder.com/300x200" alt="Azafrán en Hebras Premium">

<!-- Con esto: -->
<img src="img/producto1.jpg" alt="Azafrán en Hebras Premium">
```

### Colores

Los colores del sitio se definen como variables CSS en el archivo `styles.css`. Puedes modificar estos valores para cambiar el esquema de colores.

```css
:root {
    --primary-color: #c94618;     /* Color principal (rojo-naranja) */
    --secondary-color: #fcb900;   /* Color secundario (amarillo) */
    --accent-color: #8a1538;      /* Color de acento (rojo oscuro) */
    --text-color: #333333;        /* Color de texto principal */
    --light-text: #ffffff;        /* Color de texto claro */
    --background-color: #faf7f2;  /* Color de fondo */
    --dark-background: #2c2c2c;   /* Color de fondo oscuro */
    /* ... otros colores ... */
}
```

## Funcionalidades Pendientes

Para una versión completa del sitio, considera añadir:

1. Integración con un sistema de pagos
2. Carrito de compras
3. Sistema de gestión de inventario
4. Integración con redes sociales
5. Blog con información sobre el azafrán

## Créditos

- Fuentes: [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)
- Iconos: Emojis Unicode estándar (pueden ser reemplazados por un conjunto de iconos)
- Imágenes: Marcadores de posición de [placeholder.com](https://placeholder.com/)

## Licencia

Este proyecto es solo una demostración y puede ser modificado y utilizado según sea necesario. 