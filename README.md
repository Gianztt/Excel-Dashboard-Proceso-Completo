# 📊 Dashboard Comercial en Excel con dataset Superstore

<img width="1864" height="724" alt="image" src="https://github.com/user-attachments/assets/f13d9912-a7e3-4279-9ed4-b662c8adb189" />

Este proyecto simula un entorno de análisis empresarial utilizando Excel como herramienta de Business Intelligence (BI). El objetivo fue generar un dashboard dinámico para visualizar y analizar indicadores clave de rendimiento (KPIs) relacionados con ventas, márgenes y comportamiento de clientes.

---

## 🗂️ Datos utilizados

Se utilizó el archivo `superstore.csv`, un dataset ficticio de acceso público. Representa ventas de una tienda minorista durante varios meses, incluyendo variables como:

- Fecha de pedido y envío
- Segmento del cliente
- Región y ciudad
- Categoría y subcategoría de productos
- Ventas, ganancia y descuentos

Fuente: https://github.com/nileshely/SuperStore-Dataset-2019-2022/blob/main/Analyzing%20SuperStore's%20Product%20Sales%20and%20Profits.ipynb

---

## ⚙️ Paso a paso del proyecto

### 1. Limpieza y transformación de datos con Power Query

- Se cambió el tipo de datos de las columnas de fechas (`Order Date`) de texto a tipo `Date`.
- Se agregaron tres columnas nuevas para realizar el análisis:
  - `Month`
  - `Year`
  - `Month_Year` 

---

### 2. Cálculo de KPIs con fórmulas de Excel

Se crearon los siguientes KPIs usando fórmulas simples en celdas externas:

- Total de ventas
- Margen promedio
- Cantidad de productos vendidos
- Porcentaje de descuento promedio
- Ganancia por pedido

---

### 3. Visualización de datos con tablas dinámicas

Se insertaron tablas dinámicas en las siguientes hojas:

- `KPI - Sales`
- `KPI - Profit Margin`
- `KPI - Quantity`
- `KPI - Discount`
- `KPI - ProfitPerOrder`
- `KPI - Subcategory`

---

### 4. Construcción del Dashboard

- Se añadieron **4 segmentadores (slicers)** para exploración dinámica:
  - Mes (`Month`)
  - Segmento de cliente (`segment`)
  - Región (`region`)
  - Subcategoría (`subcategory`)

- Se agregaron **gráficos de barra** vinculados a cada tabla dinámica.
- Se aplicó un formato visual diferenciado por tipo de KPI.
<img width="1574" height="615" alt="image" src="https://github.com/user-attachments/assets/be903cfa-fb1a-48b9-9469-58e47d89d279" />
---

## 5. Insights obtenidos

🟢 Margen por producto

> El margen promedio por producto es  
> de un 12%, con ganancias  
> concentradas en fotocopiadoras y celulares.

---

🔴 Descuento y rentabilidad por región

> Central es la región con mayor % de  
> descuento (24%) lo que se asocia con  
> tener los peores márgenes por producto %  
> y la peor ganancia promedio por orden $.

---

🟡 Rotación por subcategoría

> Las fotocopiadoras tienen una  
> pequeña cantidad de ventas (234), lo que  
> indica margen alto y poca rotación.

---

## 📁 Archivos incluidos

- `DashboardSuperstore.xlsx`: archivo principal con dashboard y modelo.
- `README.md`: descripción del proyecto.

---

## 🛠️ Herramientas utilizadas

- Power Query: Para limpieza y transformación del dataset original.
- Fórmulas Excel: Para el cálculo de KPIs personalizados.
- Tablas dinámicas: Para visualización segmentada de los KPIs.
- Gráficos: Para representar cada indicador visualmente.
- Segmentadores (Slicers): Para explorar los datos por mes, segmento, región y subcategoría.

		
		
