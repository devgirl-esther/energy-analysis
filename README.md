UK Energy Transition Analysis (2009–2026)
Overview

Analysed over 303,000 half-hourly electricity generation records to understand how the UK electricity system evolved between 2009 and 2026. The project explores changes in the generation mix, progress towards decarbonisation, and uses machine learning to predict electricity carbon intensity.

Data source: [https://www.neso.energy/data-portal/historic-generation-mix]
To reproduce the analysis:

1. Download the dataset from the source above.
2. Save it as:

data/df_fuel_ckan.csv



Key Questions
How has the UK generation mix changed since 2009?
What impact has renewable growth had on carbon intensity?
Which generation sources drive carbon emissions?
Can carbon intensity be accurately predicted from generation data?
Dataset
Period: Jan 2009 – Apr 2026
Frequency: 30-minute intervals
Records: 303,389
Features: 34
Key Findings
Coal generation declined from a major electricity source to near-zero levels.
Wind became the UK's largest generation source by 2026.
Renewable generation overtook fossil generation.
Carbon intensity fell by approximately 70% over the study period.
Coal was identified as the strongest driver of carbon intensity.
Machine Learning Results
Model	MAE	R²
Baseline	192.32	-9.54
Random Forest	10.55	0.952
Gradient Boosting	13.72	0.920

Best Model: Random Forest Regressor

Technologies
Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-Learn

Skills Demonstrated: Data Cleaning • Exploratory Data Analysis • Energy Analytics • Machine Learning • Model Evaluation • Data Visualisation