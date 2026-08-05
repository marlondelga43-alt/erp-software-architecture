# 3. Alcance y Contexto del Sistema

## 3.1 Contexto de Negocio
El Sistema ERP interactúa con usuarios internos (gestores de inventario,
responsables de compras, jefes de compras, encargados de almacén) y con
sistemas externos como el sistema contable y los proveedores.

![Diagrama de Contexto](./images/c1_context.png)

## 3.2 Contexto Técnico
La comunicación con el sistema contable externo se realiza mediante
servicios REST/JSON. La comunicación con proveedores se realiza mediante
EDI o correo electrónico según el proveedor.
