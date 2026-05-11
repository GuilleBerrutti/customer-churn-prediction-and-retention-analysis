# 📉 Customer Retention & Churn Intelligence

Análisis estratégico de retención de clientes orientado a identificar patrones de abandono, detectar segmentos de alto riesgo y desarrollar modelos predictivos para optimizar estrategias de fidelización y reducir pérdida de ingresos.

---

# 🎯 Objetivo del Proyecto

Desarrollar un sistema analítico capaz de:

- Detectar factores asociados al churn
- Identificar segmentos críticos de abandono
- Anticipar cancelaciones mediante modelos predictivos
- Optimizar decisiones de retención basadas en datos

El proyecto integra SQL, Python y Power BI para transformar comportamiento de clientes en insights accionables orientados a negocio.

---

# 🧠 Problema de Negocio

En modelos de suscripción, la pérdida de clientes impacta directamente en ingresos recurrentes y rentabilidad.

La organización enfrentaba:

- Alta tasa de abandono de clientes
- Escasa capacidad de anticipación del churn
- Falta de segmentación de riesgo
- Dificultad para identificar drivers de cancelación
- Baja eficiencia en estrategias de retención

👉 Pregunta central del análisis:

**¿Qué variables impulsan el abandono de clientes y cómo pueden mitigarse mediante analítica predictiva y segmentación estratégica?**

---

# 🚀 Resultados Clave del Negocio

| KPI Estratégico | Resultado |
|---|---|
| Tasa total de churn | 26.54% de los clientes presentan abandono |
| Riesgo contractual | Clientes con contratos mensuales concentran la mayor tasa de fuga |
| Sensibilidad al precio | Clientes con cargos elevados muestran mayor probabilidad de cancelación |
| Segmento crítico | Servicio de fibra óptica presenta niveles superiores de churn |
| Precisión predictiva | Modelo de Machine Learning con aproximadamente 80% de precisión |

---

# 📊 Dashboard Ejecutivo

![Dashboard de Churn](img/grafica-analisis-churn.png)

🔗 **Acceso al dashboard interactivo:**  
👉 [Customer Retention Dashboard](https://github.com/GuilleBerrutti/analysis-churn/tree/main/dashboard)

---

# 📂 Dataset Utilizado

El análisis fue desarrollado a partir de una base de datos de clientes con información relacionada a:

- Tipo de contrato
- Servicios contratados
- Antigüedad del cliente
- Cargos mensuales
- Facturación total
- Método de pago
- Soporte técnico
- Estado de abandono

📥 **Acceso al dataset:**  
👉 [Descargar dataset de churn](Data/customer_churn_dataset.xlsx)

---

# 📦 KPIs Estratégicos Analizados

- Tasa de churn
- Riesgo de abandono por contrato
- Distribución de clientes por servicio
- Lifetime value potencial
- Churn por segmento
- Impacto de cargos mensuales
- Antigüedad promedio de clientes
- Variables predictivas de fuga

---

# 📈 Insights Estratégicos

## 📄 Tipo de Contrato y Riesgo de Fuga

Los clientes con contratos mensuales registraron una probabilidad de churn significativamente superior respecto a contratos de largo plazo.

### 💡 Impacto de Negocio

Esto evidencia que contratos de mayor permanencia generan estabilidad de ingresos y reducen volatilidad en retención.

---

## 🌐 Servicio de Fibra Óptica

El segmento de clientes con fibra óptica presentó las tasas más elevadas de abandono dentro de la base analizada.

### 💡 Insight

El comportamiento detectado sugiere posibles oportunidades de mejora relacionadas a percepción de valor, calidad del servicio o pricing.

---

## 💰 Sensibilidad al Precio

Se identificó una relación directa entre incremento de cargos mensuales y mayor probabilidad de cancelación.

### 💡 Recomendación Estratégica

La optimización de pricing y creación de bundles personalizados podría reducir significativamente el churn en segmentos sensibles al precio.

---

## 🤖 Predicción de Abandono

El modelo de regresión logística alcanzó una precisión cercana al **80%**, permitiendo identificar clientes con alta probabilidad de cancelación antes de su abandono.

### 💡 Valor Estratégico

La implementación de modelos predictivos permite priorizar campañas de retención y optimizar costos comerciales.

---

# 🤖 Modelo Predictivo de Churn

Se implementó un modelo de **Regresión Logística** para predecir probabilidad de abandono y detectar variables de mayor impacto en el churn.

### 📊 Capacidades del Modelo

- Predicción de riesgo por cliente
- Identificación de variables críticas
- Segmentación automática de clientes
- Priorización de acciones de retención

![Importancia de Variables](img/variable_de_fuga.png)

---

# 🛠️ Metodología Analítica

El proyecto fue desarrollado mediante un flujo completo de análisis de datos y Machine Learning.

### 📥 Extracción y Transformación
- Limpieza y preparación de datos con SQL
- Normalización de variables
- Tratamiento de datos faltantes
- Construcción de variables analíticas

### 📊 Exploración y Visualización
- Segmentación de clientes en Power BI
- Detección de patrones de churn
- Análisis de comportamiento y distribución

### 🤖 Modelado Predictivo
- Regresión logística con Scikit-learn
- Evaluación de precisión y métricas
- Interpretación de variables predictivas

---

# 📈 Conclusión Ejecutiva

El análisis demuestra que el churn puede anticiparse mediante segmentación estratégica y modelos predictivos, permitiendo reducir pérdida de clientes y mejorar rentabilidad.

La combinación de Power BI, SQL y Machine Learning facilita decisiones más precisas sobre retención, pricing y experiencia del cliente.

---

# 🚀 Recomendaciones Estratégicas

- Incentivar contratos de largo plazo
- Optimizar pricing en segmentos sensibles
- Revisar experiencia del servicio de fibra óptica
- Implementar campañas predictivas de retención
- Priorizar clientes de alto valor con riesgo de fuga

---

# 🛠️ Stack Tecnológico

| Tecnología | Uso |
|---|---|
| PostgreSQL | Limpieza y transformación de datos |
| Python | Modelado predictivo y análisis |
| Scikit-learn | Machine Learning |
| Power BI | Dashboard ejecutivo e insights visuales |
| Pandas | Manipulación de datos |
| Matplotlib & Seaborn | Visualización estadística |

---

# 📁 Estructura del Repositorio

```text
analysis-churn/
│
├── README.md
│
├── dashboard/
│   └── customer_retention_dashboard.pbix
│
├── data/
│   └── customer_churn_dataset.xlsx
│
├── python/
│   └── churn_prediction_model.py
│
├── sql/
│   └── churn_data_cleaning.sql
│
└── img/
    ├── grafica-analisis-churn.png
    └── variable_de_fuga.png
