# Predicting-Nitrogen-Contamination

Nitrogen contamination in the Gulf of Mexico is a major factor in the annual summer hypoxic zone, which greatly impacts the fishing economy and ecosystem while additionally causing serious health ramifications for people who consume the water. 

# Cause

This contamination is caused by the Mississippi-Atchafalaya River Basin (MARB) pollutants feeding into the Gulf of Mexico. 

# Purpose

By predicting nitrogen contamination trends and major contributors to this contamination, efforts to mitigate nitrogen contamination can be centered on major contributors, making the process more efficient. 

# Process
I compiled my dataset using streamflow data from the 9 major sub-basins of MARB (USGS), data about the concentration of nitrogen contamination in the Gulf of Mexico (USGS) and precipitation data from the Midwest (Illinois Cli-MATE tool).  I fitted the dataset to three machine learning prediction models: Ridge regression, Lasso regression and ElasticNet regression and compared them using R2 score and MSE. 

# Analysis
The results indicate that the Grafton, Grand Chain and Thebes river basins are the most contributive, which are congregated at points of the Illinois, Mississippi and Ohio rivers. Targeting nitrogen contamination reduction efforts to these basins is the most efficient method to reduce nitrogen contamination in the Gulf of Mexico.
