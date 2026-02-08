# 📊Análisis de riesgos y régimen de mercado basado en eventos (SQL)

## 📌Descripción

Este proyecto reúne una colección de análisis cuantitativos orientados a eventos de mercado y corporativos, desarrollados íntegramente en SQL, con foco en tendencia, volatilidad, noticias, riesgo sistémico y detección de regímenes de mercado.

El repositorio busca identificar señales técnicas y estadísticas que preceden o acompañan eventos relevantes (noticias, shocks sectoriales, fusiones y adquisiciones), transformándolas en insights accionables para research y risk analysis.

## 🎯Objetivos del Proyecto

- Detectar regímenes de mercado y zonas de estrés
- Analizar la dinámica de la volatilidad antes y después de eventos
- Identificar señales anticipatorias (ej. compresión de volatilidad)
- Medir el impacto de noticias y eventos corporativos
- Evaluar propagación del riesgo a nivel industria y sector
- Demostrar uso avanzado de SQL aplicado a finanzas

## 🧠Enfoque Analítico

El proyecto combina:
- Indicadores técnicos (ADX, volatilidad histórica)
- Volatilidad implícita como expectativa del mercado
- Análisis pre-evento vs. post-evento
- Métricas estadísticas (kurtosis, extremos)
- Coincidencia temporal de señales técnicas y eventos
- Agregación a nivel activo, industria y sector

Preguntas clave:
- ¿Cuándo la baja volatilidad anticipa un evento relevante?
- ¿Qué señales técnicas preceden fusiones y adquisiciones?
- ¿Cómo se propaga el riesgo tras un shock informativo?
- ¿Cuándo el mercado cambia de régimen?

## 🗂️Contenido del Repositorio

📁 Insights Principales

- Clasificación de Tickers por Robustez de la Tendencia (ADX)
- Clasificación de Eventos por Volatilidad Post-Evento
- Cobertura de la Volatilidad Sectorial por Eventos
- Cobertura de Noticias y Volatilidad Implícita (Kurtosis)
- Coincidencia de Eventos Negativos en la Industria
- Coincidencia de Extremos Técnicos y Noticias
- Compresión de Volatilidad previa a Fusiones y Adquisiciones (M&A)

Cada insight está implementado como un query SQL independiente, orientado a detectar un patrón específico del mercado.

## 🧮Tecnologías Utilizadas

- SQL
- Bases de datos relacionales
- Compatible con PostgreSQL / MySQL / BigQuery

## 🗃️Modelo de Datos (conceptual)

- tickers
- ticker_id
- nombre_empresa
- sector
- industria
- indicadores_tecnicos
- ticker_id
- fecha
- ADX, volatilidad, métricas estadísticas
- eventos / noticias / corporativos
- ticker_id
- fecha_evento
- tipo_evento (noticia, M&A, etc.)
- volatilidad_implicita
- ticker_id
- fecha
- métricas implícitas

## 📈Casos de Uso

- Detección temprana de eventos corporativos
- Análisis de regímenes de baja y alta volatilidad
- Research event-driven
- Evaluación de riesgo sistémico y sectorial
- Apoyo a estrategias cuantitativas

## ⚠️Consideraciones

- Las señales anticipatorias no garantizan eventos
- La coincidencia temporal no implica causalidad

Se recomienda complementar con:
- análisis fundamental
- gestión de riesgo
- validación histórica (backtesting)

## 🚀Posibles Extensiones

- Score de probabilidad de evento corporativo
- Backtesting de señales de compresión de volatilidad
- Integración con Python / BI
- Visualización de cambios de régimen

## 👤Autor

Flavia Hepp
Event-Driven Market Analytics · Risk & Regime Detection · SQL
