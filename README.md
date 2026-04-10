# Auto Albaranado

Sistema web de gestion de albaranes de entrega para proveedores.

## Descripcion

Aplicacion que permite a los proveedores gestionar las entregas parciales o totales de los pedidos asignados, generando albaranes de entrega de forma sencilla.

## Flujo de la aplicacion

1. **Login** - Acceso por proveedor con contrasena
2. **Mis Pedidos** - Galeria con los pedidos asignados al proveedor (estado: pendiente, parcial, completado)
3. **Detalle del Pedido** - Vista del pedido con listado de articulos. Boton "+ Adicionar Albaran" para iniciar una entrega
4. **Albaran Generado** - Documento del albaran con los articulos entregados y opcion de descarga PDF

## Conceptos clave

| Concepto | Descripcion |
|----------|-------------|
| **Pedido** | Orden de compra asignada a un proveedor |
| **Albaran** | Registro de cuales articulos fueron entregados y en que cantidad. Puede haber mas de 1 albaran por pedido (entregas parciales) |
| **Factura** | Importe final acordado del pedido. Solo se genera una vez |

## Estado actual

- [x] Mockup HTML interactivo con las 4 pantallas
- [ ] Backend / API
- [ ] Base de datos
- [ ] Autenticacion
- [ ] Generacion de PDF

## Tecnologias

Por definir. Actualmente solo existe el mockup en HTML/CSS/JS puro.

## Como ejecutar

Abrir `mockup.html` en cualquier navegador.
