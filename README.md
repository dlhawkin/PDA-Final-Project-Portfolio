# Impact of Environmental Conditions on Marathon Runners’ Performance Based on Gender and Age

In recent years, marathon participation and performance have seen a marked increase, prompting a deeper exploration into the factors influencing outcomes in these endurance events. In collaboration with Dr. Brett Romano Ely and Dr. Matthew Ely from the Department of Health Sciences at Providence College, this study aims to assess the impact of environmental condition like temperature, humidity, solar radiation, and wind speed on marathon performance in both male and female marathon runners. This project focused on three aims: examining the effects of increasing age on marathon performance in men and women,exploring the impacts of environmental conditions on marathon performance, and whether the impact differs across age and gender, and finally identifying (WBGT, Flag conditions, temperature, etc) that have the largest impact on marathon performance. I hypothesize that increasing environmental temperatures and unfavorable weather conditions will have a negative impact on marathon performance.

In this exploratory data analysis, I conducted a detailed analysis that included line plots to examine trends in runtimes (performance) across various ages, highlighting the relationship between male and female marathon performances.Along with assessing these trends, I employed spline regression to investigate the relationship between runtimes and other key variables, providing insights into potential predictors of performance. Furthermore, correlation plots will be used to assess the strength and direction of relationships among variables, offering a comprehensive understanding of their interdependencies.

In conclusion I discovered that Boston Marathon runners exhibited the strongest overall performance. The most optimal race times were achieved by participants aged 26–35. Additionally, the analysis revealed that flag conditions, specifically Red and Yellow, had the most significant impact on marathon runners' performance.



# Key Files
`Final_Report_Project2.pdf`: Finalize report that consist of the exploratory data analysis and  assessING baseline variables as potential moderators of the behavioral treatment effects on end-of-treatment (EOT) abstinence `Final_Report_Project2.Rmd` : Rmd file that contains code, analysis and interpretations.

# Assessing Baseline Variables as Potentail Moderators of the Behavioral Treatment Effects on End of Treatment (EOT)
Mental health disorders are among the most common health conditions associated with tobacco dependence. Studies have shown that smokers with depression find smoking more pleasurable and are more dependent on nicotine, leading to more severe withdrawal symptoms than smokers without major depressive disorder (MDD).  "Smokers with depression are more likely to smoke heavily, perceive smoking as more pleasureable than other traditionally rewarding activities, show greater dependence and experience more severe withdrawal than smokers without MDD (Hitsman, Papandonatos, et al., 1711). Dr. George Papandonatos, from Brown University’s highly regarded Biostatistics Department, investigated smoking cessation outcomes in adults diagnosed with MDD.

In this analysis, I began with an exploratory data analysis that examines the realtionships between various categorical and continous variables with association to abstinence. After finding the covariates that has some interesting associations to abstinence, we will implement an multiple imputation to create several datasets (5) to account for uncertainities around missing data. Following impuation mechanisms, we will implement logistic and lasso regression modeling to find significant baseline predictors of abstinence.

In conclusion, I discovered that ... 



# Key Files
`Final_Report_Project2.pdf`: Finalize report that consist of the exploratory data analysis and  assessING baseline variables as potential moderators of the behavioral treatment effects on end-of-treatment (EOT) abstinence `Final_Report_Project2.Rmd` : Rmd file that contains code, analysis and interpretations.

# Constrained Budget Simulation Model Project

Cluster randomized trials are randomized controlled trials where individuals are randomly assigned into groups called clusters. This paper presents a collaborative effort with Dr. Zhijin Wu from the Biostatistics Department at Brown University to address a fundamental challenge in experimental design: how to allocate resources optimally under budget constraints to maximize the precision of treatment effect estimation.We will consider a cluster randomized trial in which we will assign observations to either the control or treatment group and our goal is to estimate the treatment effect on an outcome variable Y.

The focus of this study is to design a simulation study to investigate optimal experimental design strategies for cluster randomized trials under budget constraints. The aims for this project consists of: designing a simulation study using the ADEMP framework from class to evaluate potential study designs, explore relationships between the underlying data generation mechanism parameters and the relative costs  (\( c_2 /c_1 \)) and how these impact the optimal study design,extending my simulation study to the setting in which Y follows a Poisson distribution with mean $\mu_i$\ and explore how this impacts the results. 











  # Dependencies
The R version and poackages used in this project are indicated below: `R version 4.2.3 (2023-03-15)`

`magick_2.8.5`
`ggwordcloud_0.6.2`
`reshape2_1.4.4`
`corrplot_0.94`
`mice_3.16.0`
`gt_0.11.1`
`gtsummary_2.0.2` 
`visdat_0.6.0`   
`naniar_1.1.0`
`GGally_2.2.1`
`knitr_1.46`
`kableExtra_1.4.0`
`MASS_7.3-58.2`
`lubridate_1.9.3`
`forcats_1.0.0` 
`stringr_1.5.1` ,   
`dplyr_1.1.4`
`purrr_1.0.2`
`tidyr_1.3.1` 
`tibble_3.2.1`,  
`ggplot2_3.5.1` 
`tidyverse_2.0.0 ` 
`readr_2.1.5`  

