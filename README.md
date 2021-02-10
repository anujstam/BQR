# BQR
Uncertainty Quantification in Binary Classification via Quantiles

This archive contains all the relevant code for the paper 'Uncertainty Quantification in Binary Classification via Quantiles' in the code folder.

The main notebook, under the code folder, called BQR_IJCNN.ipynb has a walkthrough of all the topics presented in the main paper for a single dataset.
Code for individual components can be found in the Individual_Experiments folder. Some of the topics have not been described in the main work but merely mentioned in the conclusion.

A supplementary file with detailed proofs can be found in the Supplementary folder.

Links to the image archives can be found in the ImageResults folder under the individual experiments.

UCI datasets can be obtained from the UCI machine learning dataset repository

The redshift data can be obtained from here : https://www.sdss.org/dr16/data_access/
You will have to create a Casjob to pull the required data. The range of redshift values is 0 to 7.
The features selected were: modelMag u’, ’modelMag g’, ’modelMag r’, ’modelMag i’, ’modelMag z’, ’modelMag ug’, ’modelMag gr’, 
’modelMag ri’, ’modelMag iz’, ’fiberMag u’, ’fiberMag g’, ’fiberMag r’, ’fiberMag i’, ’fiberMag z’, ’fiberMag ug’, ’fiberMag gr’, ’fiberMag ri’, ’fiberMag iz’, ’petroR50 rr’,
’petroR90 zz’, ’ri’, ’iz’, ’dered u’, ’dered g’, ’dered r’, ’dered i’, ’dered z’, ’petroMag uu’, ’petroMag gg’, ’petroMag rr’, ’petroMag ii’, ’petroMag zz’
For IMDB, please download the 50K review version, create a new folder under datasets named IMDB, and place the Train and Test csvs in that folder

Refer to the dataset_params file for details on how to use the datasets in the notebooks. Please update the path appropriately 
