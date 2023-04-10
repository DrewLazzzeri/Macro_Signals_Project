
Filtering Stock Data and Merging Compustat Returns.ipynb: A file which reads in the datashare csv file from the Empirical Asset Pricing Via Machine Learning 
paper and appends computat return data to the referenced securities. Note, the datashare file is too large to post on Github and available on the
author's website. 

Macroeconomic Dataframe Processing.ipynb:  A Jupyter Notebook which reads in the McCracken data, makes the prescribed transformations and outputs
a csv file with the processed McCracken data as outlined on the website.

McCracken_Data.csv: The raw McCracken data used for the study (the specific vintage will be available on the website). 

RegimeLASSO.ipynb: Current working file which splits the securities into larger industries by SIC code and then evaluates the sensitivity to each 
during specific macro regimes based on the whole cross-section and by larger industry grouping.