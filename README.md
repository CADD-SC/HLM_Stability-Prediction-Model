# HLM-Stability-Prediction-Model
Machine Learning-based prediction model for Human Liver Microsomal (HLM) stability prediction.

**Introduction:**

Welcome to our repository, here we provide machine learning model to efficiently predict the Human Liver Microsomal (HLM) stability of target drug compounds in early stage of drug discovery process. 

**Dependencies:**

  - python=3.7
  - rdkit
  - chembl_webresource_client
  - seaborn
  - scikit-learn
  - pickle5
  - jupyter
  - molvs
  - python-graphviz
  - pydotplus


**Execution:**

Use Jupyter notebook to execute the code, download all the provided input files and HLM_stability.pkl model file before execution.

Prepare your input file containing SMILES in .csv format and name the column as “SMILES”.

Make sure the paths of model, HLM_stability.pkl file and input files before executing the code file named as HLM_stability_Prediction_model.ipynb.

**Output:**

Our model generates output in binary value (1 or 0), where 1 indicates compound to be stable, while 0 indicates unstable.


**Authors:** 

Maninder Singh, Bilal Shaker, Jin Hee Lee, Sunghwan Choi, Sanghee Yoon, Shaherin Basith, Minghua Cui, Sunil Ahn, Haerim Han, Min SunYeom* and Sun Choi*
