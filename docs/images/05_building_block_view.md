# 5. Vista de Bloques de Construcción

## 5.1 Sistema General — Nivel 1

![Diagrama de Contenedores](./images/c2_containers.png)

## 5.2 Responsabilidad de cada Contenedor

| Contenedor | Responsabilidad |
|---|---|
| SPA (React) | Interfaz de usuario. Renderiza formularios y listas; consume la API vía HTTPS/JSON. |
| API (Spring Boot) | Contiene la lógica de negocio: validación de productos, gestión de proveedores, flujo de aprobación de órdenes, actualización de stock. |
| Base de Datos (PostgreSQL) | Persiste productos, proveedores, órdenes de compra y su detalle. |
