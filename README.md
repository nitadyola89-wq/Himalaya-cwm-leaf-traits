# Data for: Precipitation and soil nutrients drive the variation in tree leaf traits across elevation in the Himalayas

**Authors:** Nita Dyola, Sugam Aryal, Shalik Ram Sigdel, Eryuan Liang, and Sergio Rossi
**Corresponding author:** Nita Dyola; ndyola@etu.uqac.ca; nitadyola89@gmail.com
**Journal:** Journal of Vegetation Science
**Dataset DOI:** https://doi.org/10.5281/zenodo.23441994
**Repository:** https://github.com/nitadyola89-wq/Himalaya-cwm-leaf-traits (archived on Zenodo)
**License:** Creative Commons Attribution 4.0 International (CC BY 4.0; see LICENSE)

## Description

This dataset contains the elevation-belt-level data used in all statistical analyses of the article (ANOVA, PCA, Spearman correlations, simple linear regressions, and generalized linear models). It includes community-weighted mean (CWM) leaf traits of tree communities and the climatic and soil variables for 42 elevation belts along an elevational gradient (80–4200 m asl) in the Kangchenjunga Landscape, eastern Nepal Himalayas.

Trees with a diameter at breast height ≥ 5 cm were surveyed in three 20 m × 20 m plots in each 100-m elevation belt (126 plots in total). CWMs were calculated for each plot by weighting species mean trait values by the relative abundance (proportion of stems) of each sampled species, and plot-level CWMs and environmental variables were then averaged within each belt. Full methods are described in the article.

## File

`cwm_leaf_traits_environment_elevation_belts.csv`: 42 rows (one per elevation belt) × 12 columns; comma-separated; decimal point "."

## Variables

| Column | Description | Unit |
|---|---|---|
| `elevation_belt_midpoint_m` | Midpoint of the 100-m elevation belt (e.g., 50 = belt 0–100 m) | m asl |
| `bioclimatic_zone` | Bioclimatic zone (codes below) | – |
| `mean_annual_temperature_C` | Mean annual temperature (CHELSA; Karger et al., 2017) | °C |
| `total_annual_precipitation_mm` | Total annual precipitation (CHELSA; Karger et al., 2017) | mm yr⁻¹ |
| `soil_total_N_percent` | Soil total nitrogen (Digital Soil Map of Nepal; NARC, 2024) | % |
| `soil_available_P_kg_ha` | Soil available phosphorus (Digital Soil Map of Nepal; NARC, 2024) | kg ha⁻¹ |
| `cwm_LDMC_mg_g` | CWM leaf dry matter content | mg g⁻¹ |
| `cwm_SLA_mm2_mg` | CWM specific leaf area | mm² mg⁻¹ |
| `cwm_leaf_thickness_mm` | CWM leaf thickness | mm |
| `cwm_leaf_C_mg_g` | CWM leaf carbon concentration | mg g⁻¹ |
| `cwm_leaf_N_mg_g` | CWM leaf nitrogen concentration | mg g⁻¹ |
| `cwm_leaf_P_mg_g` | CWM leaf phosphorus concentration | mg g⁻¹ |

**Bioclimatic zone codes:** Tro = tropical (80–1000 m asl); Stro = sub-tropical (1000–2000 m); Wtem = warm-temperate (2000–2500 m); Ctem = cool-temperate (2500–3000 m); Salp = sub-alpine (3000–4000 m); Alp = alpine (4000–4200 m).

## Notes

1. **Elevation** is the midpoint of each 100-m belt. The lowest belt (midpoint 50 m) contains plots located at about 80 m asl.
2. **Identical trait values in the two lowest belts (50 and 150 m):** all plots in these belts contained a single sampled tree species, so their CWMs equal that species' mean trait values.
3. **Leaf thickness at the 3550 m belt:** leaf thickness was not measured in two of the three plots of this belt; these plots were recorded as 0 in the plot-level data, so the belt value (0.046 mm) is the mean of 0, 0 and 0.138 mm. Users may wish to treat this value as incomplete.
4. Climatic and soil values are derived from gridded databases; plots within a belt often share the same values.
5. There are no missing values in the file.

## Sharing and access

Licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). You may share and adapt the data for any purpose, provided that appropriate credit is given by citing the article and this dataset:

Dyola, N., Aryal, S., Sigdel, S.R., Liang, E. & Rossi, S. (2026) Data for: Precipitation and soil nutrients drive the variation in tree leaf traits across elevation in the Himalayas. Zenodo. https://doi.org/10.5281/zenodo.23441994

## Code

[Optional: link to analysis code, if shared]
