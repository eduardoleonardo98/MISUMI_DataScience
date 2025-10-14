# 🔍 Data Science Project — Locating Pins (MISUMI México)

## 📘 Descripción general

Este proyecto desarrolla un **análisis de datos integral** aplicado a la categoría **Locating Pins** del catálogo de **MISUMI México**.  
El objetivo principal es comprender el **comportamiento del cliente a lo largo del proceso de conversión (*path to purchase*)**, desde la generación de números de parte hasta la venta final, para optimizar la oferta de productos y mejorar la eficiencia comercial.

---

## 🧩 Objetivos principales

- Analizar las **etapas del funnel comercial**: generación de números de parte, descargas de modelos CAD, cotizaciones y órdenes de venta.  
- Identificar **patrones de comportamiento del cliente** y **productos de alta demanda**.  
- Medir la **eficiencia del funnel** y la conversión entre etapas.  
- Evaluar el **desempeño del portafolio DLM** dentro del mercado mexicano.  
- Transformar datos dispersos en **insights accionables** para soporte técnico y estrategia comercial.

---

## 📊 Estructura del análisis

El flujo de trabajo del notebook `Git_LocatingPins_EALI.ipynb` se organiza en las siguientes etapas:

1. **Bancos de datos y preprocesamiento**  
   Integración de cuatro fuentes CSV que representan las distintas etapas del *path to purchase*.

2. **Web Scraping y enriquecimiento de datos**  
   Recuperación automatizada de `Series Code` faltantes desde la web de MISUMI México, asegurando un dataset completo y coherente.

3. **Feature Engineering**  
   Normalización, estandarización y construcción de nuevas variables relevantes para el análisis comercial.

4. **Data Visualization**  
   Desarrollo de visualizaciones interactivas para el funnel de conversión y los *Top parts* más relevantes por volumen total y clientes únicos.

5. **Funnel DLM Offering**  
   Filtrado específico del embudo para productos disponibles dentro del portafolio **DLM**, con el fin de evaluar su impacto comercial y oportunidades de crecimiento.

6. **Conclusiones de negocio**  
   Identificación de hallazgos clave que orientan la toma de decisiones estratégicas sobre portafolio, conversión y posicionamiento.

---

## ⚙️ Tecnologías utilizadas

- **Python**  
- **Pandas / NumPy / Matplotlib**
- **BeautifulSoup / Requests** (para web scraping)  
- **Google Colab / Jupyter Notebook**  
- **Data Wrangling y Feature Engineering**  
- **Visualización de embudos y análisis comparativo DLM**

---

## 📈 Principales resultados

- Construcción de un **funnel dinámico de conversión** a partir de datos reales de interacción del cliente.  
- Identificación de **pérdidas entre cotización y venta**, señalando áreas de oportunidad comercial.  
- Detección de **productos con alta intención de compra** (por generación y descargas CAD).  
- Evaluación cuantitativa del **desempeño del portafolio DLM** frente al universo total de *Locating Pins*.  
- Generación de **insights estratégicos** basados en datos para optimizar la gestión comercial de MISUMI México.

---

## 🧠 Autor

**Eduardo Antonio Leonardo Infante**  
AI Innovation Engineer – MISUMI México  
📧 Contacto profesional: https://www.linkedin.com/in/eduardo-l-0984a1140/

---

## 🗂️ Archivo principal

- `Git_LocatingPins_EALI.ipynb` → Notebook principal con todo el flujo analítico: carga, procesamiento, enriquecimiento y visualización.

---
