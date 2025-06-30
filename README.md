# 📊 Customer Churn Analysis - Allura Latam Challenge

Este proyecto tiene como objetivo **analizar el abandono de clientes (churn)** en una empresa de servicios digitales. A través de técnicas de **limpieza de datos, transformación, visualización y análisis estadístico**, se busca comprender los factores que influyen en la pérdida de clientes y generar insights accionables para el área de negocio.

---

## 📁 Estructura del Proyecto

- `datos/`: archivos de entrada y datasets procesados
- `notebooks/`: desarrollo completo del análisis en Jupyter o Google Colab
- `imagenes/`: visualizaciones generadas
- `README.md`: documentación general del proyecto

---

## 🧠 Objetivos

1. **Entender la distribución del abandono** de clientes en el dataset.
2. **Identificar variables clave** que influyen en la decisión de abandono.
3. **Visualizar patrones** ocultos mediante gráficos categóricos y numéricos.
4. **Proponer acciones estratégicas** para la retención de clientes.

---

## 🧼 Preprocesamiento y Limpieza

- Eliminación de registros con valores vacíos o inconsistentes.
- Normalización de columnas anidadas (diccionarios dentro de celdas).
- Conversión de variables categóricas a binarias (Sí/No → 1/0).
- Renombramiento de columnas para mayor claridad y accesibilidad.
- Estandarización de variables numéricas.

---

## 📊 Análisis Exploratorio de Datos (EDA)

Se utilizaron gráficos para analizar la variable `abandono` frente a:

- Variables categóricas (como tipo de contrato, método de pago, uso de servicios).
- Variables numéricas (antigüedad, cargos mensuales, cantidad de cuentas, etc.).

Esto permitió detectar relaciones entre el abandono y:

- Tipo de contrato mensual
- Servicios no contratados (como soporte técnico o seguridad online)
- Uso de factura digital y métodos de pago

---

## 📈 Conclusiones Iniciales

- Los clientes con **contratos mensuales** y **servicios técnicos desactivados** tienden a abandonar más.
- El **método de pago electrónico** se asocia con una mayor tasa de abandono.
- **Cargos más altos** también muestran cierta correlación con la evasión.
- Se evidencia la importancia de **prolongar la permanencia** (antigüedad) para mejorar la retención.

---

## 🛠 Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (para estandarización)
- Google Colab

---

## 💡 Próximos pasos

- Implementar modelos de machine learning para **predecir el abandono**.
- Crear un **dashboard interactivo** con Power BI o Streamlit.
- Proponer una estrategia de **segmentación de clientes** para acciones de fidelización.

---

## 🙋‍♀️ Autora

**Natalia Noemí Liscio**  
Challenge de Análisis de Datos - Allura Latam  
Contacto: [LinkedIn](https://www.linkedin.com/in/natalialiscio/) | [GitHub](https://github.com/NataliaLiscio1985) 

---

## 📝 Licencia

Este proyecto se desarrolla con fines educativos y de evaluación en el marco del challenge de Allura Latam. Libre para uso no comercial.

