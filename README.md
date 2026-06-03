# ☕ Dashboard de Ventas y KPIs — Data Studio · Urban Coffee

![Data Studio](https://img.shields.io/badge/Looker%20Studio-Dashboard-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Dataset-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Publicado-4CAF50?style=for-the-badge)

> **Ejercicio Práctico — Visualización de Datos con Data Studio**  
> Caso de negocio: cadena de cafeterías ficticia **Urban Coffee**

---

## 🔗 Acceso al Dashboard

[![Ver Dashboard en Data Studio](https://img.shields.io/badge/📊%20Ver%20Dashboard-Looker%20Studio-4285F4?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://datastudio.google.com/reporting/c8a2617b-ae45-4d8c-9947-a72762f2c850/page/OvizF/edit)

[![Ver Dataset](https://img.shields.io/badge/📋%20Ver%20Dataset-Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)](https://docs.google.com/spreadsheets/d/1CB_OoMdhggqLfEnPgbmBEAg-iVxAsGVvkBnPEf_X47I/edit)

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
Conexión del informe al archivo de **Google Sheets** con los datos de ventas por región y producto (`Dataset_LookerStudio_UrbanCoffee V2`).

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
        ├── Dashboard publicado en Data Studio
        └── Dataset en Google Sheets
```

---

## 📊 Modelo de Datos

Dataset: **`Dataset_LookerStudio_UrbanCoffee V2`**  
Registros: **80 transacciones de ventas** | Periodo: **enero–diciembre 2025**

| Campo | Tipo | Descripción |
|---|---|---|
| `ID_Venta` | Número | Identificador único de la venta |
| `Fecha` | Fecha | Fecha y hora de la transacción |
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

**Ejercicio relacionado:** [Dashboard Ejecutivo en Power BI — Urban Coffee](https://github.com/migueljerico/powerbi-dashboard-urban-coffee) — misma cadena de datos, diferente herramienta de BI.

---

<p align="center">
  <sub>Desarrollado por <a href="https://github.com/migueljerico">@migueljerico</a> · 2025</sub>
</p>
