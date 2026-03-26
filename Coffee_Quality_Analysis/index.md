# Global Coffee Quality Analysis — Mini Case Study

## Overview
This project analyzes global coffee quality scores from the Coffee Quality Institute to understand how roast level influences cupping evaluations and which countries consistently achieve high-quality results. Using exploratory analysis, regression, and clustering, the project identifies flavor-driven quality patterns and defines a three-tier segmentation system for coffee quality.

---

## Objective
This analysis explores:
- Which countries consistently produce high-scoring coffees  
- How roast levels influence sensory scores across regions  
- Which flavor attributes predict overall quality  
- How clustering reveals quality tiers and flavor grouping  

---

## Methods
- Data cleaning, normalization, and feature engineering  
- Linear regression to test flavor as a predictor of Total Cup Points  
- KMeans clustering (k = 3) to segment coffee quality tiers  
- Geospatial mapping of roast-level distributions  
- Tableau Storypoint dashboard for visual storytelling  

---

## Data Sources
- Coffee Quality Database (CQI)  
- Top Rated Coffee dataset  
- Coffee Production by Region (time series)  

---

## Exploratory Analysis
Initial exploration showed strong correlations between flavor, aroma, and Total Cup Points. Regression analysis confirmed flavor as a strong predictor of overall quality (R² = 0.56), especially in medium roast profiles. Acidity and aftertaste showed weaker relationships, informing downstream modeling choices.

Add visuals here:

```
![Correlation Heatmap](images/correlation_heatmap.png)
![Flavor vs Total Score](images/flavor_regression.png)
```

---

## Clustering Results
KMeans clustering (k = 3) using flavor and total score revealed three quality tiers:

- **Top Tier** – High flavor, aftertaste, and acidity; scores above ~87.5  
- **Mid Tier** – Moderate, balanced profiles  
- **Low Tier** – Lower aftertaste and acidity; often darker roasts  

These tiers aligned with cupping notes and informed sourcing recommendations and dashboard segmentation.

Add visual here:

```
![Clustering Results](images/coffee_clusters.png)
```

---

## Key Insights
- Flavor is the strongest predictor of overall coffee quality.  
- Medium roast profiles show the clearest flavor–quality relationship.  
- Three distinct quality tiers emerge from clustering.  
- Low-tier coffees often show bitterness or astringency tied to darker roasts.  

---

## Recommendations
- Analyze country-level tier distribution to guide sourcing strategies.  
- Test PCA and expanded clustering to refine tier definitions.  
- Finalize dashboard layout and annotations for stakeholder review.  

---

## Limitations
- Clustering used only flavor, aftertaste, and total score.  
- Other attributes were excluded from model inputs and used only for interpretation.  
- Sample sizes vary by country and roast level.  

---

## Project Links
- GitHub Repository  
- Tableau Storypoint Dashboard  
