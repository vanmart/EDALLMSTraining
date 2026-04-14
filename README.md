LLM-Efficiency-Hunter-2026
🎯 Visión General
En un mercado de IA saturado, el rendimiento bruto ya no es la única métrica que importa. LLM-Efficiency-Hunter-2026 es un sistema de análisis predictivo diseñado para identificar "joyas ocultas": modelos de lenguaje que ofrecen un rendimiento excepcional a una fracción del costo de los modelos "Premium".

Utilizando el dataset de Marzo 2026, este proyecto aplica Machine Learning para automatizar la toma de decisiones tecnológicas (FinOps) en el despliegue de IA.

🚀 Características Principales
Ingeniería de Variables de Valor: Implementación de métricas de eficiencia como Intelligence per Dollar y Speed per Dollar.

Análisis de Sinergia: Identificación estadística de bloques de alta correlación entre benchmarks críticos (MMLU Pro, GPQA, SciCode).

Clasificador Inteligente: Modelo basado en LightGBM con un 94.5% de precisión para etiquetar modelos como Recomendado o No Recomendado.

Visualización Avanzada: EDA profundo con mapas de calor de correlación y análisis de costos en escala logarítmica.

🛠️ Stack Técnico
Lenguaje: Python 3.10+

Modelado: LightGBM, Scikit-learn (XGBoost, Random Forest para benchmarking).

Procesamiento: Pandas, NumPy.

Visualización: Seaborn, Matplotlib.

Entorno: Jupyter Notebook / Google Colab.

📊 Hallazgos Clave
Ineficiencia del Mercado: Se demostró que el costo operativo no tiene una correlación lineal con el rendimiento técnico. Pagar más no siempre garantiza mejores resultados.

Bloques de Inteligencia: Existe una consistencia sólida (0.70 - 0.88) entre las capacidades de razonamiento lógico y la ejecución de código.

Optimización FinOps: El modelo permite reducir sobrecostos al filtrar modelos con baja relación calidad-precio.

📂 Estructura del Proyecto
data/: Datasets originales y procesados.

notebooks/: EDA, Ingeniería de variables y entrenamiento del modelo.

src/: Scripts de procesamiento y utilidades.

reports/: Gráficas resultantes y matrices de confusión.

👥 Integrantes
Ivan Martinez

Saúl Carrillo Quintero

Nota: Este proyecto fue desarrollado como parte del Bootcamp de Inteligencia Artificial - Nivel Exploratorio (Talento TECH / Universidad de Antioquia & Universidad de Caldas).

¿Cómo usarlo?
Clona el repo: git clone https://github.com/tu-usuario/LLM-Efficiency-Hunter-2026.git

Instala dependencias: pip install -r requirements.txt

Ejecuta el notebook principal para ver el proceso de clasificación.