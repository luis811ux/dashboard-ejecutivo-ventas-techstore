# 📊 Dashboard Ejecutivo de Ventas – TECHSTORE  
*(Excel 2021 | Power Query | KPIs Financieros)*

---

## 🧾 Descripción del Proyecto

Este proyecto presenta el desarrollo de un **Dashboard Ejecutivo de Ventas** para la empresa ficticia **TECHSTORE**, dedicada a la comercialización de productos electrónicos en **Bogotá, Medellín y Cali**.

El objetivo es **automatizar el registro, transformación y análisis de datos de ventas**, convirtiendo información transaccional en **indicadores financieros y comerciales orientados a la toma de decisiones gerenciales**.

Este proyecto hace parte de mi **portafolio profesional como Analista de Datos Junior**, demostrando competencias en **ETL, análisis financiero, visualización de datos y storytelling ejecutivo** usando **Excel 2021**.

---

## 🎯 Objetivo del Dashboard

- Centralizar la información de ventas mensuales.
- Automatizar el proceso ETL mediante **Power Query**.
- Calcular métricas financieras clave del negocio.
- Analizar desempeño por **región, vendedor y producto**.
- Proveer una vista ejecutiva clara mediante **KPIs, tablas dinámicas y gráficos interactivos**.

---

## 🔍 Alcance del Proyecto

- **Periodo analizado:** Enero 2026  
- **Tipo de análisis:** Financiero y comercial  
- **Nivel:** Ejecutivo / Gerencial  
- **Herramienta:** Excel 2021  
- **Metodología:** ETL con Power Query + Tablas Dinámicas  
- **Nota:** No se utiliza el Modelo de Datos; las consultas se cargan directamente a hojas de Excel.

---










## 🗂️ Estructura del Repositorio

```
/data
│── Ventas
  │── Ventas_Ene_2025_Ana.csv
  │── Ventas_Ene_2025_Carlos.csv
  │── Ventas_Ene_2025_Luis.csv
│── Catalogo
  │── productos
    │── productos.csv
  │── vendedores
    │──  vendedores.csv
  │── costos_fijos
    │── costos_fijos.csv
  │── parametros_financieros
  	│── parametros_financieros.csv
/excel
│── TechStore_Proyecto.xlsx
/images
│── capturas del dashboard
```

---

## 🧪 Proceso ETL (Power Query)

1. Carga de archivos `.csv`.
2. Limpieza y tipificación de datos.
3. Integración de ventas con catálogos de productos y vendedores: tabla **Ventas_Consolidadas**.
4. Carga de consultas directamente a hojas de Excel.

---

## 🧮 Variables y Cálculos Clave

- Venta Bruta  
- Costo de Compra Total  
- Ganancia Bruta  
- Comisión  
- Cumplimiento de Meta  

---

## 📈 KPIs Ejecutivos

- Venta Bruta: **$297.700.000**
- Costo de Compra: **$208.870.000**
- Ganancia Bruta: **$88.830.000**
- Margen Bruto: **30%**
- Costos Fijos: **$28.715.000**
- Ganancia Operativa: **$60.115.000**
- Margen Operativo: **20%**
- Ganancia Neta: **$42.080.500**
- Margen Neto: **14%**



<img width="891" height="115" alt="02-kpis-financieros" src="https://github.com/user-attachments/assets/d683182d-1dfb-44b7-9fb3-7b26cd3289d7" />


---

## 📊 Storytelling con Datos – Análisis Ejecutivo

### 1️⃣ Desempeño General del Negocio

Durante enero de 2026, TECHSTORE alcanzó una **venta bruta total de $297.700.000**, con una **ganancia bruta de $88.830.000**, lo que representa un **margen bruto del 30%**.

Este resultado indica una estructura de precios adecuada y una correcta gestión de costos de compra, permitiendo sostener una operación rentable desde el nivel bruto.

---

### 2️⃣ Análisis por Región

La distribución de ventas por región muestra una fuerte concentración geográfica:

- **Bogotá**
  - Ventas: $142.000.000
  - Participación: **47,70%**
  - Margen Bruto: 29%

- **Medellín**
  - Ventas: $99.000.000
  - Participación: **33,25%**
  - Margen Bruto: **31%** (el más alto)

- **Cali**
  - Ventas: $56.700.000
  - Participación: **19,05%**
  - Margen Bruto: 29%

Aunque Bogotá lidera en volumen, **Medellín presenta el mejor desempeño en rentabilidad**, lo que sugiere oportunidades para replicar estrategias comerciales o de costos en otras regiones.


 <img width="684" height="102" alt="03- metricas_regiones" src="https://github.com/user-attachments/assets/ca4d125f-449a-4365-a81f-7d64ad816c16" />
 <img width="357" height="303" alt="participacion_region" src="https://github.com/user-attachments/assets/d49b1fd5-e601-4c0b-9aa0-821e4f3d6ad5" />


 


---

### 3️⃣ Desempeño de Vendedores

#### 📌 Ranking por Ventas

- **Carlos (Bogotá)**  
  - Ventas: $142.000.000  
  - Número de ventas: 3  

- **Ana (Medellín)**  
  - Ventas: $99.000.000  
  - Número de ventas: 3  

- **Luis (Cali)**  
  - Ventas: $56.700.000  
  - Número de ventas: 3  

Aunque los tres vendedores realizaron el mismo número de transacciones, el **valor promedio por venta varía significativamente**.

---

#### 🎯 Ticket Promedio por Vendedor

- Carlos: **$47.333.333**
- Ana: **$33.000.000**
- Luis: **$18.900.000**

Esto evidencia diferencias en el tipo de producto vendido y en la capacidad de generación de ingresos por operación.

---

#### 🏁 Cumplimiento de Metas = **$110.000.000**

- Carlos: **129%** (supera la meta)
- Ana: **90%** (cercana al objetivo  )
- Luis: **52%** (brecha significativa)

Este análisis permite identificar claramente:
- Alto desempeño (Carlos)
- Potencial de mejora (Ana)
- Necesidad de apoyo o ajuste de estrategia (Luis)

<img width="657" height="308" alt="metas_vendedor" src="https://github.com/user-attachments/assets/c8dc3598-efea-4aea-84db-77764eb90d65" />


---

### 4️⃣ Análisis de Productos

#### 📦 Ventas por Producto

- **Smartphone**
  - Ventas: $142.500.000
  - Participación: **47,87%**
  - Ticket promedio: $47.500.000

- **Laptop**
  - Ventas: $120.000.000
  - Participación: **40,31%**
  - Ticket promedio: $40.000.000

- **Audífonos**
  - Ventas: $35.200.000
  - Participación: **11,82%**
  - Unidades vendidas: 176

Los **Smartphones y Laptops concentran el valor del negocio**, mientras que los **Audífonos aportan volumen**, funcionando como producto de rotación.

<img width="656" height="312" alt="ventas_producto_und" src="https://github.com/user-attachments/assets/36efffe0-df20-4275-9104-32146fd47cb0" />

---

### 5️⃣ Relación Producto – Vendedor

El análisis cruzado muestra especialización por vendedor:

- Carlos concentra ventas en **Smartphones y Laptops**
- Ana presenta una distribución equilibrada
- Luis depende principalmente de **Laptops**

Este enfoque permite diseñar estrategias de capacitación, incentivos y asignación de portafolio por vendedor.

 <img width="657" height="310" alt="ventas_vendedor_producto" src="https://github.com/user-attachments/assets/6cc5b501-9ccb-42b9-8aea-332d1cd5b5e4" />

---

## 🧠 Principales Habilidades Demostradas

- ETL con Power Query  
- Integración de múltiples fuentes de datos  
- Análisis financiero en Excel  
- Diseño de KPIs ejecutivos  
- Tablas dinámicas y gráficos dinámicos  
- Storytelling con datos orientado a negocio  
- Diseño de dashboards ejecutivos  

---

## 🛠️ Herramientas Utilizadas

- Excel 2021  
- Power Query  
- Tablas dinámicas  
- Gráficos dinámicos  
- Segmentadores  
- GitHub  

---

## 👤 Autor

**Luis Fernando Alcalá**  
Analista de Datos Junior  

🔗 LinkedIn: https://www.linkedin.com/in/luis-f-alcala  
🔗 GitHub (Portafolio): https://github.com/luis811ux  
