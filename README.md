# 🍎 Apple Inc. Financial Analysis (1980–2026)

> **Exploratory Data Analysis** sobre 45+ años de datos financieros de Apple Inc.  
> Stack: Python · pandas · matplotlib · SQL · Excel

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![pandas](https://img.shields.io/badge/pandas-2.0-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-En%20desarrollo-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Objetivo del Proyecto

Analizar el rendimiento financiero histórico de Apple Inc. para identificar:

- 📈 Tendencias de revenue por línea de producto (iPhone, Mac, Services, iPad, Wearables)
- 💹 Correlación entre precio de acción y métricas financieras trimestrales
- 📅 Estacionalidad: ¿qué trimestre fiscal genera más revenue históricamente?
- 🌍 Evolución del mix de productos en los últimos 10 años

---

## 🗂️ Estructura del Repositorio

```
📦 apple-financial-analysis/
 ┣ 📁 data/
 ┃ ┣ 📁 raw/              ← Dataset original sin modificar (Kaggle)
 ┃ ┗ 📁 processed/        ← Datos limpios listos para análisis
 ┣ 📁 notebooks/
 ┃ ┗ 📓 EDA_Apple.ipynb   ← Análisis exploratorio completo
 ┣ 📁 excel/
 ┃ ┗ 📊 Dashboard_Apple.xlsx ← Dashboard interactivo
 ┣ 📁 sql/
 ┃ ┗ 📄 queries.sql        ← Queries de extracción y análisis
 ┣ 📁 outputs/
 ┃ ┗ 📁 charts/            ← Visualizaciones exportadas
 ┗ 📄 README.md
```

---

## 📊 Dataset

| Atributo | Detalle |
|---|---|
| **Fuente** | [Kaggle — Apple Financial Dataset](https://www.kaggle.com) |
| **Período** | 1980 – 2026 |
| **Frecuencia** | Diaria (precios) + Trimestral (financiero) |
| **Columnas** | 85 variables (precios, indicadores técnicos, revenue por segmento) |
| **Filas** | 11,000+ registros diarios |

**Columnas clave utilizadas:**
```
date, close, volume,
revenue_iphone, revenue_mac, revenue_services,
revenue_wearables_other, revenue_ipad, revenue_total,
fiscal_year, fiscal_quarter, rsi_14
```

---

## 🔍 Preguntas de Negocio

```
1. ¿Qué línea de producto lidera el revenue de Apple en los últimos 10 años?
2. ¿Existe correlación entre el precio de cierre y el revenue trimestral?
3. ¿Qué trimestre fiscal genera históricamente más revenue?
```

---

## 📈 Key Insights

> ⚠️ *Sección en desarrollo — se actualizará al completar el análisis*

- 📱 **iPhone dominance:** el iPhone representa históricamente el ~50%+ del revenue total
- 📦 **Services crecimiento:** el segmento de servicios ha crecido consistentemente desde 2015
- 📅 **Q1 fiscal (oct-dic):** históricamente el trimestre más fuerte por temporada navideña

---

## 🛠️ Stack Técnico

| Herramienta | Uso en el proyecto |
|---|---|
| **Python / pandas** | Carga, limpieza, transformación y análisis de datos |
| **matplotlib** | Visualizaciones de tendencias y correlaciones |
| **SQL** | Queries de extracción y análisis agregado |
| **Excel** | Dashboard interactivo con Tablas Dinámicas y XLOOKUP |
| **Git / GitHub** | Control de versiones y documentación |

---

## 🚀 Cómo Ejecutar

```bash
# 1. Clonar el repositorio
git clone https://github.com/Ivan-Developer-ict/apple-financial-analysis.git
cd apple-financial-analysis

# 2. Instalar dependencias
pip install pandas matplotlib jupyter


> **Nota:** Coloca el dataset en `data/raw/` antes de ejecutar el notebook.

---

## 📬 Contacto

**LinkedIn:** [Ivan Peña](https://www.linkedin.com/in/iv%C3%A1n-pe%C3%B1a)  
**GitHub:** [@Ivan-Developer-ict](https://github.com/Ivan-Developer-ict)  
**Email:** investmentsandbusinessivan@gmail.com

---

⭐ **Si este proyecto te resulta útil, dale una estrella en GitHub**
