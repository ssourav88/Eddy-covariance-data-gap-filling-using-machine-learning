# Eddy Covariance Data Gap Filling

This project focuses on implementing and evaluating methods for **gap filling in Eddy Covariance (EC) datasets**, typically used in micrometeorology and ecosystem carbon exchange studies. The aim is to provide robust and reproducible tools to preprocess EC time series by filling gaps caused by sensor malfunction, data filtering, and quality control.

## 🌍 Project Overview

Eddy Covariance towers provide continuous measurements of ecosystem fluxes like:
- CO₂ exchange (NEE, GPP, Reco)
- Latent heat flux (LE)
- Sensible heat flux (H)

However, the raw data often contain **gaps** due to:
- Power outages
- Sensor calibration/drift
- Low-quality data flags
- Environmental filtering (e.g., friction velocity thresholds)

This project implements automated **gap-filling techniques** following community standards (e.g., FLUXNET, REddyProc), including:
- Machine learning models - Random Forest Regressor, Hist Gradient Boosting Regressor, Support Vector Regressor, Linear Regression
