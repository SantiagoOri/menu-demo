# Menú Digital Demo · Cocina “La Tradición”

Este es el **Menú Demo General** diseñado para mostrar a prospectos y dueños de locales de comida todas las funciones activas del sistema:

- **Precios y cálculo automático** en el carrito (incluyendo opciones y extras con costo adicional como `+$15`).
- **Aviso / promoción del día** activo en la parte superior.
- **Carrusel de "Lo más pedido"** (platillos destacados).
- **Ejemplo de platillo agotado** (*Hojaldra con Mole* marcado como `"Disponible": "NO"` → muestra *"Hoy no hay"*).
- **Ruleta interactiva ("🎲 ¿Qué pido?")** y buscador en tiempo real.
- **Sección de Opiniones** con calificación promedio, barras de estrellas y reseñas de muestra.
- **Información completa del negocio** (WhatsApp, Horario, Mapa, Métodos de pago, Redes sociales).
- **Póster QR (`qr.html`)** y **Guía para el dueño (`ayuda.html`)**.

## Archivos clave

| Archivo | Función |
|---|---|
| `index.html`, `estilos.css`, `app.js` | Estructura, diseño y lógica del menú interactivo. |
| `menu-respaldo.js` | Datos del menú demo (platillos, precios, opciones, ajustes y opiniones de muestra). |
| `configuracion.js` | Conexión opcional a Google Sheets y Google Forms (vacío en el demo para usar `menu-respaldo.js`). |
| `fotos/` | Fotografías optimizadas de los platillos. |
| `qr.html` | Generador de póster con código QR listo para imprimir o descargar. |
| `ayuda.html` | Instructivo paso a paso para mostrarle al dueño lo fácil que es administrar su menú. |
| `administracion/configurar-google.gs` | Script automatizado de Google Apps Script para crear la hoja, carpeta de Drive y formulario de un cliente nuevo. |
