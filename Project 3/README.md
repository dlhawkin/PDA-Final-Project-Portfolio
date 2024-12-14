# Constrained Budget Simulation Model Project

Cluster randomized trials are randomized controlled trials where individuals are randomly assigned into groups called clusters. This paper presents a collaborative effort with Dr. Zhijin Wu from the Biostatistics Department at Brown University to address a fundamental challenge in experimental design: how to allocate resources optimally under budget constraints to maximize the precision of treatment effect estimation.We will consider a cluster randomized trial in which we will assign observations to either the control or treatment group and our goal is to estimate the treatment effect on an outcome variable Y.

The focus of this study is to design a simulation study to investigate optimal experimental design strategies for cluster randomized trials under budget constraints. The aims for this project consists of: designing a simulation study using the ADEMP framework from class to evaluate potential study designs, explore relationships between the underlying data generation mechanism parameters and the relative costs c_2 /c_1 and how these impact the optimal study design,extending my simulation study to the setting in which Y follows a Poisson distribution with mean \μi\ and explore how this impacts the results.

In conclusion, the simulation model study effectively demonstrated the intricate trade-offs inherent in optimizing study design under budgetary constraints while balancing statistical performance measures such as variance, cost-efficiency, and intra-class correlation coefficients (ICC).

# Dependencies

The R version and poackages used in this project are indicated below: R version 4.2.3 (2023-03-15)

magick_2.8.5 ggwordcloud_0.6.2 reshape2_1.4.4 corrplot_0.94 mice_3.16.0 gt_0.11.1 gtsummary_2.0.2 visdat_0.6.0
naniar_1.1.0 GGally_2.2.1 knitr_1.46 kableExtra_1.4.0 MASS_7.3-58.2 lubridate_1.9.3 forcats_1.0.0 stringr_1.5.1 ,
dplyr_1.1.4 purrr_1.0.2 tidyr_1.3.1 tibble_3.2.1,
ggplot2_3.5.1 tidyverse_2.0.0  readr_2.1.5
