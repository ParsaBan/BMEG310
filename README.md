# Using a Logistic Model to Predict the Presence of Metastatic Tumors
## With a Secondary Analysis Performed on Regional Lymph Nodes

### Overview:
In this project, we use the ```RNAseq.csv``` and ```data_clinical_patient.txt``` files in order to create a machine learning model that can predict the presence of metastatic tumors (and regional lymph nodes) via the features and their expressions present in RNA.

### Steps Taken in Analysis:
1) Setting up the data and organizing data-frames.
2) Survival analysis following the Kaplan-Meier Estimator for patients with metastatic tumors (M1) and without (M0).
3) PCA.
4) Logistic regression model using data from PCA and a custom training and test set.


### Important Notes:

The main codebase is contained in the Metastatic.Rmd file, with an html of the same name being provided as well. The codebase requires the TCGA KIRC ```data_clinical_patient.txt``` file provided and the ```RNAseq.csv``` (provided via a link). All other required data is self-contained in the Rmd itself

The plots are contained in a zip file in the main project folder. All other relevant data that was not plotted can be found in the appendix of the research paper.

Data like the ```RNAseq.csv``` file was far too large to be uploaded into the main project folder (even after significant compression). Within a file named "RNAseq.csv LINK" is a Google Drive link to a publicly accessible shared folder with the appropriate csv. Please download the data from this link.

The Final Report can be found in the main folder. The report details our idea, methods, and results. It also contains an appendix with the confusion matrices resulting from the output of the logistic regression.

If there are any issues with running the Rmd file, finding files, or any other project-related issues, please contact parsa.moheban@alumni.ubc.ca for assistance

Thank you!
