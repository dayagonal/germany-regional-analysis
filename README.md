# germany-regional-analysis

# Germany Regional Economic Analysis

##  Overview
This project analyzes the relationship between regional GDP, R&D expenditures, and education across Germany (2017–2019).
The goal is to explore spatial patterns and test whether economic development, innovation, and education are correlated across regions.

## Objectives
- Analyze spatial distribution of GDP and R&D
- Examine relationship between education and economic indicators
- Identify regional disparities
- Apply spatial econometrics (Moran’s I)


## Data
Data sources:
- Eurostat
- German official statistics (Destatis)
- GIS shapefiles (Germany regions)

Variables used:
- GDP (million EUR)
- R&D expenditure (million EUR)
- Student rate (per population)
- Regional geometry (spatial data)


## Tools & Technologies
- R
- Packages:
  - `dplyr`, `tidyr`
  - `sf` (spatial data)
  - `tmap` (visualization)
  - `spdep` (spatial analysis)
  - `mice` (data imputation)

---

##  Key Analysis

### 1. Spatial Visualization
- Choropleth maps for GDP and R&D
- Bubble maps for student rates
- Animated maps across years

### 2. Relationship Analysis
- GDP vs R&D
- R&D vs Education
- GDP vs Education

### 3. Spatial Econometrics
- Global Moran’s I → strong positive spatial autocorrelation (~0.9)
- Local Moran’s I → identification of clusters (hotspots & cold spots)

## 🔍 Key Findings
- Strong geographical clustering of economic activity
- Southern regions (Bavaria, Baden-Württemberg) dominate in GDP and R&D
- Eastern regions lag behind economically
- Education does not always correlate with wealthier regions
- Less developed regions tend to have higher student rates
