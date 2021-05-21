# BBB_SVM
Blood-brain barrier (BBB) permeability is an important property for the drugs that act on central nervous system. In attempt to predict the the BBB permeability of compounds we applied Machine learning techniques e.g. SVM, kNN, RF and NB. 

A. Description of files in BBB.rar:
1. Script file : bbb_script.py
2. User input : smiles.smi
3. Prediction model : svm_model.sav
4. Feature Calculation software: PaDEL

B. Execution Steps:
Step 1: Install Anaconda3-5.2 or above.

Step 2: Install or upgrade following libraries (python, numpy, scikit-learn).

Step 3: Download and extract the BBB.rar file. 

Step 4: Save SMILES notation of your compounds in "smiles.smi" file in the extracted folder

Step 5: Change value of path variable in bbb_script.py and execute the script. (Features will be automatically calculated using PaDEL software and SVM model(svm_model.sav) will be executed for prediction)
