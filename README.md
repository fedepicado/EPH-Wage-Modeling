# Modelos de Regresión Estadística aplicados al Análisis de la Encuesta Permanente de Hogares

Este proyecto fue desarrollado en el marco de la materia **Enfoque Estadístico del Aprendizaje** (Maestría en Data Mining and Knowledge Discovery, segundo semestre 2023).  

El objetivo principal es analizar el **salario horario de las personas en Argentina** utilizando datos de la **Encuesta Permanente de Hogares (EPH)**.  
A partir de las variables disponibles, se busca **evaluar y comparar diferentes modelos de regresión estadística**, considerando dos perspectivas complementarias:  

1. **Explicabilidad:** identificar relaciones entre variables y entender los determinantes del salario.  
2. **Capacidad predictiva:** seleccionar el modelo que mejor prediga el salario horario, aunque ello implique mayor complejidad o menor interpretabilidad.  

---

## Objetivos
- Construir modelos de regresión lineal simple y múltiple para estudiar el salario horario.  
- Analizar el trade-off entre **modelos interpretables** (sencillos, con coeficientes claros) y **modelos predictivos** (con mejor ajuste, aunque menos interpretables).  
- Evaluar la **significancia estadística** de los predictores.  
- Probar **modelos robustos** que permiten atenuar el impacto de outliers en los resultados.  
- Responder a las **consignas propuestas en la guía de la materia**, documentando el proceso completo.   

---

## Herramientas Utilizadas
- **Lenguaje:** R  
- **Bibliotecas principales:**  
  - `tidyverse`
  - `tidymodels`
  - `robustbase`
---

## Estructura del Proyecto
El proyecto sigue la **estructura planteada en las consignas de la materia**, incluyendo:  
- Preprocesamiento y exploración inicial de los datos.  
- Modelado con regresiones lineales simples, múltiples, con términos cuadráticos e interacciones.  
- Estimación de modelos robustos frente a la presencia de outliers.  
- Comparación entre modelos interpretables y modelos con mayor poder predictivo.  

---

## Resultados y Conclusiones
- Se observan diferencias de género en el efecto de la educación sobre el salario.  
- La experiencia potencial muestra un efecto no lineal (rendimientos crecientes pero decrecientes a tasas altas).  
- Los modelos robustos resultan útiles para validar la estabilidad de las conclusiones ante valores extremos.  
- La elección del “mejor modelo” depende del objetivo: **explicar relaciones** o **maximizar la capacidad predictiva**.  

---

## Relevancia
Este trabajo refleja la **aplicación práctica de modelos de regresión en R**, integrando:  
- Análisis descriptivo y exploratorio.  
- Construcción y diagnóstico de modelos.  
- Evaluación de modelos robustos ante outliers.  
- Discusión crítica sobre el balance entre **explicabilidad** y **poder predictivo**.  

De este modo, combina tanto el rigor estadístico como la orientación aplicada, mostrando cómo distintas estrategias de modelado responden a objetivos analíticos diferentes.  

---
