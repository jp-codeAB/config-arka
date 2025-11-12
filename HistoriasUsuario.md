# Historias de Usuario

El backlog del proyecto se ha organizado en módulos funcionales, con cada Historia de Usuario (HU) detallando la necesidad desde la perspectiva del usuario (Administrador o Cliente) y definiendo criterios de aceptación.

## 1. Historias de Usuario por Módulo

### Módulo 1: Gestión de Inventario y Abastecimiento

| HU | Descripción | Criterios de Aceptación Clave |
| :--- | :--- | :--- |
| **HU1** | Registrar productos en el sistema (ADMIN) | Carga de nombre, descripción, precio, stock y categoría. Validaciones de datos requeridos|
| **HU2** | Actualizar stock de productos (ADMIN) | Permitir modificar el stock. Prohibir valores negativos. Historial de cambios en el stock|
| **HU3** | Generar reportes de productos por abastecer (ADMIN) | Reporte semanal automático. Incluir productos con stock menor a un umbral configurable. Exportación a CSV/PDF |

### Módulo 2: Gestión de Órdenes de Compra

| HU | Descripción | Criterios de Aceptación Clave |
| :--- | :--- | :--- |
| **HU4** | Registrar una orden de compra(CLIENT) | Registro de múltiples productos. Validación de disponibilidad de stock. Mensaje de confirmación |
| **HU5** | Modificar una orden de compra (CLIENT)  | Solo se permiten modificaciones en estado pendiente esto cuando aun se esta en el carrito. Actualización del stock en caso de eliminación de productos.  |
| **HU6** | Notificación de cambio de estado de pedido (CLIENT)  | Notificación por correo o en la plataforma. **Estados:** pendiente, confirmado, en despacho, entregado |

### Módulo 3: Reportes y Análisis de Ventas

| HU | Descripción | Criterios de Aceptación Clave |
| :--- | :--- | :--- |
| **HU7** | Generar reportes de ventas (ADMIN) | Incluir total de ventas, productos, y clientes . Exportación a CSV/PDF |
| **HU8** | Identificar carritos abandonados(ADMIN) | Listado con fecha y productos. |



| [Modelo Entidad-Relacion](Entidad-Relación.md) | Esquema relacional del sistema. |
