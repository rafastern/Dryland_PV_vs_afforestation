[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Dryland PV vs. afforestation

Code and data related to our article on dryland PV and afforestation (see citation below). The repository is organised as follows:

  - Codes: Contains subfolders for 4 main parts, with calculations of:
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
  - glob
  - re
  
## Code organisation

The code is organised in 4 subcategories:

  - **01_UAV_radiation_calibration:** Calibration scripts for UAV data based on ground-based data from Mobile Lab EC measurements
  - **02_Sensible_heat_and_resistance:** Calculations of sensible heat flux and aerodynamic resistance
  - **03_Break_even_time:** Break-even time calculation for the Ketura and Yatir sites
  - **04_Additional_climate_zones:** Calculation of break-even time for 2 additional climate zones. Note that the Euroflux and Fluxnet data is not provided in the current repository as it is available from those networks. Please request it from the site maintainers there.
  
## Data availability

Data is provided for the Ketura and Yatir sites. For the two additional climate zones, the Euroflux (http://www.europe-fluxdata.eu/) and Fluxnet (https://fluxnet.org/) data is not provided in the current repository as it is available from those networks. Please request it from the site maintainers there.

## How to Cite

Rafael Stern; Muller, Jonathan D.; Amer, Madi; Segev, Lior; Rotenberg, Eyal and Yakir, Dan (2022). Dryland photovoltaic fields outperform afforestation in climate mitigation. DOI: XXX/XXXXXXX

## License

This software and data is distributed under the GNU GPL version 3. The license file is provided in the repository. Note that all modifications must be made available openly under the same license.

