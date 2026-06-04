# ☕ Dashboard de Ventas y KPIs — Data Studio · Urban Coffee

![Google Data Studio](https://img.shields.io/badge/Google%20Data%20Studio-Dashboard-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Dataset-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Publicado-4CAF50?style=for-the-badge)
![Tipo](https://img.shields.io/badge/Práctica-Visualización%20de%20Datos-FF6B6B?style=for-the-badge)

> **Ejercicio Práctico — Visualización de Datos con Google Data Studio**  
> Caso de negocio: cadena de cafeterías ficticia **Urban Coffee**

---

## 🔗 Acceso al Dashboard

[![Ver Dashboard en Data Studio](https://img.shields.io/badge/📊%20Ver%20Dashboard-Google%20Data%20Studio-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://datastudio.google.com/reporting/c8a2617b-ae45-4d8c-9947-a72762f2c850/page/OvizF/edit)

[![Ver Dataset en Google Sheets](https://img.shields.io/badge/📋%20Ver%20Dataset-Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)](https://docs.google.com/spreadsheets/d/1CB_OoMdhggqLfEnPgbmBEAg-iVxAsGVvkBnPEf_X47I/edit)

[![Descargar Dataset CSV](https://img.shields.io/badge/⬇️%20Descargar%20Dataset-CSV%20v1.0-FFA500?style=for-the-badge&logo=github&logoColor=white)](https://github.com/migueljerico/data-studio-dashboard-urban-coffee/releases/tag/v1.0)

> El dashboard se actualiza automáticamente al modificar el Google Sheets de origen.

---

## 📋 Descripción del Proyecto

Dashboard interactivo desarrollado en **Google Data Studio** para analizar el rendimiento comercial de una cadena de cafeterías con locales en Madrid, Barcelona, Valencia y Sevilla.

El objetivo es facilitar la **toma de decisiones basada en datos** mediante KPIs visuales, gráficos de tendencia y filtros dinámicos que permiten explorar ventas por producto, región, tipo de tienda y periodo temporal.

---

## 🛠️ Caso Práctico — Pasos del Ejercicio

### Paso 1 · Crear el informe
Acceso a [datastudio.google.com](https://datastudio.google.com) y creación de un informe nuevo desde cero.

### Paso 2 · Conectar la fuente de datos
Conexión del informe al archivo de **Google Sheets** con los datos de ventas por región y producto (`Dataset_UrbanCoffee_2025`).

### Paso 3 · Insertar visualizaciones y KPIs
Incorporación de:
- **Gráficos de barras** — ventas por categoría, producto y región
- **Tablas dinámicas** — resumen de ingresos, costes y beneficio
- **KPI Cards** — métricas clave: ingresos totales, conversión y tendencia

### Paso 4 · Añadir filtros interactivos
Configuración de controles de filtro por:
- 📅 **Fecha** — selector de rango temporal
- 🗺️ **Región** — ciudad (Madrid, Barcelona, Valencia, Sevilla)
- 🏷️ **Categoría** — Café, Té, Snacks, Repostería

---

## 🗂️ Estructura del Repositorio

```
data-studio-dashboard-urban-coffee/
│
├── 📖 README.md
│       └── Documentación completa del proyecto
│
└── 🔗 Links externos
        ├── Dashboard publicado en Google Data Studio
        └── Dataset en Google Sheets
```

---

## 📊 Modelo de Datos

Dataset: **`Dataset_UrbanCoffee_2025`**  
Registros: **80 transacciones de ventas** | Periodo: **enero–diciembre 2025**

| Campo | Tipo | Descripción |
|---|---|---|
| `ID_Venta` | Número | Identificador único de la venta |
| `Fecha` | Fecha | Fecha de la transacción |
| `Producto` | Texto | Nombre del producto vendido |
| `Categoria` | Texto | Agrupación del producto |
| `Region_Ciudad` | Texto | Ciudad donde se realizó la venta |
| `Tipo_Tienda` | Texto | Formato del establecimiento |
| `Visitas` | Número | Número de visitas en la sesión |
| `Cantidad_Vendida` | Número | Unidades vendidas |
| `Ingresos` | Decimal | Ingresos generados (€) |
| `Costes` | Decimal | Costes asociados (€) |
| `Beneficio` | Decimal | Beneficio neto (€) |

### 🏪 Dimensiones del negocio

| Dimensión | Valores |
|---|---|
| **Ciudades** | Madrid · Barcelona · Valencia · Sevilla |
| **Tipo de tienda** | Centro · Centro Comercial · Calle · Oficina |
| **Categorías** | Café · Té · Snacks · Repostería |
| **Productos** | Latte · Espresso · Mocha · Cappuccino · Té Verde · Té Negro · Cookie · Sandwich · Muffin · Croissant |

---

## 📈 KPIs del Dashboard

- 💰 **Ingresos Totales** — suma acumulada de ventas en el periodo
- 📦 **Unidades Vendidas** — total de productos despachados
- 💹 **Beneficio Neto** — diferencia entre ingresos y costes
- 👣 **Visitas** — tráfico total en los establecimientos
- 📊 **Tendencia temporal** — evolución mensual de ventas

---

## 🧰 Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| **Google Data Studio** | Creación del dashboard interactivo |
| **Google Sheets** | Fuente de datos conectada en tiempo real |

---

## 📚 Contexto formativo

Este ejercicio forma parte del programa de formación en **Análisis de Datos**, dentro del módulo de visualización. El objetivo es desarrollar competencias en la creación de dashboards conectados a datos en vivo, aplicando buenas prácticas de visualización y storytelling con datos.

**Ejercicio relacionado:** [Dashboard Ejecutivo en Power BI — Urban Coffee](https://github.com/migueljerico/powerbi-dashboard-urban-coffee) — misma cadena de datos, herramienta Microsoft BI.

---

<p align="center">
  <sub>Desarrollado por <a href="https://github.com/migueljerico">@migueljerico</a> · 2026</sub>
</p>
