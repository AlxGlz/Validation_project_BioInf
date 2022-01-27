# Validation_project_BioInf

External validation of the prognostic score for monitoring of COVID-19 patients condition

The project is aimed at validation of the prognostic score developed in the First Pavlov State Medical University [1]. 
In the validating study we used clinical data from the Republican National Scientific and Practical Center for Emergency Medicine, Chisinau, Republic of Moldova (data is not available). 
The validating set comprised the information about 3162 ICU patients hospitalized with respiratory diagnosis and positive PCR test for COVID-19 between March 2020 and November 2021.
We confirmed that the prognostic scale demonstrates predictive capabilities and can be used for outcome prediction.

The project script is written in R (Main_script.Rmd) and includes data parsing, multistep filtering, prognostic score calculation, estimation of sensitivity and specificity of the prognostic score, calculation of the odds of death, score-based lethal outcome prediction. Primary data for analysis are available on request. The results of the script execution are given in the file "Main_script.html".

Dependencies (R-packages): tidyr, lubridate, ggplot2, stringr, zoo, flextable, dplyr, readxl.

The original article can be found in the "data/original/" directory.

1. Bakin, E., et al. (2021). A Novel Approach for COVID-19 Patient Condition Tracking: From Instant Prediction to Regular Monitoring. Frontiers in Medicine 8, 2482. 10.3389/fmed.2021.744652
