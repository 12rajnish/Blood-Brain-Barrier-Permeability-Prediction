# Blood-Brain-Barrier-Permeability-Prediction
Blood-brain barrier (BBB) permeability is an important property for the drugs that act on central nervous system. In attempt to predict the the BBB permeability of compounds we applied Machine learning techniques e.g. SVM, kNN, RF and NB. 

Step 1
Install Anaconda3-5.2 or above.

Step 2
Install or upgrade following libraries (python, numpy, tensorflow, keras, scikit-learn).

Step 3
Prepare input file (user_input.csv). Calculate molecular properties and fingerprints from SMILES format of a chemical compound using software’s like PaDel, alvaDesc, DRAGON, etc. and save as user_input.csv. Keep the header information (first row) as such in input file.

Step 4
Change value of path variable in bbb_script.py available here and execute the script.
