# Using a Machine Learning Model to Predict the Presence of Metastatic Tumors
## With a Secondary Analysis Performed on Regional Lymph Nodes

#### Group Members:
* Parsa Moheban
* Mattathias Klassen
* Michelle Kojekine

### Overview:
In this project, we use the RNAseq.csv and data_clinical_patient.txt files in order to create a machine learning model that can predict the presence of metastatic tumors (and regional lymph nodes) via the features and their counts present in RNA.

### Steps Taken in Analysis:
1) Setting up the data and organizing data-frames.
2) Survival analysis following the Kaplan-Meier Estimator for patients with metastatic tumors (M1) and without (M0).
3) PCA.
4) Machine learning model using data from PCA and a training and test set.


### Important Notes:

All the main code is contained in the Metastatic.Rmd file, with an html of the same name being provided as well. The code will need the TCGA KIRC data_clinical_patient.txt file provided and the RNAseq.csv (provided via a link). All other required data is self-contained in the Rmd itself

The plots are contained in a zip file in the main project folder. All other relevant data that was not a plot can be found in the appendix of the research paper.

Data like the RNAseq.csv file was far too large to be uploaded into the main project folder (even after significant compression). Within a file named "RNAseq.csv LINK" is a Google Drive link to a publicly accessible shared folder with the appropriate csv. Please download the data from this link.

The link to the presentation is contained in a .txt file named "Youtube Link". Please access it from there.

The Final Report and outdated Progress Report can be found in the main folder. The report details our idea, methods, and results. It also contains an appendix with the confusion matrices resulting from the output of the logistic regression.

If there are any issues with running the code, finding files, or any other project-related issues. Please contact parsa.moheban@alumni.ubc.ca for assistance

Thank you!
