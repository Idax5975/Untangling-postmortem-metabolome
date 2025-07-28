# Untangling-postmortem-metabolome
Scripts available for the research article entitled: "Untangling the Postmortem Metabolome: A Machine Learning Approach for Accurate PMI Prediction"
https://doi.org/10.1021/acs.analchem.4c05796 

This repository is divided into  main folders, sub-folders and sub-sub-folders. Each main folder is divided into sub-folders named by the tissue analysed within the scripts. Main folders and sub-sub-folders are numbered according to the order of the analysis. However, there is no folder 1 as the initial preprocessing was performed in Microsoft Excel. 

Raw data was preprocessed using XCMS - settings and link to script can be found in "0_XCMS settings and script".
To briefly explain the initial preprocessing, features were removed if detected in more than 50% of the blank samples and had a blank contribution ((average blank signal / average QC signal)*100%) greater than 5%. The data is located in the folder "1_Data".
Next, data was imported to R, continuing the preprocessing, data analysis (folder named "2_Data normalization", and modelling (folder named "3_ML").

In the main folder "Functions_R" are the specific functions used for plotting the data.

Please note: updates have been made to the annotations. Check annotation list in the article supplementary.

Packages used for machine learning:

caret (version 7.0-1), glmnet (version 4.1-8), ranger (version 0.17.0)
