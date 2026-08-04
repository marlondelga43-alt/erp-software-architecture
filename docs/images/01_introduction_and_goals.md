# 1. Introducción y Objetivos

## 1.1 Propósito del Sistema
El Sistema ERP tiene como objetivo centralizar y automatizar los procesos
clave de negocio de la empresa: compras, facturación, stock/costos,
activos fijos, empleados y business intelligence (EIS), reemplazando
procesos manuales y hojas de cálculo dispersas.

## 1.2 Requisitos de Negocio — Módulo de Compras
- RN-01: El sistema debe permitir registrar y mantener un catálogo de productos.
- RN-02: El sistema debe permitir gestionar un directorio de proveedores.
- RN-03: El sistema debe permitir generar órdenes de compra asociadas a un proveedor.
- RN-04: Las órdenes de compra deben pasar por un flujo de aprobación antes de ser enviadas.
- RN-05: El sistema debe registrar la recepción de mercancía y actualizar el stock automáticamente.
- RN-06: El sistema debe permitir consultar el historial de compras con filtros.

## 1.3 Objetivos de Calidad
| Prioridad | Objetivo de calidad | Escenario |
|---|---|---|
| 1 | Usabilidad | El registro de un producto debe tomar menos de 1 minuto. |
| 2 | Consistencia de datos | El stock debe actualizarse de forma atómica al registrar una recepción. |
| 3 | Trazabilidad | Toda orden de compra debe conservar su historial de estados. |

## 1.4 Interesados (Stakeholders)
| Rol | Interés |
|---|---|
| Gestor de Inventario | Mantener catálogo de productos actualizado |
| Responsable de Compras | Gestionar proveedores y generar órdenes |
| Jefe de Compras | Controlar y aprobar el gasto |
| Encargado de Almacén | Registrar recepciones y controlar stock |
