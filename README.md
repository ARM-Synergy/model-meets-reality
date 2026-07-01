<img src="/notebooks/images/arm_logo.png" width=500 alt="ARM Logo"></img>

# Model Meets Reality (MMR): A Cross-Comparison of DP-SCREAM and WRF Against ARM Observations

[![DOI](https://zenodo.org/badge/1246820879.svg)](https://doi.org/10.5281/zenodo.21113436)

![arms-race](/notebooks/images/model-meets-reality.jpg)

## [2026 ARM Summer School Project](https://arm-development.github.io/arm-summer-school-2026/)

* **Science question(s)**: The upstart DP-SCREAM model is ready to rumble with the long-in-the-tooth WRF model–which one compares better to observations? How do differences in resolution and physics impact cloud representation?
* **Project Scope**: We have prepared DP-SCREAM simulations to pair with WRF sims from LASSO-ShCu for three cases. ARM has dozens of measurements that can be used to examine the representativeness of these simulations. Cross compare the two models and put their differences in context with the observations. 
* **Datasets**:
- DP-SCREAM (dx=3 km) and WRF (dx=100 m) for 9-Jul-2018, 17-May-2019, & 29-Sep-2019
- sgplassohighfreqobsC1.c1: cloud-base height at 5 stations, LWP, LCL, cloud fraction from KAZR-ARSCL
- sgpcldfraccogs10mC1.c1: cloud fraction from photogrammetry–bye bye bugs!
- sgplassodiagobsmod8C1.m1: various prepared obs like CF from TSI, boundary layer T and Q

## Authors

- Pappu Paul  
-- ORCID: 0000-0003-0060-849X
- Luojie (Roger) Dong 
-- ORCID: 0009-0007-7911-6012
- Emmanuel Kipchirchir 
-- ORID: 0009-0008-9351-1446
- Luke Heim 
-- ORCID: 0009-0005-1674-8106
- Sining Niu  
-- ORCID: 0000-0002-3389-0076
- yijia Sun 
-- ORCID: 0000-0003-1539-4877
- Maggie Powell 
-- ORCID: 0009-0008-8826-1948
- William Gustafson 
-- ORCiD: 0000-0001-9927-1393
- Lucia Liu  
-- ORCID: 0000-0002-6958-2868 
- Jing Li 
-- ORCID: 0009-0001-2473-0468

## Structure
- Compiled analysis of the group is within main_analysis.ipynb and a preliminary ML analysis for feature importance using Random Forest is in ML_analysis.ipynb
- Scratch notebooks with exploration are within notebooks.
- All analysis was done using the base environment on ARM Juypter Hub.

## Final Presentation

- [Link to Final Presentation](./model-meets-reality-cross-comparison-dpscream-wrf.pdf)
