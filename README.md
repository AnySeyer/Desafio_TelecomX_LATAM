# 📊 Desafio_TelecomX_LATAM  (Análisis de Evasión de Clientes)

---

## 📑 Índice

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Objetivo](#objetivo)
3. [Tecnologías Utilizadas](#tecnologías-utilizadas)
4. [Metodología](#metodología)
5. [Análisis Exploratorio de Datos](#análisis-exploratorio-de-datos)
6. [Principales Hallazgos](#principales-hallazgos)
7. [Conclusiones](#conclusiones)
8. [Recomendaciones Estratégicas](#recomendaciones-estratégicas)
9. [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
10. [Autor](#autor)

---

## Descripción del Proyecto

Este proyecto tiene como finalidad analizar la **evasión de clientes (Churn)** en una empresa de telecomunicaciones mediante técnicas de análisis de datos en Python.

La evasión representa la cancelación del servicio por parte de los clientes, lo cual impacta directamente en los ingresos y la estabilidad financiera de la organización. A través de un proceso estructurado de limpieza, transformación y análisis exploratorio, se identificaron patrones asociados al abandono del servicio.

---

## Objetivo

Identificar factores que influyen en la cancelación del servicio y generar información estratégica que permita:

- Reducir la tasa de evasión.
- Mejorar la retención de clientes.
- Apoyar la toma de decisiones empresariales basadas en datos.

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Plotly  
- Jupyter Notebook / Google Colab  

---

## Metodología

### 1️⃣ Preparación y Limpieza de Datos

- Conversión a DataFrame.
- Normalización de datos.
- Traducción de columnas al español.
- Eliminación de espacios en blanco y duplicados.
- Manejo de valores nulos.
- Creación de variable derivada: **Cuentas_Diarias**.

### 2️⃣ Estandarización

- Traducción de categorías (género, contrato, método de pago, tipo de internet).

---

## Análisis Exploratorio de Datos

Se realizaron:

- Análisis descriptivo (media, mediana, desviación estándar).
- Distribución general de la evasión.
- Análisis por variables categóricas:
  - Género
  - Tipo de contrato
  - Método de pago
  - Tipo de internet
- Análisis por variables numéricas:
  - Cargos mensuales
  - Cargos totales
  - Meses de contrato

Las visualizaciones se desarrollaron utilizando gráficos profesionales e interactivos con Plotly.

---

## Principales Hallazgos

- Los contratos mensuales presentan mayor tasa de evasión.
- Clientes con menor antigüedad tienden a cancelar con mayor frecuencia.
- Existen diferencias en la evasión según tipo de internet.
- Algunos métodos de pago muestran mayor riesgo de abandono.
- El género no representa un factor determinante en la cancelación.

---

## Conclusiones

Conclusión: El análisis permitió identificar que la duración del contrato y el tipo de contrato son factores clave en la evasión de clientes. Los clientes con contratos mensuales y menor antigüedad presentan mayor probabilidad de cancelación. Esta información es fundamental para diseñar estrategias de retención más efectivas y segmentadas.

---

## Recomendaciones Estratégicas

1. Incentivar contratos de mayor duración.
2. Implementar programas de fidelización para clientes nuevos.
3. Analizar la calidad del servicio en segmentos críticos.
4. Promover métodos de pago automáticos.
5. Desarrollar modelos predictivos para anticipar el churn.

---

## Cómo Ejecutar el Proyecto

1. Clonar el repositorio:

```bash
git clone <https://github.com/AnySeyer/Desafio_TelecomX_LATAM>

```
---

## 👨‍💻 Autor

Proyecto desarrollado como parte de un desafío práctico en ALURALATAM_Data Science
