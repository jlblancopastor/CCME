# CCME
This project aims to generate the code for the analysis of genetic diversity loss in alpine ecosistems due to climate change


Part 1 
Import GPS and genetic datasets with appropriate format

Part 2
Download CHELSEA rasters for current time and future periods
Clipping 
Regionalization of Climate Change projections

Part 3
Run SDMs with R package "dismo"
Generate threshold layers of suitable distribution at 5 years period

Part 4
Compute population Expected heterozigosity (Hs) and haplotype diversity (Hd)
Interpolate Hs to whole suitable distribution at 5 years period (sensu Espíndola et al. 2014)
Calculate mean Hs per cell at 5 years period

Part 5
Compute ancestry coefficients at 5 years period (sensu Fay et al. 2012)
Calculate index of intra-specific turnover at 5 years period (sensu Fay et al. 2012). Consider only populations not predicted to be extinct

Part 6
Plot results of Part 4 and Part 5



