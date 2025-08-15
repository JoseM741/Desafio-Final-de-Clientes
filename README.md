# 📊 Desafío Final de Clientes

## 📝 Informe de Clasificación de Cancelación de Clientes

---

## 🎯 Misión

Desarrollar **modelos predictivos** capaces de prever qué clientes tienen mayor probabilidad de **cancelar sus servicios**.  
La empresa busca **anticiparse a la cancelación** y necesita un **pipeline robusto** para esta etapa inicial de modelado.

---

## 🎯 Objetivos del Desafío

- 🛠 Preparar los datos para el modelado (tratamiento, codificación y normalización).  
- 📊 Realizar análisis de correlación y selección de variables.  
- 🤖 Entrenar dos o más modelos de clasificación.  
- 📈 Evaluar el rendimiento de los modelos con métricas.  
- 🔍 Interpretar los resultados, incluyendo la **importancia de las variables**.  
- 🏆 Crear una conclusión estratégica señalando los principales factores que influyen en la cancelación.

---

## 🗂 Preparación de los Datos

Se utilizaron datos previamente procesados en el proyecto anterior, **limpios y de tipo binario (0 y 1)**.  

---

## 🧩 Metodología utilizada en el Desafío

1. 📂 Recuperación del archivo anterior del desafío.  
2. 📊 Verificación de la proporción de cancelación.  
3. 🔄 Pipeline predictivo para abandono.  
4. ⚖ Implementación de **SMOTE** en el pipeline para balancear clases.  
5. 🛠 Pipeline completo con codificación + SMOTE + modelo.  
6. 📈 Visualización de la **curva ROC**.  
7. 🎯 Ajuste de umbral para mejorar **Recall**.  
8. 📦 Box-Plots para análisis de distribución.  
9. 🔍 Determinación de variables más relacionadas con la cancelación de servicios.  
10. 🔄 Validación cruzada estratificada.  
11. 🔧 **RandomizedSearchCV** para optimizar RandomForest.  
12. 📌 Identificación de variables importantes para comunicar insights al negocio.

---

## 🤖 Métodos de Modelado

Se implementaron principalmente **modelos basados en árboles**, incluyendo:  
- Random Forest  
Para **estructurar todo el proceso de manera eficiente**, se utilizó un **Pipeline**, que permitió combinar:  
- 📦 **Preprocesamiento de datos** (codificación, normalización)  
- ⚖ **Balanceo de clases** con SMOTE  
- 🤖 **Entrenamiento del modelo**  

Esto garantiza que **todas las transformaciones se apliquen de manera consistente** y facilita la **evaluación y ajuste de los modelos**.  

---

## 🏁 Conclusiones

> Aquí se pueden incluir los **principales hallazgos** y recomendaciones estratégicas basadas en la importancia de las variables y patrones detectados en los datos.

