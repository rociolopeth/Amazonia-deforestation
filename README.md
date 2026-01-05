# Amazonia-deforestation
Deforestation dynamics in Indigenous Territories of the Brazilian Amazon

### A remote sensing analysis of vegetation loss and moisture changes in Cachoeira Seca (Pará, Brazil)

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

This project focuses on the **Cachoeira Seca Indigenous Territory**, located in the state of **Pará, Brazil**. Cachoeira Seca became one of the most emblematic examples of deforestation within Indigenous lands during the 2016–2017 period, experiencing extensive forest clearing and conversion to pasture.

The territory provides a compelling case study to explore:
- How land-cover change unfolds within Indigenous territories,
- How forest loss is spatially organized,
- And how deforestation alters environmental conditions beyond simple land-cover replacement.

---

## Objectives

The main objective of this project is to **visualize and analyze vegetation loss and its environmental effects** in Cachoeira Seca using remote sensing data.

Specifically, this project aims to:
- Assess changes in land-cover composition over time,
- Quantify the expansion of pasture areas at the expense of Amazon rainforest,
- Examine how these land-cover changes affect vegetation moisture patterns.

---

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




