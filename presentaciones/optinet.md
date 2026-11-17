<div align="center">

# OptiNet · Sistema de gestión para ópticas

**NetSol | SaaS especializado | En desarrollo**

[![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-245b63)](https://react.dev/)
[![Backend](https://img.shields.io/badge/Backend-Express-516f88)](https://expressjs.com/)
[![Datos](https://img.shields.io/badge/BD-MySQL%2FMariaDB-447fa0)](https://www.mysql.com/)

</div>

## El problema

Una óptica necesita conectar información de clientes y recetas con presupuestos, órdenes de trabajo, ventas, pagos y stock. Es un flujo diferente al de un comercio genérico.

## El proyecto

**OptiNet Manager** es un sistema SaaS desarrollado desde NetSol para la gestión de ópticas argentinas. Su documentación privada describe una arquitectura modular, aislamiento por empresa y procesos específicos del sector.

## Flujos documentados

- Clientes e información óptica relacionada con la atención.
- Recetas, presupuestos y órdenes de trabajo con varios productos o tratamientos.
- Catálogo, ventas, pagos parciales o combinados y cuentas corrientes.
- Movimientos de stock, caja y devoluciones.
- Trabajo de integración fiscal mediante un adaptador de ARCA, sujeto a configuración y validaciones específicas.

## Arquitectura

| Capa | Tecnologías |
| --- | --- |
| Frontend | React y TypeScript |
| Backend | Express y Node.js |
| Base de datos | MySQL / MariaDB |
| Validación compartida | Contratos con Zod |
| Procesos | Worker de correo y comprobantes con cola MySQL |

Se trabaja con controles de empresa y validaciones de operación; no se exponen conexiones, certificados ni datos ópticos reales.

## Estado del proyecto

**En desarrollo / evolución del MVP.** Su propia documentación distingue funcionalidades actuales de etapas posteriores. Suscripciones pagas, integración con Tiendanube, sucursales avanzadas y otros módulos **no se presentan como disponibles**.

La emisión fiscal y los flujos de operación requieren verificaciones controladas antes de ofrecerlos como funcionalidad plenamente productiva.

## Mi participación

Desarrollo de un producto de gestión específico para ópticas, con trabajo en frontend, backend, datos y evolución funcional desde NetSol.

## Presentación visual

La documentación y el código original permanecen privados. Las capturas públicas se añadirán únicamente si corresponden a pantallas verificadas y datos ficticios.

---

**[Volver a los cinco proyectos](./README.md)** · **[NetSol](https://netsol.ar/)** · **[Portfolio](https://emanuel-paz-portfolio.vercel.app/)**
