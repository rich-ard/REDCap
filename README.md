# ETL from REDCap projects to R

I use this code to:

- load a data dictionary and raw data csv extracted from REDCap
- convert the data from wide format to long format
- separate data into quantitative (df 'chartdata') and qualitative (df 'textdata')
- adds percentage of whole to quantitative data, except *checkbox* data
