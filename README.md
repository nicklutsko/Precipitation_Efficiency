# Lutsko and Cronin precipitation efficiency files

Respository for code used in analysis of Lutsko and Cronin (2018) JAMES article on precipitation efficiency.

Contains datafiles from the SAM simulations, 2 sample namelist files and 7 python notebooks used in the analysis.

The notebooks include:
  -precip_efficiency calculates the precip efficiency, sedimentation efficiency and re-evaporation efficiency for the small domain simulations and mock-Walker simulations. It plots Figures 1, 9 and 10 of the manuscript.

  -analyze_phases calculates the water paths shown in Figure 2, the profiles shown in Figure 3 and the cloud densities shown in Figure 6.

  -re-evaporation performs the analysis of the re-evaporation, shown in Figures 7 and 8.

  -subsidence_fraction plots the subsidence fractions shown in Figure 5.

  -calc_PDFs outlines how the PDFs in Figures 4 and 13 were calculated. Since the PDFs were estimated from a large number of 3D output files we have not provided the data to actually do the calculations. 

  -mock-Walker_analysis produces the mock Walker simulation Figures 11 and 12.

  -simple_model_cloud_density calculates cloud condensate mixing ratios for plumes starting at 900hPa with an environmental relative humidity of 80% and cloud-base temperature of 288K, 290K and 292K, and makes Figure A1.
