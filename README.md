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
