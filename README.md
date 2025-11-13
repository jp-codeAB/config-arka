# Documentación Técnica del Backend Arka

## Resumen Ejecutivo

El proyecto **Arka** es la implementación del backend de un sistema de comercio electrónico, diseñado bajo **arquitectura de microservicios** para garantizar **escalabilidad**, **mantenibilidad** y **resiliencia**. Su principal **propósito** es optimizar la gestión integral de inventario, el procesamiento de órdenes de compra y la analítica de ventas.

El **alcance** abarca el desarrollo de un conjunto de servicios desacoplados (Inventario, Pedidos, Carrito, Autenticación, Notificaciones y un API Gateway) utilizando **Java 21** con **Spring Boot 3.5.7**. Se emplea una estructura de código basada en el patrón **Arquitectura Hexagonal (Ports & Adapters)** y los principios **SOLID**, promoviendo un desacoplamiento total entre las capas de dominio, aplicación e infraestructura.

---
## Guía de Navegación

Esta documentación está organizada en secciones numeradas para facilitar la trazabilidad.

| Archivo | Contenido Principal |
| :--- | :--- |
| [Historias de Usuario](HistoriasUsuario.md) | Requisitos detallados y priorización del desarrollo. |
| [Modelo Entidad-Relacion](Entidad-Relación.md) | Esquema relacional del sistema. |
| [Diagrama de Casos de Uso](Casos-uso.md) | Diagrama de casos de Uso. |
| [Arquitectura del Software](ArquitecturaDelSoftware.md) | Definición de microservicios, patrones y diagramas. |
