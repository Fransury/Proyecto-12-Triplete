# 📊 Análisis y Dashboard Interactivo de Tendencias en YouTube para Marketing Publicitario
## 📌 Descripción del Proyecto
Este proyecto consiste en el análisis de tendencias de videos en YouTube y el desarrollo de un dashboard interactivo diseñado para apoyar la toma de decisiones estratégicas en campañas publicitarias.
La agencia Sterling & Draper busca optimizar su planificación de campañas a partir de datos sobre videos en tendencia, categorías más populares y distribución geográfica de tendencias. El dashboard permite explorar de forma dinámica cómo varían las categorías y qué regiones tienen mayor impacto en las preferencias de los usuarios.

---

## 🎯 Objetivos del Proyecto
* Analizar los videos en tendencia de YouTube para identificar patrones en categorías, regiones y fechas.
* Desarrollar un dashboard interactivo que agilice la consulta de tendencias y facilite la toma de decisiones.
* Responder preguntas clave como:
  * ¿Qué categorías son más populares en cada región?
  * ¿Cómo cambian las tendencias semana a semana?
  * ¿Qué países presentan mayor concentración de videos virales?
 
---

## 🗂 Dataset
Los datos provienen de tablas agregadas de tendencias de YouTube:
* trending_by_time
  * record_id: Clave primaria del registro.
  * region: País o región geográfica.
  * trending_date: Fecha en la que un video se convierte en tendencia.
  * category_title: Categoría del video (ej. entretenimiento, música, política).
  * videos_count: Número de videos en tendencia por día.
Los datos se actualizan cada **24 horas** (medianoche UTC).

---

# 🛠️ Herramientas y Tecnologías
* **Lenguaje:** Python
* **Librerías:** pandas, numpy, matplotlib, seaborn, plotly
* **Dashboard:** Tableau
* **Entorno:** Jupyter Notebook

---

# 📈 Visualizaciones del Dashboard
**1. Tendencias históricas:**
  * Gráficos de barras y líneas para analizar evolución semanal de categorías.
**2. Distribución de videos por región:**
  * Mapas y gráficos apilados para comparar regiones geográficas.
**3. Correspondencia entre categorías y países:**
  * Tablas y heatmaps mostrando qué categorías dominan en cada región.

# 🚀 Resultados Esperados
* Un **dashboard interactivo** actualizado diariamente, listo para su uso por el equipo de marketing.
* **Insights accionables** para optimizar campañas publicitarias basadas en datos reales de consumo de contenido.
* Reducción del tiempo de análisis manual de tendencias y mayor rapidez en la **toma de decisiones estratégicas.**

# 📌 Impacto del Proyecto
Este proyecto aporta valor al permitir que los gerentes de publicidad:
  * ✅ Detecten patrones en el comportamiento de usuarios.
  * ✅ Tomen decisiones informadas para campañas en distintas regiones.
  * ✅ Enfoquen esfuerzos de marketing en categorías y mercados de mayor potencial.
