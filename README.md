# 🚀 LiveOps Engine 3.0

**LiveOps Engine** es una solución avanzada de automatización desarrollada en **Python (AI3 Layer)** diseñada para optimizar la gestión logística en tiempo real.  
Esta herramienta actúa como una **capa inteligente sobre sistemas existentes**, eliminando cuellos de botella operativos y automatizando tareas manuales y repetitivas del equipo de LiveOps Chile.

---

## 📊 Hitos Destacados (2025)

- **Volumen de Gestión:** +47,000 órdenes procesadas.
- **Eficiencia:** En solo **1 mes** se gestionó el equivalente a **1 año de trabajo manual** previo.
- **Automatización:** **88%** de *share* de gestión autónoma en periodos de alta demanda.
- **Efectividad:** Tasa de éxito sostenida del **89%** en Q4.
- **Impacto Fail Rate:** Reducción de **21.8% → 11.8%** en órdenes Accepted (+35 min), intervención donde ICE no cubría eficientemente.

---

## 🛠️ Stack Tecnológico

- **Lenguaje:** Python 3.11x  
- **Interfaz:** PyQt5 (arquitectura modular de paneles)  
- **Automatización:** Selenium & Multithreading  
- **Data Pipeline:** Google BigQuery, Sheets API & Grafana  
- **Arquitectura:** Patrón **MVC (Model–View–Controller)** bajo principios **SOLID**

---

## 🚀 Funcionalidades Implementadas

### Gestión Stagnant (Core)
Detección y resolución proactiva de órdenes en estados críticos (*NDO, Accepted, Pickup*). Opera en modo headless silencioso, evaluando cada orden contra una Matriz de Decisión validada con el equipo Regional.

### Reporting en Tiempo Real
Extracción, procesamiento y envío de alertas a Slack en menos de 30 segundos. Incluye métricas de saturación, análisis de ineficiencias y revisión de órdenes activas.

### Alertas Operacionales (Producción)
- **Alertas de Saturación Dmart** — Trigger automático para ejecución de HDM
- **Alertas VFR** — Vendor Fail Rate para integraciones Food
- **Alertas de Conectividad** — Piloto Dunkin Donuts (locales cerrados)
- **Push Masivo a Flota** — Comunicaciones one-click por ciudad y estado

### Proyectos Exploratorios (En desarrollo)
- Activación Inteligente de Eventos en DAS
- Alertas de Lluvia en Tiempo Real
- Seteo Automático de Incentivos (quests)
- Ejecución Automática HDM Dmart
- Scraping Benchmark Competencia (Uber Eats)

---

## 🔗 Páginas del Proyecto

| Página | Descripción |
|--------|-------------|
| `index.html` | Dashboard principal con métricas, arquitectura y performance |
| `resumen-ejecutivo.html` | Resumen ejecutivo para presentación M-Level |

---

## 📦 Instalación Rápida

1. Clona el repositorio.
2. Crea un entorno virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
3. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Ejecuta la aplicación:
   ```bash
   python main.py
   ```

---

## 🏗️ Arquitectura del Proyecto

El Engine opera como **tercera capa de gestión** sobre los sistemas existentes (Hurrier + ICE). Actúa específicamente donde ICE no alcanza con suficiente precisión, y genera el *business case* para mejorar las configuraciones del sistema automático corporativo a nivel regional.

```
Live_Ops_Engine/
├── index.html              ← Dashboard principal
├── resumen-ejecutivo.html  ← Resumen ejecutivo M-Level
├── styles.css              ← Light mode styles
├── styles-dark.css         ← Dark mode styles
├── README.md
└── stack/
    ├── UI3.0.png
    ├── bigquery.svg
    ├── hurrier.png
    └── ...assets
```

---

**Desarrollado localmente · Seguro · Documentado · LiveOps Chile 2025**