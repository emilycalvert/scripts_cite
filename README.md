# Scripts de Teledetección

¡Bienvenido a mi repositorio de Scripts de Teledetección! Aquí encontrarás un tesoro de scripts y cuadernos destinados a automatizar y mejorar los flujos de trabajo dentro de nuestro laboratorio de teledetección en CiteForestal-Maynas, en el corazón de la Amazonía peruana. Desarrollados para abordar necesidades y desafíos específicos, estas herramientas están a la vanguardia de la observación terrestre y el análisis de teledetección para la silvicultura sostenible. 🌍💚

## Visión General

Este repositorio es un hogar acogedor para varios scripts de Python y cuadernos Jupyter diseñados para agilizar procesos y esparcir un poco de magia en las operaciones de nuestro laboratorio. Cada script es como una poción única, contribuyendo a la eficiencia y efectividad general de nuestros flujos de trabajo. Aquí tienes un vistazo al mundo mágico en su interior:

1. **tallando_verification.ipynb**
   Un hechizo poderoso para monitorear las actividades de extracción de madera. Genera informes detallados a partir de polígonos definidos por entradas CSV, ofreciendo una vista de pájaro de la extracción de madera a lo largo del tiempo. 🌲🔍

   - **Contribución de Valor:** Mejora el monitoreo y la aplicación de la ley, disuade la tala ilegal y allana el camino para servicios de consultoría y recomendaciones legislativas. 💼🌳

2. **analisis_salud_bosque_ejemplo.ipynb**
   Sumérgete en el corazón del bosque con análisis y visualizaciones que revelan los cambios pulsantes en su salud y cobertura. Utilizando NDVI y EVI, este cuaderno es tu guía a través de la selva verde de Loreto, Perú. 🍃💡

   ### Proceso de Análisis
   El proceso incluye los siguientes pasos:
   - **Preparación de Datos:** Cargar y procesar imágenes satelitales Landsat para obtener índices de vegetación.
   - **Análisis Temporal:** Comparar imágenes para detectar cambios en la cobertura vegetal entre dos períodos de tiempo.
   - **Visualización Interactiva:** Usar geemap para crear mapas interactivos que permitan la exploración de cambios en NDVI y EVI.
   - **Detección de Cambios:** Aplicar máscaras para resaltar áreas con cambios significativos en la vegetación.
   - **Análisis Estadístico:** Evaluar la relación entre NDVI y EVI y su significancia estadística.
   - **Recomendaciones de Políticas:** Basado en los resultados, se proporcionan recomendaciones para la emisión de permisos de tala y políticas relacionadas.

   - **Contribución de Valor:** Los resultados de este análisis son esenciales para el monitoreo ambiental y proporcionar consultoría y recomendaciones de políticas basadas en datos. 📊📈

3. **censo_visualizacion.ipynb**
   Este cuaderno da vida al `censo_aprovechamiento.csv`, mostrando los árboles evaluados para la cosecha en 2022. Sumérgete en un mundo de comparaciones e ideas, desentrañando la historia de nuestros bosques a través de los datos. 🌳📊

   - **aprovechable_stats.csv & non_aprovechable_stats.csv:** Estos archivos ofrecen estadísticas descriptivas por especie, mientras que `df.csv` representa la esencia depurada y pulida de nuestros datos, listos para el análisis. 📚🔍

## Uso

Embárcate en esta aventura con las dependencias necesarias a tu lado y sigue las instrucciones místicas proporcionadas en cada cuaderno. Siéntete libre de explorar, modificar y adaptar los hechizos para ajustarlos a las necesidades únicas de tu proyecto. Con las siguientes ideas y datos puedes realizar tu propio análisis.

- **imazacoord_NOppi.csv:** Estos son los vértices para una de las parcelas de bosque mixto privado más antiguas de Loreto.
- **censo_extra.csv:** Estos son datos adicionales del censo que se pueden usar con el script y para un análisis e ideas adicionales.

## Flujos de Trabajo Amplios para la Gestión Forestal Sostenible

Nuestros scripts no son solo herramientas; son portales para demostrar y abogar por la gestión forestal sostenible. Al entrelazar datos del censo con análisis de salud, empoderamos a los tomadores de decisiones con una visión holística de nuestros ecosistemas. 🌱🛤

## Análisis Extendido Posible sobre la Salud:

1. **Temperatura de la superficie terrestre:** Siente el calor de la Tierra mientras exploramos las variaciones de la temperatura superficial. 🔥🌡
2. **Densidad del bosque:** Aventúrate en el corazón denso del bosque, entendiendo su profundo lenguaje no dicho. 🌲🌲
3. **Cambio de biomasa:** Sé testigo de la transformación de la biomasa, una historia de crecimiento y descomposición. 🔄🍂
4. **Degradación:** Descubre las cicatrices de la degradación, trazando un curso para la recuperación y resiliencia. 🌪🌿
5. **Cambio de carbono:** Sigue el aliento del bosque, monitoreando el flujo y reflujo del cambio de carbono. 💨🌍

### Cómo Integrar el Análisis de Salud con el Censo:

1. **Análisis de Correlación Entre Parámetros de los Árboles e Índices de Teledetección:** Explora la relación entre las meticulosas mediciones en tierra de los parámetros de los árboles (como la calidad del tronco y las especies) y los altos índices de teledetección (NDVI y EVI) de las imágenes Sentinel. Desentraña cómo estos índices reflejan las condiciones y características reales del bosque. ¡Es una forma divertida e informativa de ver si ciertas especies o calidades de tronco resaltan como correlatos fuertes con las firmas saludables y exuberantes que capturamos desde el espacio! 🕵️‍♂️
2. **Análisis Temporal para la Detección de Cambios:** Amplía tu análisis más allá de fechas estáticas para abrazar la historia dinámica del bosque. Al comparar los valores de NDVI y EVI a lo largo de varios puntos en el tiempo, crearás un diario viviente de la salud del bosque, siendo testigo de su danza a través de las estaciones, su resiliencia contra la cosecha y sus susurros de cambio a lo largo de los años. Esta narrativa continua nos ayuda a rastrear el pulso del vigor de la vegetación, identificando tendencias y cuentos de recuperación o declive.🚀
3. **Análisis Espacial para Identificar Zonas de Impacto de la Cosecha:** Usa la magia del SIG para trazar áreas cosechadas y superponerlas sobre el cambiante tapiz de valores NDVI y EVI. Busca patrones que revelen el toque de la cosecha en la tela del bosque. Identificar zonas amortiguadoras más saludables o áreas donde la huella ecológica de la cosecha es un susurro, no un rugido, puede dirigir nuestras energías de conservación y manos de cosecha sabiamente.🗺️
4. **Modelos de Aprendizaje Automático para Perspectivas Predictivas:** Desarrolla modelos que miren hacia el mañana, prediciendo la salud del bosque y destacando áreas sedientas de atención o maduras para la restauración. Incorpora los ricos detalles de la vulnerabilidad de las especies, cuentos de calidad del tronco e índices de teledetección históricos para afilar tu previsión. Esta visión proactiva puede revolucionar la gestión forestal, guiando la emisión de permisos con una mano sabia y nutriendo áreas antes de que sufran en silencio. 🤖
5. **Desarrollo de un Índice de Sostenibilidad:** Desata tu creatividad para forjar un Índice de Sostenibilidad 🎨. Entrelaza los hilos de datos del censo de árboles, ritmos NDVI/EVI, narrativas de cosecha y perspectivas predictivas para esbozar un gráfico integral de la salud del bosque. Este índice, adaptado al latido único de tu bosque y sus sueños de administración, ilumina el camino para los tomadores de decisiones, destacando áreas vibrantes, regiones en recuperación y zonas anhelando un descanso del baile de la cosecha.

Al abrazar estos análisis extendidos, no solo estamos procesando números; estamos contando la historia del bosque, pintando un futuro donde la conservación y la innovación giran en armonía. 🌲💃 Cada punto de datos es un trazo de pincel en esta obra maestra de la silvicultura sostenible, narrando una historia de equilibrio, crecimiento y resiliencia. Mantengamos nuestros bosques exuberantes, nuestras metodologías afiladas y nuestros corazones abiertos a las infinitas posibilidades de la ciencia de la conservación. ¡Aquí estamos para hacer que cada árbol cuente, cada análisis importe y cada decisión sea un paso hacia un mañana más verde! 🌍✌️

Esta suite de análisis enriquecida está diseñada para guiar y dirigir la emisión de permisos y la planificación/gestión de la tierra, asegurando que cada decisión esté enraizada en la sostenibilidad y armonía con la naturaleza. 🌏💖

## Soporte y Retroalimentación

Si encuentras algún problema, tienes sugerencias para mejoras o te gustaría colaborar en desarrollos futuros, no dudes en contactarnos. Tu retroalimentación es invaluable en el refinamiento de estos scripts y en impulsar la innovación en nuestro laboratorio de teledetección.

¡Sigamos empujando los límites de la observación de la Tierra y la teledetección juntos! 🌍✨ Ve a abrazar un árbol....🌴🌿🌱🌳

# **Teledetection Lab Scripts**

Welcome to my Teledetection Lab Scripts repository! Here, you'll find a treasure trove of scripts and notebooks aimed at automating and enhancing workflows within our teledetection lab at CiteForestal-Maynas, nestled in the heart of the Amazon in Peru. Developed to address specific needs and challenges, these tools are at the forefront of earth observation and remote sensing analysis for sustainable forestry. 🌍💚

## **Overview**

This repository is a cozy home for various Python scripts and Jupyter Notebooks designed to streamline processes and sprinkle a little magic on our lab's operations. Each script is like a unique potion, contributing to the overall efficiency and effectiveness of our workflows. Here's a peek into the magical world inside:

### **1. tallando_verification.ipynb**

A powerful spell for monitoring timber extraction activities. It generates detailed reports from polygons defined by CSV inputs, offering a bird's-eye view of timber extraction over time. 🌲🔍

- **Value Contribution:** Enhances monitoring and enforcement, deters illegal harvesting, and paves the way for consulting services and legislative recommendations. 💼🌳

### **2. analisis_salud_bosque_ejemplo.ipynb**

Dive into the heart of the forest with analyses and visualizations that reveal the pulsing changes in its health and coverage. Utilizing NDVI and EVI, this notebook is your guide through the green wilderness of Loreto, Peru. 🍃💡

#### Analysis Process

The process includes the following steps:

1. _Data Preparation:_ Loading and processing Landsat satellite images to obtain vegetation indices.
2. _Temporal Analysis:_ Comparing images to detect changes in vegetation cover between two time periods.
3. _Interactive Visualization:_ Using `geemap` to create interactive maps that allow for the exploration of changes in NDVI and EVI.
4. _Change Detection:_ Applying masks to highlight areas with significant changes in vegetation.
5. _Statistical Analysis:_ Evaluating the relationship between NDVI and EVI and its statistical significance.
6. _Policy Recommendations:_ Based on the results, recommendations are provided for issuing timber harvest permits and related policies.

- **Value Contribution:** The results of this analysis are essential for environmental monitoring and providing data-driven consulting and policy recommendations. 📊📈

Usage:
- Adjust the visualization and analysis parameters according to the specific needs of the project. This is meant to serve at a starting point and example about how to analyzes different satellite information to make data-backed decisions regarding specific land parcels.

### **3. censo_visualizacion.ipynb**

This notebook brings the censo_aprovechamiento.csv to life, showcasing the evaluated trees for harvest in 2022. Dive into a world of comparisons and insights, unraveling the story of our forests through data. 🌳📊

- **aprovechable_stats.csv & non_aprovechable_stats.csv:** These files offer descriptive stats per species, while **df.csv** represents the cleansed and polished essence of our data, ready for analysis. 📚🔍

## **Usage**

Embark on this adventure with the necessary dependencies at your side and follow the mystical instructions provided within each notebook. Feel free to explore, modify, and adapt the spells to fit your unique project needs. With the following ideas and data you can conduct your own analysis. 

- **imazacoord_NOppi.csv:** These are the vertices for one of the oldest, privately owned mixed forest plots in Loreto.
- **censo_extra.csv:** This is addiitional census data that can me used with the script and for further analysis and insight.

## **Ample Workflows for Sustainable Forest Management**

Our scripts are not just tools; they are gateways to demonstrating and advocating for sustainable forest management. By weaving together census data with health analysis, we empower decision-makers with a holistic view of our ecosystems. 🌱🛤

### Possible Extended Analysis on Health:
- _Temperatura de la superficie terrestre:_ Feel the warmth of the Earth as we explore surface temperature variations. 🔥🌡
- _Densidad del bosque:_ Venture into the dense heart of the forest, understanding its deep, unspoken language. 🌲🌲
- _Cambio de biomasa:_ Witness the transformation of biomass, a tale of growth and decay. 🔄🍂
- _Degradación:_ Uncover the scars of degradation, plotting a course for recovery and resilience. 🌪🌿
- _Cambio de carbono:_ Track the breath of the forest, monitoring the ebb and flow of carbon change. 💨🌍

### How to Integrate Health Analysis with the Census:
- _1. Correlation Analysis Between Tree Parameters and Remote Sensing Indices:_ Explore the relationship between the meticulous ground-based measurements of tree parameters (like trunk quality and species) and the high-flying remote sensing indices (NDVI and EVI) from Sentinel images. Unravel how these indices mirror the actual conditions and characteristics of the forest. It's a fun and insightful way to see if certain species or trunk qualities shine through as strong correlates with the lush, healthy signatures we capture from space! 🕵️‍♂️
-  _2. Temporal Analysis for Change Detection:_ Expand your analysis beyond static dates to embrace the forest's dynamic story. By comparing NDVI and EVI values over multiple time points, you'll craft a living diary of the forest's health, witnessing its dance through seasons, its resilience against harvesting, and its whispers of change over years. This ongoing narrative helps us trace the pulse of vegetation vigor, spotting trends and tales of recovery or decline.🚀
-  _3. Spatial Analysis for Identifying Harvesting Impact Zones:_ Use GIS magic to chart out harvested areas and drape them over the changing tapestry of NDVI and EVI values. Search for patterns that reveal the touch of harvesting on the forest's fabric. Identifying healthier buffer zones or areas where the ecological footprint of harvesting is a whisper, not a roar, can direct our conservation energies and harvesting hands wisely.🗺️
-  _4. Machine Learning Models for Predictive Insights:_ Develop models that peer into tomorrow, predicting forest health and spotlighting areas thirsting for attention or ripe for restoration. Fold in the rich details of species vulnerability, trunk quality tales, and historical remote sensing indices to sharpen your foresight. This proactive vision can revolutionize forest management, guiding permit issuance with a wise hand and nurturing areas before they silently suffer. 🤖
-  _5. Sustainability Index Development:_ Unleash your creativity to forge a Sustainability Index 🎨. Weave together the threads of tree census data, NDVI/EVI rhythms, harvesting narratives, and predictive insights to sketch a comprehensive health chart for the forest. This index, tailored to the unique heartbeat of your forest and its stewardship dreams, lights the way for decision-makers, spotlighting vibrant areas, recovering regions, and zones yearning for a rest from the harvest dance.

By embracing these extended analyses, we're not just crunching numbers; we're telling the forest's story, painting a future where conservation and innovation twirl in harmony. 🌲💃 Each data point is a brush stroke in this masterpiece of sustainable forestry, narrating a tale of balance, growth, and resilience. Let's keep our forests lush, our methodologies sharp, and our hearts open to the endless possibilities of conservation science. Here's to making every tree count, every analysis matter, and every decision a step towards a greener tomorrow! 🌍✌️

This enriched analysis suite is designed to guide and direct permit issuance and land planning/management, ensuring every decision is rooted in sustainability and harmony with nature. 🌏💖

## **Support and Feedback**
If you encounter any issues, have suggestions for improvements, or would like to collaborate on further developments, please don't hesitate to reach out. Your feedback is invaluable in refining these scripts and driving innovation in our teledetection lab.

Let's continue pushing the boundaries of earth observation and remote sensing together! 🌍✨ Go hug a tree....🌴🌿🌱🌳 
