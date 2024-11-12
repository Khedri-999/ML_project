## Solubility Prediction with Machine Learning
This repository contains a Python-based machine learning project aimed at predicting the solubility of molecules. It utilizes the scikit-learn library to build and evaluate models on a publicly available dataset. The project explores various machine learning techniques, including linear regression and random forest, to predict the solubility of molecules based on their molecular properties. 
## Dataset
The dataset contains 1444 rows (molecules) and 5 columns:

* **MolLogP:** Molecular LogP, a measure of lipophilicity.
* **MolWt:** Molecular weight.
* **NumRotatableBonds:** Number of rotatable bonds.
* **AromaticProportion:** Proportion of aromatic atoms.
* **logS:** Experimental solubility (target variable).

* ## Project Structure
* The project consists of several Python scripts (e.g., solubility_prediction.py, data_preprocessing.py) that perform various tasks like data loading, preprocessing, model building, and evaluation.
* ## Usage

### Prerequisites:

* Python 3.x
* Required libraries: pandas, scikit-learn, matplotlib, numpy

### Running the Project:

1. Clone the repository:

   ```bash
   git clone [https://github.com/Khedri-999 /solubility-prediction.git](https://github.com/Khedri-999 /solubility-prediction.git)
   pip install pandas scikit-learn matplotlib numpy
   cd solubility-prediction
   python solubility_prediction.py 
