# 📊 Dashboard Power BI – Análisis Espacial y Temporal de Patentes en México

Este repositorio contiene un dashboard desarrollado en **Power BI Desktop** para analizar el comportamiento de las patentes registradas en México, integrando visualizaciones temporales, categóricas y geoespaciales. El objetivo es identificar patrones por clasificación CPC, evolución anual y ubicación geográfica.

---

## 🔧 Arquitectura del Proyecto

### 1. Origen y Transformación de Datos
- Limpieza y estructuración de datos mediante **Power Query**.
- Normalización de campos como:
  - Año de registro
  - Clasificación CPC
  - Coordenadas de ubicación
- Conversión de tablas a un esquema tipo **Star Schema** para optimizar la relación entre hechos y dimensiones.

---

## 📈 Funcionalidades del Dashboard

- **Recuento total de patentes registradas.**
- **Número de ciudades** con actividad de registro.
- **Gráfica temporal** que muestra el comportamiento de patentes a lo largo del tiempo.
- **Gráfica de participación por clasificación CPC** tipo dona/barras segmentadas.
- **Mapa geoespacial interactivo** con distribución de patentes por ciudad.
- **Segmentadores de usuario**:
  - Clasificación CPC  
  - Año  

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- **Power BI Desktop**
- **Power Query M**
- **DAX (Data Analysis Expressions)**
- **Modelado Tabular**
- **Mapas con Bing Maps**
- **Fuentes CSV/Excel**

---


