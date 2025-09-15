# Spatio-Temporal-Analysis-of-street-level-crime-in-City-of-London

The folder raw dataset consists of all 24 indivdual files of each month from May 2023 to April 2025 downloaded from the datasource
The folder cleaned dataset consists of 3 files
    - combined_city_of_london_crime.csv: this file contains data of all 24 files combined together
    - cleaned_city_of_london_crime_for_temporal_analysis.csv: this file contains cleaned dataset for performing temporal analyis
    - cleaned_city_of_london_crime_for_spatial_analysis.csv: this file contains cleaned dataset for performing spatial analyis

This repo consists of 5 jupyter notebook files
    - data_qc_temporal_analysis.ipynb: this notebook contains python code used to club all 24 files together in single file and python code used for data cleaning implementation for temporal analysis
    - data_qc_spatial_analysis.ipynb: this notebook contains python code used for data cleaning implementation for spatial analysis
    - RQ1.ipynb: this notebook contains python code used for performing data analysis and generating data visuals for Research Question 1
    - RQ2_RQ4.ipynb: this notebook contains python code used for performing data analysis and generating spatial maps for Research Question 2 and 4
    - RQ3.ipynb: this notebook contains python code used for performing data analysis and generating data visuals and spatial maps for Research Question 3
