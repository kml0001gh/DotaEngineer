# DotaEngineer 🎮📊

**DotaEngineer** es una plataforma de análisis y toma de decisiones basada en datos para Dota 2. Utiliza información de la API de OpenDota y partidas profesionales para identificar tendencias emergentes, mejorar la fase de draft y explorar el impacto de los héroes en el juego competitivo.

---

## 🚀 Objetivos

### 1. Meta Analyzer & Predictor 🔮
- Detectar **tendencias emergentes** de héroes, ítems o estilos de juego que podrían convertirse en *meta* antes de que se generalicen.
- Usar **datos filtrados por parche**, **medalla** y **frecuencia reciente**.
- Asignar **mayor peso** a partidas de alto MMR o de jugadores profesionales (EWC, Div 1, etc.).
- Analizar no sólo victorias, sino también **performance contextual** (impacto sin necesidad de ganar la partida).

---

### 2. Player Context-Aware Drafting Tool 🧠
- Herramienta de drafteo inteligente que:
  - Tiene en cuenta **counters y sinergias**.
  - Analiza el **historial reciente de los jugadores** para predecir la intención real de un pick.
  - Sugiere **baneos contextuales**, según el historial y desempeño del rival.

---

### 3. In-depth Hero Analysis 🔍
- Analizar profundamente la forma de jugar un héroe específico:
  - Builds de ítems y habilidades.
  - Rotaciones efectivas por el mapa.
  - Tips y timings clave.
- Esta funcionalidad requerirá análisis de **archivos .dem** o incluso videos `.mp4` para capturar datos no disponibles vía API.

---

## 🛠️ Tecnologías

- **Lenguaje:** Python 3.11+
- **APIs:** OpenDota, Stratz (evaluación)
- **Data Science:** pandas, scikit-learn, XGBoost, PyTorch (para modelos complejos)
- **Visualización:** Streamlit, Dash
- **Base de datos:** PostgreSQL
- **Otros:** GitHub Actions, Docker

---

## 📁 Estructura del proyecto