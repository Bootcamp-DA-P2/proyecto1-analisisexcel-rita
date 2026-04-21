# 📊 Dashboard de Análisis de Préstamos (Excel)

![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Power Query](https://img.shields.io/badge/ETL-PowerQuery-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🧩 Descripción

Proyecto de análisis de datos enfocado en préstamos, desarrollado en Excel.
Incluye procesos de **extracción, limpieza, transformación y visualización**, culminando en un **dashboard interactivo**.

---

## 🔌 Extracción de datos

* Importación de datos desde archivo **CSV** mediante **Power Query**
* Conexión dinámica para actualización automática

---

## 🧹 Limpieza y transformación

* Eliminación y tratamiento de valores nulos
* Estandarización de columnas
* Conversión de formatos:

  * 💰 Números → formato moneda
  * 📅 Fechas → formato fecha y hora

---

## ⚙️ Enriquecimiento de datos

Se añadieron nuevas variables:

* 🌍 **Continente**
* 💳 **Nivel del crédito**
* 👤 **Ícono de género**

---

## 🎨 Formato condicional

* Aplicado a la columna **repayment_interval**
* Mejora la lectura visual de los intervalos de pago

---

## 📊 Tablas dinámicas

Se construyeron **6 tablas dinámicas**:

### 🔹 KPIs

* Total del préstamo
* Total financiado
* Total pagado

### 🔹 Análisis

* Préstamos por país
* Préstamos por continente
* Préstamos por género

---

## 📈 Dashboard

El dashboard incluye:

### 📌 Gráficos

* Total de préstamos
* Total financiado
* Total pagado
* Préstamos por continente

### 📌 KPIs visuales

* 💰 Total préstamo
* 💵 Total financiado
* ✅ Total pagado

---

## 🎛️ Interactividad

Segmentadores de datos (slicers):

* País
* Sector
* Continente
* Intervalo de reembolso
* Género

✔️ Todos los elementos están conectados entre sí para análisis dinámico.

---

## 🎬 Extra

* Inclusión de **GIF interactivo** para mejorar la presentación del dashboard

---

## 🖼️ Vista previa

*Aquí puedes agregar capturas de tu dashboard:*

```
![Dashboard](./images/dashboard.png)
![Filtros](./images/slicers.png)
```

---

## 🚀 Insights obtenidos

* Identificación de regiones con mayor volumen de préstamos
* Comparación de financiamiento por género
* Evaluación del comportamiento de pago
* Análisis por continente y sector

---

## 🛠️ Herramientas utilizadas

* Microsoft Excel
* Power Query
* Tablas dinámicas
* Segmentación de datos
* Formato condicional

---

## 📁 Estructura del repositorio

```
📦 loan-analysis-dashboard
 ┣ 📂 data
 ┃ ┗ prestamos.csv
 ┣ 📂 images
 ┃ ┗ dashboard.png
 ┣ 📄 dashboard.xlsx
 ┗ 📄 README.md
```

