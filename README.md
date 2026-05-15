# 📉 Customer Retention Intelligence & Predictive Churn Analytics

# 🎯 Objetivo Estratégico

Desarrollar una solución analítica capaz de transformar datos de comportamiento de clientes en decisiones accionables para reducir pérdida de ingresos recurrentes y mejorar la eficiencia de retención.

El proyecto busca responder tres necesidades críticas del negocio:

- Detectar clientes con mayor riesgo de cancelación
- Identificar factores con mayor impacto en el churn
- Priorizar acciones de retención según valor y riesgo

La solución integra SQL, Python y Power BI para construir un flujo completo de inteligencia comercial y predicción de abandono.

---

# 🧠 Contexto de Negocio

En modelos basados en suscripción, pequeñas variaciones en la tasa de churn generan impactos significativos sobre ingresos, rentabilidad y crecimiento sostenido.

La organización enfrentaba múltiples desafíos:

- Incremento progresivo en abandono de clientes
- Escasa visibilidad sobre patrones de fuga
- Retención reactiva en lugar de preventiva
- Campañas comerciales poco segmentadas
- Dificultad para priorizar clientes de alto riesgo

Como consecuencia, la empresa destinaba recursos de retención sin una estrategia basada en datos, reduciendo eficiencia operativa y aumentando costos comerciales.

---

# ❓ Pregunta Estratégica del Proyecto

¿Qué variables explican el abandono de clientes y cómo puede la organización anticipar cancelaciones para intervenir antes de la pérdida del cliente?

---

# 🚀 Hallazgos Clave para la Toma de Decisiones

| Insight Estratégico | Impacto Detectado | Oportunidad de Negocio |
|---|---|---|
| El 26.54% de los clientes presenta churn | Pérdida relevante de ingresos recurrentes | Implementar retención predictiva |
| Contratos mensuales concentran la mayor fuga | Alta volatilidad de clientes | Incentivar planes anuales |
| Clientes con cargos elevados muestran mayor abandono | Sensibilidad al pricing | Optimizar estructura de precios |
| El servicio de fibra óptica posee mayor churn | Riesgo operativo y de experiencia | Revisar calidad y propuesta de valor |
| El modelo predictivo alcanza ~80% de precisión | Capacidad de anticipación temprana | Priorizar campañas de retención |

---

# 📊 Dashboard Ejecutivo

![Dashboard de Churn](img/grafica-analisis-churn.png)

🔗 **Acceso al dashboard interactivo:**  
👉 [Customer Retention Dashboard](https://github.com/GuilleBerrutti/analysis-churn/tree/main/dashboard)

---

# 📈 Insights Estratégicos de Negocio

## 📄 Contratos Mensuales: Principal Foco de Riesgo

El análisis identificó que los clientes con contratos mensuales presentan una probabilidad de cancelación significativamente superior respecto a contratos de largo plazo.

### 🎯 Interpretación Estratégica

La ausencia de compromiso contractual incrementa la volatilidad del ingreso recurrente y reduce estabilidad financiera.

### ✅ Decisión Recomendada

- Diseñar incentivos para migración a contratos anuales
- Implementar descuentos por permanencia
- Activar campañas preventivas en clientes próximos a renovación

### 📌 Impacto Esperado

Una reducción parcial del churn en este segmento podría generar mejoras directas sobre estabilidad de ingresos y lifetime value.

---

## 🌐 Fibra Óptica: Segmento con Mayor Tasa de Abandono

Los clientes asociados al servicio de fibra óptica concentraron los niveles más elevados de churn dentro de la base analizada.

### 🎯 Interpretación Estratégica

El patrón detectado sugiere posibles fricciones vinculadas a:

- percepción de valor,
- experiencia del servicio,
- soporte técnico,
- o pricing competitivo.

### ✅ Decisión Recomendada

- Priorizar auditorías de experiencia en este segmento
- Implementar monitoreo de satisfacción
- Diseñar ofertas de retención específicas para fibra óptica

### 📌 Impacto Esperado

Reducir el abandono en este segmento tendría efecto directo sobre ingresos de clientes de mayor ticket promedio.

---

## 💰 Sensibilidad al Precio y Riesgo de Cancelación

El incremento en cargos mensuales mostró correlación directa con mayor probabilidad de abandono.

### 🎯 Interpretación Estratégica

El análisis evidencia que determinados segmentos presentan elasticidad al precio superior a la esperada.

### ✅ Decisión Recomendada

- Implementar pricing segmentado
- Crear bundles personalizados
- Diseñar beneficios de fidelización para clientes de alto valor

### 📌 Impacto Esperado

La optimización de pricing permitiría disminuir cancelaciones sin afectar significativamente ingresos promedio.

---

## 🤖 Predicción Temprana de Churn

El modelo de Machine Learning logró una precisión cercana al 80%, permitiendo detectar clientes con alta probabilidad de abandono antes de su cancelación efectiva.

### 🎯 Valor para el Negocio

La capacidad predictiva transforma la retención desde un enfoque reactivo hacia una estrategia preventiva basada en riesgo.

### ✅ Aplicaciones Estratégicas

- Priorización automática de clientes críticos
- Activación temprana de campañas de retención
- Optimización de inversión comercial
- Reducción de costos de adquisición por reemplazo de clientes perdidos

---

# 🤖 Modelo Predictivo de Churn

Se desarrolló un modelo de Regresión Logística utilizando Scikit-learn para estimar probabilidad de abandono y detectar variables con mayor impacto sobre churn.

## 📊 Capacidades del Modelo

- Scoring de riesgo por cliente
- Predicción de cancelación
- Segmentación automática
- Identificación de variables críticas
- Priorización de retención basada en riesgo

![Importancia de Variables](img/variable_de_fuga.png)

---

# 📦 KPIs Estratégicos Analizados

- Churn Rate
- Riesgo de abandono por contrato
- Distribución de clientes por servicio
- Customer Lifetime Value potencial
- Riesgo por segmento
- Impacto del pricing sobre churn
- Antigüedad promedio de clientes
- Variables predictivas de cancelación

---

# 🛠️ Metodología Analítica

El proyecto fue desarrollado mediante un flujo completo de analítica de negocio y Machine Learning.

## 📥 Ingeniería y Preparación de Datos

- Limpieza y transformación con SQL
- Estandarización de variables
- Tratamiento de valores faltantes
- Feature engineering
- Construcción de variables analíticas

## 📊 Exploración y Visualización

- Segmentación de clientes
- Detección de patrones de abandono
- Análisis de comportamiento
- Visualización ejecutiva en Power BI

## 🤖 Machine Learning

- Regresión logística con Scikit-learn
- Evaluación de precisión
- Interpretación de variables predictivas
- Validación de capacidad predictiva

---

# 📈 Impacto Potencial para el Negocio

La implementación de una estrategia de retención basada en analítica predictiva permitiría:

- Detectar clientes críticos antes de su abandono
- Optimizar recursos comerciales
- Reducir pérdida de ingresos recurrentes
- Mejorar eficiencia de campañas de fidelización
- Incrementar estabilidad de ingresos a largo plazo

El proyecto demuestra cómo la combinación de analítica avanzada y visualización ejecutiva puede transformar datos operativos en decisiones estratégicas de alto impacto.

---

# 🚀 Recomendaciones Estratégicas

| Recomendación | Objetivo |
|---|---|
| Incentivar contratos de largo plazo | Reducir volatilidad de churn |
| Implementar scoring predictivo | Anticipar cancelaciones |
| Optimizar pricing por segmento | Reducir sensibilidad al precio |
| Revisar experiencia de fibra óptica | Disminuir churn operativo |
| Priorizar clientes de alto valor | Maximizar eficiencia comercial |
| Automatizar campañas de retención | Mejorar velocidad de respuesta |

---

# 🛠️ Stack Tecnológico

| Tecnología | Aplicación |
|---|---|
| PostgreSQL | Transformación y limpieza de datos |
| Python | Análisis y Machine Learning |
| Scikit-learn | Modelado predictivo |
| Power BI | Dashboard ejecutivo |
| Pandas | Manipulación de datos |
| Matplotlib & Seaborn | Visualización analítica |

---

# 📂 Dataset Utilizado

El análisis fue desarrollado a partir de una base de clientes con información relacionada a:

- Contratos
- Servicios contratados
- Antigüedad
- Facturación
- Pricing
- Soporte técnico
- Métodos de pago
- Estado de abandono

📥 **Acceso al dataset:**  
👉 [Descargar dataset de churn](Data/customer_churn_dataset.xlsx)

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
