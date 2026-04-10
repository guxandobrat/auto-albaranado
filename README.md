# Auto Albaranado

Sistema web de gestion de albaranes de entrega para proveedores.

## Descripcion

Aplicacion que permite a los proveedores gestionar las entregas parciales o totales de los pedidos asignados, generando albaranes de entrega de forma sencilla.

## Flujo de la aplicacion

1. **Login** - Acceso por proveedor con contrasena
2. **Mis Pedidos** - Galeria con los pedidos asignados (con busqueda inteligente y filtros por estado)
3. **Detalle del Pedido** - Vista con articulos, precios, cantidades y totales con/sin IVA
4. **Anadir Albaran** - Pop-up para subir archivo del albaran (drag & drop)

## Funcionalidades

- **Busqueda inteligente** por articulo, pedido o codigo de articulo (con categorias por colores)
- **Filtrado** por estado: pendiente, parcial, cerrado
- **Pedidos cerrados** en gris diferenciados visualmente
- **Nombre del comprador** visible en galeria y detalle
- **Precios por linea** y totales con/sin IVA por pedido
- **Cantidades fijas** (no modificables) por linea
- **Reporte de incidencias** por linea (icono de aviso amarillo) con envio por email al comprador o al proveedor
- **Upload de albaran** via pop-up con drag & drop

## Conceptos clave

| Concepto | Descripcion |
|----------|-------------|
| **Pedido** | Orden de compra asignada a un proveedor |
| **Albaran** | Registro de entrega. Puede haber mas de 1 por pedido (entregas parciales) |

## Estado actual

- [x] Mockup HTML interactivo con 4 pantallas
- [x] Busqueda inteligente con categorias
- [x] Filtros de estado en galeria
- [x] Sistema de incidencias por linea
- [x] Upload de albaran con drag & drop
- [ ] Backend / API
- [ ] Base de datos
- [ ] Autenticacion
- [ ] Envio real de emails

## Como ejecutar

Abrir `mockup.html` en cualquier navegador.
