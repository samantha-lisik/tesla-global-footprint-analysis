**Tesla Global Footprint Analysis (2015–2025)
Deliveries, CO₂ Impact & Market Segmentation**

**Overview**

This project explores Tesla’s global presence using open-source data covering 2015–2025. The analysis examines:

- **Regional delivery trends**

- **Estimated CO₂ savings**

- **Market differences across regions**

- **Correlation and regression modeling**

- **Cluster-based segmentation of global markets**

- **Time-series performance over a 10-year period**

The results are curated into an interactive Tableau storyboard, highlighting the most meaningful insights for stakeholders.

View the full Tableau Storyboard [here](https://public.tableau.com/views/YourDashboard/Story).

The storyboard focuses on the final insights. All exploratory steps, intermediate models, and analyses are documented in the notebooks within this repository.

**Project Objectives**

- Understand Tesla’s global delivery growth and environmental impact

- Compare regional performance and sustainability outcomes

- Identify meaningful relationships (e.g., deliveries ↔ CO₂ savings)

- Segment markets using clustering

- Communicate insights in a clear, business-friendly Tableau narrative

**Repository Structure**
| Folder              | Description                                                                                                                                                                                                                                                  |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Data/**           | Contains datasets used in the project, including **Original Data/** (raw Kaggle dataset + GeoJSON) and **Prepared Data/** (cleaned, formatted data).                                                                                                         |
| **Notebooks/**      | Jupyter notebooks for each analysis stage:<br>• *01. Data Profile*<br>• *02. Exploring Relationships*<br>• *03. Geographic Visualizations*<br>• *04. Machine Learning - Regression*<br>• *05. Machine Learning - Clustering*<br>• *06. Time-Series Analysis* |
| **Visualizations/** | Exported charts and plots grouped by analysis type:<br>• *01. Exploring Relationships*<br>• *02. Geographic Visualizations*<br>• *03. Regression Analysis*<br>• *04. Machine Learning - Clustering*<br>• *05. Time-Series Analysis*                          |
| **Documents/**      |Project Brief                                                                                                                                                                        |



**Data Sources**
1. Tesla Global Deliveries Dataset (Primary)

- Dataset source: [Kaggle – Tesla Global Deliveries](https://www.kaggle.com/datasets/rehan497/tesla-global-deliveries-dataset-20152025)

- Author: Rehan Ahmed

- Includes: deliveries, production, price, CO₂ savings, battery capacity, charging infrastructure, region labels

2. Custom GeoJSON Regions File

- Created to map Tesla metrics by North America, Europe, and Asia

- Used for Tableau geospatial visualizations

3. Time-Series Preparation

- A cleaned dataset extracted for trend analysis of deliveries and sustainability impact

**Analysis Components**

✔ **Exploratory Data Analysis**

- Pair plots, correlation heatmap, scatterplots

- Early hypotheses formed based on relationships (e.g., deliveries ↔ CO₂ saved)

✔ **Geographic Analysis**

- Regions mapped via a custom GeoJSON

- Shows how Tesla’s environmental impact varies globally

✔ **Regression Modeling**

- Tested the predictive relationship between deliveries and CO₂ savings

- Found a strong positive linear relationship

✔ **Clustering**

- Segmenting regions based on multiple metrics (deliveries, CO₂, production)

- Confirmed that each region behaves uniquely

✔ **Time-Series Analysis**

- Yearly delivery patterns

- Insight into Tesla’s global expansion trajectory

**Key Insights**

- Deliveries and CO₂ savings are strongly correlated, confirming that Tesla’s growth directly scales environmental impact.

- Asia shows the highest delivery volumes, followed by Europe and North America.

- Clustering revealed three distinct regional profiles, highlighting different market characteristics.

- Tesla’s footprint is not uniform globally, and regions require individual strategies.

**Tools & Technologies**

- Python: pandas, seaborn, matplotlib, scikit-learn, statsmodels

- GeoPandas for geospatial processing

- Tableau Public for the final interactive presentation

- Jupyter Notebook for full workflow documentation
