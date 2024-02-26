# **Teledetection Lab Scripts**

Welcome to the enchanted forest of data and satellites – our Teledetection Lab Scripts repository! 🌍✨ Nestled in the heart of the Amazon at CiteForestal-Maynas, Peru, this digital grove is where technology meets Mother Nature in a quest for sustainable forestry. Inside, you'll discover a treasure trove of scripts and notebooks, each conjured to automate, enchant, and enhance our workflows with a sprinkle of earth observation and remote sensing magic.

## **Overview**

Dive into a world where Python scripts and Jupyter Notebooks weave spells to streamline our lab’s quests. Each creation serves a unique purpose, fueling our efficiency and effectiveness in the realm of teledetection. Here's a sneak peek of the mystical manuscripts you'll encounter:

### **1. tallando_verification.ipynb**

A wizard’s tool for monitoring timber extraction with the precision of an eagle's eye. By channeling the power of latitude and longitude from a CSV file, this spell reveals time-shifting NDVI values across polygons, unmasking timber extraction secrets.

Value Contribution:

- **Guardians of the Forest:** Bolsters our arsenal against illegal timber harvesting, with swift, cost-effective permit verification.

- **Sages of Policy and Consulting:** Empowers us to shape the future with legislative recommendations and consulting services, spreading our influence far and wide.

### **2. analisis_salud_bosque_ejemplo.ipynb**

From data preparation spells to interactive map incantations, this journey through satellite imagery reveals the heartbeat of our forests, culminating in wisdom for timber harvest policies and conservation strategies.

#### Analysis Process

The process includes the following steps:

1. **Data Preparation**: Loading and processing Landsat satellite images to obtain vegetation indices.
2. **Temporal Analysis**: Comparing images to detect changes in vegetation cover between two time periods.
3. **Interactive Visualization**: Using `geemap` to create interactive maps that allow for the exploration of changes in NDVI and EVI.
4. **Change Detection**: Applying masks to highlight areas with significant changes in vegetation.
5. **Statistical Analysis**: Evaluating the relationship between NDVI and EVI and its statistical significance.
6. **Policy Recommendations**: Based on the results, recommendations are provided for issuing timber harvest permits and related policies.

Value Contribution

The results of this analysis are essential for:

- **Environmental Custodians:**: Elevates our monitoring rituals for the guardianship of forest treasures.
- **Consulting Oracles:**  Bestows data-driven insights upon those who shape our lands and laws.

Usage:
- Adjust the visualization and analysis parameters according to the specific needs of the project. This is meant to serve at a starting point and example about how to analyzes different satellite information to make data-backed decisions regarding specific land parcels.

### **3. censo_visualizacion.ipynb**

  A newly discovered grimoire that delves into the censo_aprovechamiento.csv, unveiling the lore of trees assessed for harvest in 2022. Through enchanting comparisons and descriptive statistics, it chronicles the strengths and stories of each species within our forested realm.

#### Data Artifacts:

- **aprovechable_stats.csv & non_aprovechable_stats.csv:** The scrolls of knowledge, detailing the descriptive stats of our forest's bounty by species.
- **df (the cleaned dataframe):** The purified essence of our data, ready for analysis and insight.

## **Usage**

To embark on this quest, ensure your satchel is packed with the necessary dependencies. Each script is a starting point for your own adventures, adaptable to the mysteries of your project.

- imazacoord_NOppi.csv: The legend of IMAZA, a venerable expanse of mixed-forest, unfolds through this dataset. With gratitude to the stewards of IMAZA, this script taps into the ancient wisdom of our ecosystem for the betterment of our collective future.

## **Support and Feedback**
If you encounter any issues, have suggestions for improvements, or would like to collaborate on further developments, please don't hesitate to reach out. Your feedback is invaluable in refining these scripts and driving innovation in our teledetection lab.

Let's continue pushing the boundaries of earth observation and remote sensing together! 🌍✨ Go hug a tree....🌴🌿🌱🌳 
