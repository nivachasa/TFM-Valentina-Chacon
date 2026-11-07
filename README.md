# TFM · Predicción temprana del abandono en educación superior

Trabajo Fin de Máster · Máster Universitario en Inteligencia Artificial (UNIR)
Autora: Nicole Valentina Chacón Sánchez · Director: Javier Ricardo Luna Pineda
Tipo 1 · Piloto experimental (caso base frente a caso experimental)

**Título:** Predicción temprana del abandono en educación superior con datos de
matrícula y modelos de ensamble frente a reglas tradicionales.

## Objetivo

Determinar si un modelo de ensamble entrenado solo con la información
disponible en la matrícula (E1) identifica a los estudiantes que abandonan con
una sensibilidad no inferior en más de cinco puntos a la de una regla de
rendimiento académico aplicada al cierre del primer semestre (E2), cuando ambos
señalan la misma proporción de estudiantes. El trabajo documenta además la
contribución de las variables (SHAP) y las diferencias de desempeño entre
subgrupos.

## Datos

El repositorio incluye una copia **sin modificar** del conjunto de datos
*Predict Students' Dropout and Academic Success* (UCI Machine Learning
Repository, id 697).

Realinho, V., Vieira Martins, M., Machado, J., y Baptista, L. (2021).
*Predict Students' Dropout and Academic Success* [Conjunto de datos]. UCI
Machine Learning Repository. https://doi.org/10.24432/C5MC89

- Archivo: `TFM-Valentina-Chacon/Datos/predict+students+dropout+and+academic+success/data.csv`
  (separador `;`, UTF-8 con BOM).
- 4.424 estudiantes, 36 predictores y la columna `Target`
  (Graduate 49,9 %, Dropout 32,1 %, Enrolled 17,9 %).
