# 6. Vista de Ejecución (Runtime)

## 6.1 Escenario: Registrar un Producto

Este escenario corresponde a la historia de usuario:
*"Como gestor de inventario, quiero registrar nuevos productos con su
información básica, para que pueda mantener un catálogo actualizado."*

![Diagrama de Secuencia](./images/sequence_registrar_producto.png)

## 6.2 Explicación del Flujo
1. El gestor de inventario completa el formulario de nuevo producto en la SPA.
2. La SPA envía una petición `POST /api/productos` a la API con los datos ingresados.
3. La API valida los datos recibidos.
4. Si los datos son válidos, la API inserta el registro en la base de datos y retorna `201 Created` con el producto creado.
5. Si los datos son inválidos, la API retorna `400 Bad Request` con el detalle del error.
6. La SPA actualiza la interfaz mostrando el mensaje correspondiente al usuario.
