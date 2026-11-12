# Capturas

Pantallas que ilustran el proyecto. Las marcadas como listas están en esta carpeta; las demás se
agregarán con el nombre de archivo indicado.

## Criterios para cada captura

- Sin datos reales de clientes: ni nombres, ni teléfonos, ni correos, ni direcciones, ni números
  de orden. En la bandeja y el bot se usa una conversación de prueba.
- Sin la barra de direcciones cuando muestre rutas internas, hosts del backend o parámetros.
- Sin paneles de proveedores (WooCommerce, Mercado Pago, Meta, Vercel, base de datos) ni
  identificadores de cuenta.
- En el panel de administración, sin nombres del equipo de la tienda.
- Formato PNG o WebP, ancho de escritorio de 1440 px y de móvil de 390 px.

## Lista

| # | Archivo | Pantalla | Qué debe mostrar | Vista | Estado |
|---|---|---|---|---|---|
| 1 | `01-inicio.png` | Página de inicio | Carrusel principal, categorías por público y productos destacados | Escritorio | Lista |
| 2 | `02-categoria-movil.png` | Listado de una categoría | Filtros de subcategoría y tarjetas de producto, incluida una talla o producto agotado | Móvil | Lista |
| 3 | `03-ficha-producto.png` | Ficha de producto | Galería, selector de tallas y guía de tallas abierta | Escritorio | Lista |
| 4 | `04-carrito-checkout.png` | Carrito y checkout | Carrito con dos productos y formulario de envío con un error de validación visible, llenado con datos de prueba | Escritorio | Lista: formulario vacío con el resumen del pedido; falta la variante con error de validación |
| 5 | `05-bot-whatsapp.png` | Conversación con el bot | Menú, búsqueda con un error de escritura y ficha con tallas y enlace de compra, desde un número de prueba | Móvil | Pendiente |
| 6 | `06-bandeja.png` | Bandeja de conversaciones | Lista de conversaciones de los tres canales y una conversación abierta con el botón de tomar o devolver al bot, solo con conversaciones de prueba | Escritorio | Pendiente |
| 7 | `07-inventario.png` | Panel de inventario | Tabla por talla con el estado de stock y el indicador del adaptador en simulación | Escritorio | Lista: tomada con el adaptador de WooCommerce en vivo (solo borradores), no en simulación |
| 8 | `08-inventario-masivo.png` | Edición masiva | Vista previa "antes y después" de una operación masiva, antes de aplicarla | Escritorio | Lista: recortada al diálogo de vista previa |