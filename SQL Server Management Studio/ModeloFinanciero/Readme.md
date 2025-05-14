# 💼 Modelo Financiero 

Este proyecto representa un modelo de base de datos optimizado para el análisis financiero, implementado bajo la arquitectura de **esquema estrella**, ideal para soluciones de Business Intelligence (BI), Power BI, Azure Synapse o Microsoft Fabric.

> Autor: **Ricardo Ugarte**

---

## 🧩 Estructura del modelo

- 📊 **Tabla de hechos:**
  - `FactTransacciones`: movimientos contables o financieros.
  - `FactAmortizaciones`: evolución del capital e intereses.
  - `FactGarantias`: garantías asociadas a productos financieros.

- 📐 **Tablas de dimensiones:**
  - `DimFecha`: calendario analítico.
  - `DimCliente`: segmentación y localización de clientes.
  - `DimProducto`: productos financieros (préstamos, cuentas, etc.).
  - `DimCompañia`: entidades responsables.
  - `DimMoneda`: gestión multimoneda con tipo de cambio.
  - `DimCuentaContable`: plan de cuentas por categorías.
  - `DimCentroCosto`: control por áreas o centros operativos.

---
| Recurso              | Descripción                                                                                       | Enlace                                                                                         |
|----------------------|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
|  Diagrama del modelo | Puedes visualizar el diagrama del modelo financiero o importar el archivo `.dbml` en dbdiagram.io | [Ver diagrama🌐](https://dbdiagram.io/d/6824d0b35b2fc4582f9f00bc)                           |
| Script SQL         | Script completo en SQL Server con claves primarias, foráneas y estructura optimizada para BI     | [Modelo.SQL 📄](./modelo_financiero.sql)                                                       |

---

Este modelo está orientado a:

- Análisis financiero por producto, cliente, compañía o centro de costo
- Cálculo de KPIs: rentabilidad, riesgo, mora, exposición, etc.
- Cruce entre capital, intereses, garantías y moneda
- Soporte a reportes de Power BI o sistemas analíticos como Fabric



