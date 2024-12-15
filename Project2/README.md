# Assessing Baseline Variables as Potentail Moderators of the Behavioral Treatment Effects on End of Treatment (EOT)
Mental health disorders are among the most common health conditions associated with tobacco dependence. Studies have shown that smokers 
with depression find smoking more pleasurable and are more dependent on nicotine, leading to more severe withdrawal symptoms than smokers 
without major depressive disorder (MDD).  "Smokers with depression are more likely to smoke heavily, perceive smoking as more pleasureable than
other traditionally rewarding activities, show greater dependence and experience more severe withdrawal than smokers without MDD 
(Hitsman, Papandonatos, et al., 1711). Dr. George Papandonatos, from Brown University’s highly regarded Biostatistics Department,
investigated smoking cessation outcomes in adults diagnosed with MDD.

In this analysis, I began with an exploratory data analysis that examines the realtionships between various categorical
and continous variables with association to abstinence. After finding the covariates that has some interesting associations to abstinence, we will
implement an multiple imputation to create several datasets (5) to account for uncertainities around missing data. Following impuation mechanisms,
we will implement logistic and lasso regression modeling to find significant baseline predictors of abstinence.

In conclusion, I discovered that  **NMR**, **readiness to quit**, **race/ethnicity**, **menthol use**, **cigarettes per day**, **income level**, and **age** are critical moderators that influence the effectiveness of treatments and the likelihood of abstinence.



# Key Files
`Project2_Final_Report`.pdf: Finalize report that consist of the exploratory data analysis and  assessING baseline variables as potential 
moderators of the behavioral treatment effects on end-of-treatment (EOT) abstinence `Final_Report_Project2.Rmd` : Rmd file that contains code, 
analysis and interpretations.

![adjustedtable2](https://github.com/user-attachments/assets/cfcd32e1-1b52-482c-b619-faecc09bbd88)

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
