## CIVE202_Project4 - Risk Adverse, LLC
This repository contains the files and information for CIVE 202 Project #4. The Python code in this project is used to compare FEMA's National RIsk Index (NRI) risk scoring method toward our own proposed risk defintion. The aim of this project is to investigate how changing the approach to calculate risk will impact the results for each community. For this project, we use NRI Census tract data, Social Vulnerability Index (SVI) data, NRI data dictionary, and Census tract shapefiles. The two main states analyzed in the written report are Florida and Wyoming and a non main addition of Louisiana. The cleaning and analysis of these datasets were done using the Python code to generate comparative plots and GeoPandas maps.

## Repository Contents
- Project4_Code.ipynb – Python code for the project
- Project4_ACD.docx – Document annotated with code explanations
- Project_4_Risk_Averse_Writing_Report.docx – Summary of the methods and results
- Raw data files – Raw data (NRI, SVI, metadata, shapefiles)
- Project4_Scope_of_Work - Document laying out the clients requests
- Project4_Timesheet - Showing the teams hours spent on each activity 

# How To Run
To run the data you first must download the Python notebook to your device. You must also downloaded all the raw data files for the project and save them in the same directory where the Python notebook is located. These data files include the NRI, SVI files, shapefile files, and the data dictionary of the NRI. Execute each cell one after the other from the top to the bottom. Each cell is divided into blocks, and each block is labeled to ease your navigation. Package import is done in the first block. The second block involves loading and cleaning of the datasets. In the next blocks, the merging of data, creation of the risk calculation, and generation of figures are done.

Due to some shapefiles and the NRI dictionary being too large to upload here, you can access and downloads these files here:
- https://uofnebraska-my.sharepoint.com/personal/37381171_nebraska_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F37381171%5Fnebraska%5Fedu%2FDocuments%2FTeaching%2FCIVE%20202%2FSpring%202026%2FProject%20%234%2FSHP%20by%20State%2FStudent%20Shape%20Files&ga=1
- https://uofnebraska-my.sharepoint.com/:x:/g/personal/37381171_nebraska_edu/IQAvXCXswi0qRYTbxnHb9OY3AfHntK45kx768_5_-5FUQe8?e=McTQTt

# User Guide
The Python notebook is what carries out all the coding processes in this project. The annotated code file provides explanations for the coding steps in the Python notebook. The written report highlights the background of the project, process used, results, and comparison between FEMA's method of calculating the risk and our proposed method. The raw data files are included so the code can run correctly and so the project can be reproduced. 
The Python notebook does not require user inputs. The selected states, hazards, and risk variables are already set directly into the code. If the user wishs to change the state or harzard being analyized you would need to edit the variables and column selected in the notebook.


