## Solubility Prediction with Machine Learning
This project explores the use of machine learning techniques to predict the solubility of molecules, a crucial parameter for drug discovery.
It utilizes the scikit-learn library in Python to build and evaluate models on a publicly available dataset. 
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
