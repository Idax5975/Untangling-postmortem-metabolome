# Untangling-postmortem-metabolome
Scripts available for the research article entitled: "Untangling the Postmortem Metabolome: A Machine Learning Approach for Accurate PMI Prediction"

This repository is divided into  main folders, sub-folders and sub-sub-folders. Each main folder is divided into sub-folders named by the tissue analysed within the scripts. Main folders and sub-sub-folders are numbered according to the order of the analysis. However, there is no folder 1 as the initial preprocessing was performed in Microsoft Excel. 

To briefly explain the initial preprocessing, features were removed if detected in more than 50% of the blank samples and had a blank contribution ((average blank signal / average QC signal)*100%) greater than 5%.
Next, data was imported to R, continuing the preprocessing, data analysis, and modelling in the folders starting with the numbers "2" and "3".

In the main folder "Functions_R" are the specific functions used for plotting the data.
