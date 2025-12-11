This repository is related to a manuscript submited. The link of the manuscript will be shared once available. 

------------------------------------------------------------------------------------

Modeling code: ModelBuilder.py
Predictor code: ModelPredictor.py
ChemBL dataset: ChemBL.csv
lombardo dataset: lombardo.csv
lombardo dataset with descriptors: lombardo_descriptors.csv
------------------------------------------------------------------------------------
To run the codes: 
------------------------------------------------------------------------------------
Conda environment

Python version 3.8.11
Packages:
# Name Version                  
numpy   	1.19.4
pandas 	1.2.1
rdkit   	2020.09.3
pickle 	4.0
sklearn	0.24.1
------------------------------------------------------------------------------------
In command line type these:

python ModelBuilder.py
python ModelPredictor.py

------------------------------------------------------------------------------------
Or in the python prompt, copy and paste all the code in ModelBuilder.py to build the model and copy and paste all the code in ModelPredictor.py to make predictions.

For simplicity, the descriptor file for the lombardo dataset (lombardo_descriptors.csv) is also attached. The descriptor file can be directly used by the prediction code.



