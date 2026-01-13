# Amazonia Deforestation in Indigenous Lands
Visualizing and analyzing two decades of forest loss, pasture expansion, and hydration changes in Cachoeira Seca, Pará, Brazil.


## 📘 Project Notebooks

This repository contains two complementary Jupyter notebooks that address different stages of the analysis workflow.

### 📊 Visualization & Interpretation Notebook (Didactic)

The notebook **`deforestation_amazonas_visualization.ipynb`** is a didactic and presentation-oriented notebook designed to facilitate the interpretation of results. It includes:

- Clear visualizations (bar charts and maps) summarizing soil hydration changes  
- Tables reporting surface area values (km²) for each NDMI hydration category  
- Interactive links to satellite imagery for spatial exploration  
- Step-by-step explanations of the methodology and results  

This notebook is intended for readers interested in understanding the environmental trends and outcomes of the analysis without diving into the full technical development.

[![Open Visualization Notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1f5JrXyjftGlHf7C4LhFBPmA_5IGh359z)

---

### 🛠️ Original Development Notebook

For users interested in the full analytical workflow, data processing steps, and methodological development, the original notebook used to build and test the analysis pipeline is also available. This notebook contains the complete codebase for data ingestion, NDMI computation, pixel classification, and spatial quantification.

[![Open Development Notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DQDdrp6nLvDcxv2eqUbMBE-MIJAFWT3z)


## Background

Deforestation in the Amazon rainforest remains one of the most critical environmental challenges worldwide, with profound implications for biodiversity, climate regulation, and Indigenous livelihoods. While deforestation is often associated with agricultural expansion, cattle ranching, and infrastructure development, its spatial distribution is highly uneven.

Numerous studies and monitoring initiatives have shown that **Indigenous Territories (Terras Indígenas)** play a crucial role in limiting deforestation. These territories frequently act as **barriers against forest loss**, maintaining significantly higher levels of preserved forest cover compared to surrounding non-protected areas. The protection offered by Indigenous land governance has therefore been recognized as a key component of Amazon conservation strategies.

However, despite their protective role, Indigenous Territories are **not immune to deforestation pressures**.

---

## Deforestation in Indigenous Territories

Between **2016 and 2017**, several Indigenous Territories in Brazil experienced **episodes of intense and rapid deforestation**, marking one of the most critical periods of forest loss within legally protected Indigenous lands. These events were particularly pronounced in parts of the eastern Amazon, including the state of **Pará**, where land grabbing, illegal cattle ranching, and weak enforcement converged.

According to reports compiled by Indigenous monitoring initiatives and environmental organizations, this period represents a turning point in which deforestation penetrated areas that had historically functioned as strongholds of forest conservation.

---

## Study Area: Cachoeira Seca Indigenous Territory

This project focuses on the **Cachoeira Seca Indigenous Territory**, located in the state of **Pará, Brazil**. The territory covers approximately 7056.82 km², providing a tangible sense of the scale of land management and deforestation dynamics. Cachoeira Seca became one of the most emblematic examples of deforestation within Indigenous lands during the 2016–2017 period, experiencing extensive forest clearing and conversion to pasture.

The territory provides a compelling case study to explore:
- How land-cover change unfolds within Indigenous territories,
- How forest loss is spatially organized,
- And how deforestation alters environmental conditions beyond simple land-cover replacement.

---

## Objectives

The main objective of this project is to **analyze vegetation loss and its environmental effects** in the selected Indigenous territory using remote sensing data.

Specifically, this project aims to:
- **Visualize changes in land-cover type** in the selected Indigenous territory over the last 25 years, identifying trends in forest loss and land conversion.
- **Assess how these land-cover changes affect environmental characteristics**, by monitoring vegetation moisture patterns using NDMI over different years, with a focus on the 2016–2017 period, when literature reports significant forest disturbance.
- **Quantify these changes through parametrization**, classifying vegetation moisture levels into categories to provide a quantitative understanding of environmental impacts.


## Data Sources

### MAPBIOMAS Land Cover Dataset
To analyze land-cover dynamics, this project uses the **MAPBIOMAS** dataset, which provides annual land-cover classifications for Brazil based on satellite imagery.

Using this dataset, the evolution of different land-cover classes was assessed, with particular attention to:
- Dense Amazon rainforest,
- Pasture and grazing areas.

The analysis reveals a progressive **expansion of pasturelands** coinciding with a **reduction in native forest cover**, especially during and after the 2016–2017 period.

---

### Vegetation Moisture Index (NDMI)

To explore the environmental consequences of land-cover change, the **Normalized Difference Moisture Index (NDMI)** was computed from satellite imagery.

NDMI provides information about **vegetation water content** and is commonly used to assess plant hydration and moisture stress.

The analysis shows that:
- Pasture areas retain some degree of moisture, as expected for vegetated surfaces,
- However, these areas are associated with the emergence of **drier zones in their surroundings**,
- Suggesting that forest-to-pasture conversion alters local moisture dynamics and potentially increases landscape-level dryness.

This highlights that, although pasture is not a completely dry surface, it does not reproduce the hydrological and microclimatic functions of intact rainforest.

---

## Methodological Overview

This project combines:
- Land-cover classification data (MAPBIOMAS),
- Spectral index analysis (NDMI),
- Spatial visualization techniques,

to provide an integrated view of deforestation dynamics and their environmental impact within an Indigenous Territory.

The full analytical workflow, including data processing, visualization, and figure generation, is documented in the accompanying Jupyter notebook.

---


## Conclusions

This project provides a landscape-scale analysis of environmental change in the **Cachoeira Seca Indigenous Territory** over the last two decades, integrating multi-source remote sensing data and spatial analysis.

Key findings include:

- **Progressive decline of very hydrated areas:** Between 2008 and 2025, *very hydrated* surfaces decreased from **6,634.76 km²** to **4,098.68 km²**, a loss of over **2,500 km²**.  
- **Expansion of intermediate and dry zones:** *Intermediate* hydration expanded from **243.74 km²** to **2,789.41 km²**, while *dry* areas increased from **46.01 km²** to **184.58 km²**, reflecting a significant shift in soil moisture conditions.  
- **Temporal focus on 2016–2017:** Changes observed around this period align with literature reports of intensified deforestation and forest disturbance in the territory.  
- **Landscape-scale environmental implications:** The redistribution of hydration states suggests a transition from a largely intact, moisture-rich forest to increasingly fragmented and moderately to poorly hydrated landscapes.  
- **Consistency with broader regional trends:** Observed patterns correlate with deforestation, land-use conversion to pasture, and climatic stress affecting the Amazon region.  
- **Link to land-use change drivers:** By analyzing **MapBiomas land-cover data**, we see that the expansion of pasture areas has been ongoing since 2000, progressively occupying more territory, degrading surrounding areas, and ultimately driving the observed changes in vegetation hydration. This highlights the conversion to pasture as the **primary origin of environmental change** in the Cachoeira seca indigenous land territory.

These results underscore the importance of **conservation strategies and sustainable land management** to preserve forest integrity and soil moisture in Indigenous territories.

---

## Why this matters

Understanding deforestation **within** Indigenous Territories is critical for:
- Evaluating the limits of legal protection alone,
- Identifying periods and mechanisms of vulnerability,
- Supporting Indigenous-led monitoring and conservation strategies.

By focusing on Cachoeira Seca, this project illustrates how remote sensing can be used to document not only forest loss, but also its broader ecological consequences.

---

## Data Sources and References

- MAPBIOMAS Land Cover Dataset – Souza, C. M. et al. (2020). Reconstructing Three Decades of Land Use and Land Cover Changes in Brazilian Biomes with Landsat Archive and Earth Engine. *Remote Sensing*, 12(17), 2735. https://doi.org/10.3390/rs12172735
- Terra Indígena Database. https://terrasindigenas.org.br/. Accessed 4 January 2026.
- - Satellite imagery:
  - **Copernicus Sentinel-2**: `COPERNICUS/S2_SR_HARMONIZED`
  - **Landsat 8**: `LANDSAT/LC08/C02/T1_L2`




