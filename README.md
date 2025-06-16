# Clustering African Countries by Healthcare Access and Outcomes

## Project Overview  
This project analyzes healthcare disparities across African countries using data driven techniques. By integrating six datasets including population, GDP, access to doctors, causes of mortality, and mortality by age group it applies Exploratory Data Analysis (EDA), Principal Component Analysis (PCA), and KMeans Clustering to group countries with similar healthcare characteristics and identify outliers with critical health concerns.

---

## Objectives  
- Group African countries by healthcare and socio economic patterns  
- Identify outlier nations with extreme conditions  
- Reveal gaps in healthcare access across the continent  
- Support targeted interventions and data driven global health strategies  

---

## Use Cases  
- Guide targeted health interventions in vulnerable regions  
- Inform strategic investments and resource allocation  
- Address healthcare inequalities at scale  
- Enable AI driven and data-informed public health solutions   

---

## Tools and Libraries  
- **Python**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `plotly`, `kneed`  
- **Power BI**: for interactive, country-level and cluster-level dashboards  

---

## Methodology  

1. **Data Collection**  
   Merged 6 datasets on GDP, population, mortality, causes of death, mortality by age group, and access to medical professionals.

2. **Data Cleaning and Preparation**  
   Addressed missing values and inconsistencies, standardized country names, converted types, and scaled data for analysis.

3. **Exploratory Data Analysis (EDA)**  
   Explored patterns and anomalies in mortality, population, GDP, and healthcare coverage.

4. **Dimensionality Reduction**  
   Applied PCA, preserving 96.1% of total variance, to simplify the dataset and enhance clustering accuracy.

5. **Clustering**  
   Performed KMeans Clustering to categorize countries into four distinct clusters based on healthcare indicators.

6. **Evaluation**  
   - Silhouette Score: `0.82` (strong internal consistency)  
   - Inter/Intra-cluster Distance Ratio: `~9.7` (clear separation and well-defined clusters)

7. **Visualization**  
   Created plots and cluster maps using Python libraries and exported results to Power BI for interactive, country by country and cluster by cluster exploration.

---

## Insights and Recommendations  

1. **Notable Spike in Mortality in 1994**  
   A significant spike in mortality occurred in 1994, with a peak between 2003 and 2005 reaching 9.3 million deaths. Rwanda and Burundi stood out as outliers during this period, linking the mortality trend to regional crises.

2. **Population and Mortality Correlation**  
   There’s a general correlation between population size and mortality, but exceptions exist. Uganda, Tanzania, Rwanda, and Sudan demonstrate lower than expected mortality, suggesting the role of health infrastructure and living conditions beyond population alone.

3. **Cardiovascular Diseases as the Leading Cause of Death**  
   With over 37 million deaths, cardiovascular diseases are the top mortality driver. Unlike more volatile causes, these deaths show a steady upward trend highlighting the need for sustained focus on heart health.

4. **High Mortality Among Children Under 5**  
   Children under five account for about 41% of total deaths (116 million). This calls for urgent attention to maternal care, early childhood interventions, and health system support for infants.

5. **Access to Medical Professionals Reflects System-Level Investment**  
   While countries like Nigeria and Egypt have more doctors due to population size, others like Tunisia and Algeria achieve high doctor access through deliberate, strategic investment, demonstrating that healthcare quality can be improved independent of population.

---

## 🔗 Power BI Dashboard  
An interactive Power BI dashboard allows for exploration of country level and cluster based healthcare trends across Africa.  
👉 [View Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTIwYmZhNGUtMzFmNy00ZWVlLWJmOGItNGVlMDMxYzNlZDc2IiwidCI6IjEwMWQ0NjY0LTg3OGEtNGUzYi04N2Y3LTc4ZjA4Yjc2MjhiYSJ9)

---

## 📘 View Jupyter Notebook  
Explore the complete analysis and interactive Plotly visuals via NBViewer:  
👉 [Open in NBViewer](https://nbviewer.org/github/aminahol/africa-mortality-clustering/blob/5d7270aa61af88f29cd658840c5645721af1936f/Mortality%20Rates%20In%20Africa-revised.ipynb)

---

## Let’s Connect  
If you're interested in healthcare data, public sector analytics, or AI for global health, feel free to connect.

---

### 🔖 Tags  
#healthcareanalytics #datascience #unsupervisedlearning #publichealth #powerbi #africadata #kmeans #pca #healthdata

