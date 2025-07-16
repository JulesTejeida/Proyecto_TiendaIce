# Proyecto Tienda Ice 🎮🧊

Este proyecto fue desarrollado como parte del programa de análisis de datos de TripleTen. El objetivo es ayudar a la tienda online **Ice**, que vende videojuegos a nivel mundial, a identificar patrones que determinen si un juego será exitoso o no. Esta información permitirá planificar campañas de marketing más efectivas.

## 🧠 Objetivo
Analizar datos históricos de ventas, reseñas, plataformas y géneros de videojuegos para detectar factores clave de éxito comercial y ayudar a definir estrategias para el año 2017.

## 📦 Datos utilizados
Se trabajó con el dataset `games.csv`, que contiene información sobre:

- Nombre del juego
- Plataforma (ej. Xbox, PlayStation)
- Año de lanzamiento
- Género
- Ventas por región (NA, EU, JP, Otros)
- Calificaciones de críticos y usuarios
- Clasificación ESRB

## 🔍 Proceso de análisis

1. **Preparación de datos:**
   - Limpieza, conversión de tipos y tratamiento de valores nulos.
   - Cálculo de ventas totales globales.

2. **Análisis exploratorio:**
   - Plataformas líderes y en declive.
   - Reseñas vs. ventas.
   - Géneros más rentables.
   - Comparación por año y región.

3. **Perfil de usuario por región (NA, EU, JP):**
   - Plataformas y géneros más populares.
   - Influencia de clasificaciones ESRB.

4. **Pruebas de hipótesis:**
   - Comparación de calificaciones entre plataformas y géneros.

## 📊 Herramientas utilizadas

- Python (Pandas, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook

## 🧾 Conclusión

Los resultados del análisis permiten identificar los juegos más prometedores y orientar las decisiones de marketing según regiones y plataformas. También se validaron hipótesis relevantes sobre el comportamiento de los usuarios y las calificaciones.

---

**Nota:** Este análisis se realizó simulando estar en diciembre de 2016, con el propósito de planificar campañas para el 2017.
