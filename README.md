# Network-Fluid Gravitational Shear: Probing Dark Compact Objects via OGLE-2024 Microlensing

## Overview
This repository houses the theoretical framework, automated extraction pipelines, and empirical datasets for auditing gravitational lensing anomalies through the **Unyielding Network Stage** and fluid boundary shear models.

## Theoretical Framework
* **The MOND Acceleration Scale ($a_0$):** Modeled as the critical shear-stress threshold of the background network grid ($\sigma_{\text{shear}} / \Sigma_{\text{baryon}}$).
* **Gravitational Anomalies:** Conceptualized as local energy code excitations within a static, unyielding fluid matrix rather than mutable space-time stretching.

## Empirical Methodology & Pipeline
* **Data Source:** OGLE-IV Early Warning System (EWS) survey stream.
* **Difference Image Analysis (DIA):** Leverages flux-difference photometry to isolate transient events in crowded Galactic bulge fields.
* **Filtering Criteria:** 
  * High Einstein crossing times ($\tau > 50\text{--}100\text{ days}$).
  * Absolute optical invisibility / high blend fractions ($f_{\text{bl}} \approx 1.0$).

## Top Candidates Identified
* `2024-BLG-0174` ($\tau \approx 1433.4\text{ days}, f_{\text{bl}} = 1.0$)
* `2024-BLG-0022` ($\tau \approx 312.1\text{ days}, f_{\text{bl}} = 1.0$)

## Repository Structure
* `/scripts/ogle_fetcher.py` - Automated Python tool for querying and downloading raw `.dat` photometry.
* `/data/` - Filtered high-tau, dark-blend datasets.

