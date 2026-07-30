Chesapeake_Benthic_Phenology

# Quantitative Spatial Modeling of Scyphozoan Dynamics: Chesapeake Bay Baseline Triptych

## Overview
This repository contains the finalized geospatial assets and multi-criteria habitat maps evaluating population anomalies of *Chrysaora chesapeakei* (sea nettles) within the Chesapeake Bay estuarine system.

By utilizing Inverse Distance Weighting (IDW) continuous interpolation surfaces and map algebra via the QGIS Raster Calculator, this project isolates the precise abiotic switches controlling localized abundance fluctuations against a 10-year historic baseline.

## Repository Contents: The Seasonal Triptych
This repository serves as a standalone visual portfolio restricted exclusively to the primary spatial layers. Full manuscript text, automated R data-cleaning pipelines, and predictive machine learning regression scripts are reserved for upcoming publication.

* **Base Map (Historical Normal):** Formatted using a 10-year April historical average to establish the control baseline, mapping the regions where benthic river nurseries typically satisfy optimal salinity parameters.
* **Scarcity Map (2018 Anomaly):** Features a boolean mask layer evaluating `salinity < 10` to visually isolate the geographic footprint of the 2018 spring hydrologic bottleneck. This layer maps the exact lower river coordinates where extreme freshwater discharge forced benthic polyps into permanent podocyst dormancy, triggering a total summer population crash.
* **Surge Map (2021 Anomaly):** Features a corresponding thermal boolean mask layer to isolate the exact environmental boundaries where a mild winter sea surface temperature anomaly bypassed standard polyp stasis to trigger accelerated, premature strobilation and a massive summer medusae population explosion.

## Methods Summary
* **Geospatial Platform:** QGIS
* **Interpolation Engine:** Inverse Distance Weighting (IDW) continuous surfaces
* **Logical Expressions:** Dual-scenario binary boolean raster masking.

## Citation and Open Science Archive
This repository is permanently archived with Zenodo to ensure reproducibility and data transparency in estuarine ecology.

**DOI:** *10.5281/zenodo.2170993*

---
**Author:** Dawn Grogg
*Jetersville, VA, USA*
