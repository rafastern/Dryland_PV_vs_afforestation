[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Code for "Photovoltaic fields largely outperform afforestation efficiency in global climate-change mitigation strategies"

This repository contains the code related to the article ["Photovoltaic fields largely outperform afforestation efficiency in global climate-change mitigation strategies"](https://academic.oup.com/pnasnexus/article-lookup/doi/10.1093/pnasnexus/pgad352) (see citation below). The repository is organised as follows:

  1) **code**: Folder containing the main code of the article
  2) **data**: Place all data from the data repositories listed below in this folder to run the code
  3) **code/Supplementary Information**: Code related to tables and figures in the supplementary information

## Abstract of the article

> Suppression of carbon emissions through photovoltaic (PV) energy and carbon sequestration through afforestation provide complementary climate-change mitigation (CCM) strategies. However, a quantification of the “break-even time” (BET) required to offset the warming impacts of the reduced surface reflectivity of incoming solar radiation (albedo effect) is needed, though seldom accounted for in CCM strategies. Here, we quantify the CCM potential of PV fields and afforestation, considering atmospheric carbon reductions, solar panels life cycle analysis (LCA), surface energy balance, and land area required across different climatic zones, with a focus on drylands, which offer the main remaining land area reserves for forestation aiming climate change mitigation. Results indicate a BET of PV fields of ~2.5 years, but >50× longer for dryland afforestation, even though the latter is more efficient at surface heat dissipation and local surface cooling. Furthermore, PV is ~100× more efficient in atmospheric carbon mitigation. While the relative efficiency of afforestation compared with PV fields significantly increases in more mesic climates, PV field BET is still ~20× faster than in afforestation, and land area required greatly exceeds availability for tree planting in a sufficient scale. Although this analysis focusing purely on the climatic radiative forcing perspective quantified an unambiguous advantage for the PV strategy over afforestation, both approaches must be combined and complementary, depending on climate zone, since forests provide crucial ecosystem, climate regulation and even social services.

## Data availability

The data underlying this analysis are freely available from the following sources:
  - Flux data for the sites in Israel: https://doi.org/10.34933/403d99aa-17e2-4f67-95a4-5de13681439c
  - GPPD database (v.1.1.0): http://datasets.wri.org/dataset/globalpowerplantdatabase
  - Fluxnet: https://fluxnet.org/ and
  - Euroflux: http://www.europe-fluxdata.eu/
 
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
  - Plotnine

  
## How to Cite

Rafael Stern; Muller, Jonathan D.; Rotenberg, Eyal; Amer, Madi; Segev, Lior and Yakir, Dan (2023). Photovoltaic fields largely outperform afforestation efficiency in global climate-change mitigation strategies. PNAS Nexus. DOI: [10.1093/pnasnexus/pgad352](https://academic.oup.com/pnasnexus/article-lookup/doi/10.1093/pnasnexus/pgad352)

## Copyright & License

© 2023 Rafael Stern & Jonathan D. Müller

This software is distributed under the GNU GPL version 3. The license file is provided in the repository. All modifications or copies must be made available openly under the same license. Contact the authors for requests on license changes.

