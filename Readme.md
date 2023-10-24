[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Dryland PV vs. afforestation

Code and data related to the article on dryland PV and afforestation (see citation below). The repository is organised as follows:

  - Code: Contains subfolders for 4 main parts, with calculations of:
    1) Calibration of UAV radiation measurements to the Eddy Covariance system mast
	2) Sensible heat flux and aerodynamic resistance
    3) The break-even time (BET) for our forest and PV sites
	4) The temperate and tropical zones' BET
  - Data: Related to subfolders 2-4 of code above

## Code dependencies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

The following python packages are required to run the code

  - Pandas
  - Numpy
  - Scipy
  - Gmpy2

Some scripts use, additionally:
  - Plotnine
  - glob
  - re
  
## Code organisation

The code is organised in 4 subcategories:

  - ***01_UAV_radiation_calibration:*** Calibration scripts for UAV data based on ground-based data from Mobile Lab EC measurements
  - ***02_Sensible_heat_and_resistance:*** Calculations of sensible heat flux and aerodynamic resistance
  - ***03_Break_even_time:*** Break-even time calculation for the Ketura and Yatir sites
  - ***04_Additional_climate_zones:*** Calculation of break-even time for 2 additional climate zones
  
## Data availability

The data underlying this analysis are freely available from the following sources:
  - Flux data for the sites in Israel: https://doi.org/10.34933/403d99aa-17e2-4f67-95a4-5de13681439c
  - GPPD database (v.1.1.0): http://datasets.wri.org/dataset/globalpowerplantdatabase
  - Fluxnet: https://fluxnet.org/ and
  - Euroflux: http://www.europe-fluxdata.eu/

## How to Cite

Rafael Stern; Muller, Jonathan D.; Rotenberg, Eyal; Amer, Madi; Segev, Lior and Yakir, Dan (2023). Photovoltaic fields largely outperform afforestation efficiency in global climate-change mitigation strategies. PNAS Nexus. DOI: XXX/XXXXXXX

## Copyright & License

© 2023 Rafael Stern & Jonathan D. Müller

This software is distributed under the GNU GPL version 3. The license file is provided in the repository. All modifications or copies must be made available openly under the same license. Please contact the authors for requests on license changes.

