ToDo:
- Note, Translate, Make Everything Look Nice in Both Scripts
- Once Over Again For Errors
SALUD> New Notebook:
- Expand and explore health anaylsis- keep deriving actionable insights.
- Develop Example IFM Methodology- and Baselines on Imaza
- Verify in the field and conduct "further analysis" as necessary
- Sample Verra Project
- Ready submit to Prociencia

# **Teledetection Lab Scripts**

Welcome to my Teledetection Lab Scripts repository! Here, you'll find a collection of scripts and notebooks aimed at automating and enhancing workflows within our teledetection lab at CiteForestal-Maynas in the heart of the Amazon in Peru. These scripts have been developed to address specific needs and challenges, particularly in the realm of earth observation and remote sensing analysis for sustainable forestry.

## **Overview**

This repository houses various Python scripts and Jupyter Notebooks designed to streamline processes and add value to our lab's operations. Each script serves a unique purpose and contributes to the overall efficiency and effectiveness of our workflows. Below is a brief overview of the main scripts included:

### **1. tallando_verification.ipynb**

This notebook is a powerful tool for monitoring timber extraction activities. By inputting a CSV file containing latitude and longitude coordinates of vertices, users can define specific time frames (before and after) to compare NDVI (Normalized Difference Vegetation Index) values. The script generates a detailed report of polygons, allowing users to determine if timber extraction has occurred in a given area.

Value Contribution:

- **Enhanced Monitoring and Enforcement:** In regions where monitoring and enforcement agencies lack efficient methods for verifying timber transport permits, this script fills a crucial gap. It enables quick, easy, and cost-effective verification of permits, thereby deterring illegal timber harvesting practices. 

- **Consulting Services:** As a government agency involved in research and technology development, we will leverage this script to propose legislative recommendations aimed at standardizing permit verification practices. Subsequently, we can offer consulting services to other agencies, further extending our impact and revenue streams.

### **2. analisis_salud_bosque_ejemplo.ipynb**

This notebook includes various analyses and visualizations that help understand changes in forest health and coverage in the Loreto region, Peru. Using vegetation indices such as NDVI and EVI, we can detect areas of vegetation gain or loss over time, which is crucial for making sustainable decisions in forest management.

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

- **Environmental Monitoring**: Improving monitoring practices for the sustainable management of forest resources.
- **Consulting and Policy Recommendations**: Informing government agencies and conservation organizations with data-driven recommendations.

Usage:
- Adjust the visualization and analysis parameters according to the specific needs of the project. This is meant to serve at a starting point and example about how to analyzes different satellite information to make data-backed decisions regarding specific land parcels.

## **Usage**
To utilize these scripts effectively, ensure you have the necessary dependencies installed and follow the instructions provided within each notebook. Feel free to explore, modify, and adapt the scripts to suit specific project requirements.

- imazacoord_NOppi.csv: data about one of the largest and oldest privately-own plots of mixed-forest for timber harvest here in Loreto, Peru. The owners of IMAZA have graciously allowed CiteForestal-Maynas to conduct extensive research to gain a deeper understanding of our ecosystem and forest health in relation to timber harvest. The scripts in here use the IMAZA csv for reference. All data contained is available through public land registries and private personal identifiers have been removed.

## **Support and Feedback**
If you encounter any issues, have suggestions for improvements, or would like to collaborate on further developments, please don't hesitate to reach out. Your feedback is invaluable in refining these scripts and driving innovation in our teledetection lab.

Let's continue pushing the boundaries of earth observation and remote sensing together! 🌍✨ Go hug a tree....🌴🌿🌱🌳 
