# 🐧 Modelo Predictivo de Masa Corporal en Pingüinos
**EDA + Regresión Lineal | Proyecto de Análisis Predictivo**

![Status](https://img.shields.io/badge/EDA-Complete-brightgreen)
![Model](https://img.shields.io/badge/Model-LinearRegression-blue)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Last Update](https://img.shields.io/badge/Last_Update-2025-lightgrey)

---

## 🧠 Sobre el Proyecto

Este proyecto analiza si las características morfométricas de pingüinos permiten **estimar la masa corporal** mediante un modelo simple, interpretable y reproducible.

El análisis sigue un enfoque profesional orientado a decisiones, permitiendo identificar rápidamente **el predictor más importante** dentro del dataset.

Incluye:

- Exploración del dataset *Palmer Penguins*  
- Análisis de correlaciones y patrones  
- Modelo de regresión lineal OLS  
- Validación de supuestos estadísticos  
- Documentación ejecutiva (PACE + One Pager)  

El modelo explica **76.9% de la variabilidad** de la masa corporal usando una sola variable.

---

## 🔑 Insight Clave

> **La longitud del pico es el predictor más fuerte de masa corporal, con una relación lineal positiva y altamente consistente.**

---

## 📊 Principales Resultados

- Cada **1 mm adicional** en longitud del pico incrementa en promedio **≈141 g** la masa corporal.
- R² = **0.769**, confirmando buen ajuste y poder explicativo.
- Los supuestos del modelo (linealidad, normalidad, independencia, homocedasticidad) se cumplen satisfactoriamente.
- La longitud de la aleta también muestra correlación útil para futuros modelos multivariables.

---

## 🗂️ Estructura del Repositorio

```
Modelo Predictivo de Masa Corporal/
│
├── data/
│   └── penguins.csv
│
├── notebooks/
│   └── Modelo Predictivo de Masa Corporal.ipynb
│
├── reports/
│   ├── Modelo Predictivo de Masa Corporal.pdf
│   ├── PACE - Modelo Predictivo de Masa Corporal.docx
│   ├── PACE - Modelo Predictivo de Masa Corporal.pdf
│   ├── Resume Ejecutivo.pdf
│   └── Resume Ejecutivo.pptx
│
├── images/
│   ├── dispersion_por_pares.png
│   ├── grafico_q-q.png
│   ├── histograma_de_residuos.png
│   ├── linea_de_regresion.png
│   └── valores_ajustados_vs_residuos.png
│
├── requirements.txt
│
└── EXECUTIVE_SUMMARY.md
```

---

## 📄 Documentos del Proyecto

| Tipo | Archivo |
|------|---------|
| 📘 Notebook interactivo | [Modelo Predictivo de Masa Corporal.ipynb](notebooks/Modelo%20Predictivo%20de%20Masa%20Corporal.ipynb) |
| 📄 PACE (Metodología) | [PACE - Modelo Predictivo de Masa Corporal.pdf](reports/PACE%20-%20Modelo%20Predictivo%20de%20Masa%20Corporal.pdf) |
| 📊 Resumen Ejecutivo | [Resume Ejecutivo.pdf](reports/Resume%20Ejecutivo.pdf) |
| 🗂 Dataset | [penguins.csv](data/penguins.csv) |

---

## 🔧 Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/fcamasca/modelo-predictivo-masa-corporal.git
   ```
2. **Crear entorno virtual (opcional)**
   ```bash
   python -m venv venv
   source venv/bin/activate     # Linux/Mac
   venv\Scripts\activate       # Windows
   ```
3. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```
4. **Abrir el notebook**
   ```bash
   jupyter notebook notebooks/Modelo Predictivo de Masa Corporal.ipynb
   ```

---

## 🧪 Tecnologías y Librerías

- Python 3  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Statsmodels  
- Jupyter Notebook  

Requisitos completos en  
📦 **requirements.txt**

---

## 📈 Visualizaciones

### 🔹 Pairplot — Relaciones morfométricas  
<img src="images/dispersion_por_pares.png" width="450px">

---

### 🔹 Regresión Lineal — Longitud del Pico vs Masa Corporal  
<img src="images/linea_de_regresion.png" width="450px">

---

## 🚀 Próximos Pasos

- Construir modelo multivariable.  
- Evaluar diferencias predictivas por especie.  
- Probar modelos no lineales para comparación.  
- Crear dashboard interactivo.  

---

## 📬 Autor

**Frankz Camasca**  
Analista de Datos | Data Analytics & Predictive Modeling  

[![GitHub](https://img.shields.io/badge/GitHub-%40fcamasca-black?logo=github)](https://github.com/fcamasca)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Frankz%20Camasca-blue?logo=linkedin)](https://www.linkedin.com/in/frankz-william-camasca-castillo-b63a0094)

---

## 📄 Licencia
Proyecto de uso educativo y demostración profesional.
