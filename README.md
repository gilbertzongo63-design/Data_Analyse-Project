# Data_Analyse-Project
Data-Analyse-project
 # Analysis of Average Farm Size by Country (1960–2000)

## Project Overview
This project presents an exploratory data analysis of **average farm size (in hectares)** across multiple countries over time.  
The objective is to understand long-term structural changes in agriculture, identify disparities between countries, and highlight trends such as farm consolidation or fragmentation.

# How has the average farm size evolved across different countries between 1960 and 2000?

This question is addressed through:
- Descriptive statistics
- Cross-country comparisons
- Temporal trend analysis
- Analytical indicators (variance and growth rate)

  ## Project Structure
-average-farm-size.csv # Dataset
-farm_size_analysis.ipynb,analysis, visualization)
- presentation.pptx # Project presentation (results & interpretation)
- README.md # Project documentation

  # Dataset Description
- **Source**: Our World in Data / World Bank  
- **Variables**:
  - `Entity`: Country or region
  - `Code`: ISO country code
  - `Year`: Observation year
  - `average_farm_size_ha`: Average farm size (hectares)

The dataset covers **over 100 countries** with observations between **1960 and 2000**.

# Data Cleaning
The following steps were applied:
- Verification of data types
- Removal of missing values (notably in country codes)
- Elimination of duplicate records
- Validation of non-negative farm size values

# Notable findings:
- Strong disparity between countries
- Extremely large average farm sizes in countries such as **Australia, Argentina, and Canada**
- Small and fragmented farm structures in parts of **Africa and Asia**

Analytical Indicators
Two custom indicators were created:

### Annual Variance
Measures the dispersion of average farm sizes across countries for each year, highlighting increasing global inequality in farm structures.

### Relative Growth Rate
Compares each country’s farm size to its own 1960 baseline, allowing:
- Identification of consolidation trends
- Detection of long-term decline or stagnation

# Visualizations
The notebook includes:
- Kernel Density Estimation (KDE) of years
- Pie chart of observation distribution by year
- Bar chart comparing the **Top 10 countries** by average farm size

These visualizations help translate numerical results into clear insights.

# Key Insights
- Average farm size varies **significantly** across countries
- Three dominant patterns emerge:
  - **Continuous growth** (mechanization and policy-driven consolidation)
  - **Stagnation** (geographical or institutional constraints)
  - **Fragmentation** (population pressure, inheritance systems)

These trends reflect the strong influence of **agricultural policy, land tenure systems, and socio-economic factors**.

# Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook/vscode
- Microsoft PowerPoint

 # Project Team
1. ZONGO Gilbert
2. ZONGO Viviane
3. COMPAORE Faozia Arielle Carine Ziabala
4. KONDOMBO Ibrahim
   
**Reviewers**: Miss Otema & Miss Blebo

# References
- Our World in Data  
- World Bank  

# Status
Project completed – exploratory analysis and visualization finalized.
