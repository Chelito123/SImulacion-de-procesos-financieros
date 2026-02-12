# Simulación de Procesos Financieros 📈

Este repositorio contiene los proyectos y algoritmos desarrollados para la materia de **Simulación de Procesos Financieros**. El enfoque principal es la aplicación del **Método de Montecarlo** para la valoración de activos, análisis de riesgo y resolución de problemas matemáticos mediante simulación estocástica.

---

## 🎯 Objetivos del Curso
* Modelar el comportamiento de activos financieros mediante procesos estocásticos.
* Implementar simulaciones de Montecarlo para estimar variables financieras y constantes matemáticas.
* Analizar la relación riesgo-rendimiento mediante métricas de volatilidad, asimetría (skewness) y curtosis.
* Integrar indicadores estratégicos mediante el marco del Balanced Scorecard (BSC).

---

## 💻 Contenido del Repositorio

### 1. Estimación de Áreas e Integrales (Montecarlo Hit-or-Miss)
Implementación de algoritmos para resolver integrales definidas mediante muestreo aleatorio.
* **Cálculo de $\pi$:** Aproximación mediante la simulación de puntos en un cuadrante de círculo unitario.
* **Integración Numérica:** Resolución de funciones polinómicas complejas manejando áreas negativas y límites dinámicos.

[Image of Monte Carlo integration method diagram showing points in a rectangle and under a curve]

### 2. Modelado de Activos (Geometric Brownian Motion)
Simulación de trayectorias de precios utilizando el modelo de Movimiento Browniano Geométrico (GBM).
* **Parámetros:** Cálculo de Drift ($\mu$) y Volatilidad ($\sigma$) basados en datos históricos reales.
* **Visualización:** Comparativa de datos reales (Adj Close) frente a modelos simulados para predicción de escenarios.

[Image of Geometric Brownian Motion simulation multiple paths graph]

### 3. Análisis Estadístico Financiero
* **Momentos Estadísticos:** Uso de `.skew()` para medir la asimetría de los rendimientos y evaluar el riesgo de cola.
* **Métricas de Desempeño:** Cálculo de ratios de volatilidad anualizada y márgenes netos.

---

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 3.x
* **Librerías:**
    * `numpy`: Generación de números aleatorios y álgebra lineal.
    * `pandas`: Manipulación de series de tiempo y estructuras de datos.
    * `matplotlib`: Visualización de datos y gráficos de simulación.
    * `scipy`: Integración numérica avanzada.

---

## 📊 Gestión Estratégica (Balanced Scorecard)
Ejemplo de implementación de KPIs integrados en las 4 perspectivas del BSC:
1. **Financiera:** Rendimiento sobre el capital (ROE).
2. **Clientes:** Cuota de mercado y satisfacción.
3. **Procesos:** Eficiencia operativa y tiempos de ciclo.
4. **Aprendizaje:** Capacitación técnica y retención de talento.

[Image of Balanced Scorecard strategy map showing cause and effect links]

---

##
