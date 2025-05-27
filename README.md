# Machine Learning for Lung Cancer Survival Prediction

Lung cancer is one of the most common and lethal types of cancer worldwide. Early diagnosis and appropriate treatment play a crucial role in reducing mortality associated with this disease. Artificial intelligence techniques can be used to support clinical approaches to lung cancer, helping healthcare professionals to make informed decisions and personalize treatments. This study proposes the application of supervised machine learning techniques to develop and evaluate models that can classify lung cancer patients according to their survival time, distinguishing between those with short and long survival times. The incorporation of these models into clinical practice can support decision-making and personalization of patient treatments.


# Dataset

The dataset used was obtained from [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga), containing data from lung cancer patients. The dataset has 56 columns, with information such as gender, ethnicity, race, age, year of birth, year of diagnosis, clinical and pathological TNM staging, tumor classification, diagnostic method, primary diagnosis, data on the existence of previous cancer, disease progression, whether there is residual disease after treatment, tumor position, presence or absence of other types of tumor at the same time, and type of treatment. The **pre-processing.pdf** file shows how the pre-processing steps of the data obtained were carried out. The **TableauPrepStep1.tfl** and **TableauPrepStep2.tfl** files are the pre-processing flows performed with the Tableau Prep tool.

# Implementation 

Five Machine learning algorithms were implemented to analyze which one performs best in classifying patients:

- Random Forest
- Logistic Regression
- K Nearest Neighbor
- Decision Tree
- Support Vector Classifier

The models were implemented in two ways **lung_cancer_survival_prediction.ipynb**, without applying parameter customization and **lung_cancer_survival_prediction_with_tunning.ipynb** applying tools to identify the best configuration to run the algorithms for the dataset. The notebooks have alternative codes to perform class balancing, offering different oversampling and undersampling techniques and combinations. Choose one of them to perform the test. 

## Requirements 

- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Imblearn](https://imbalanced-learn.org/)
- [Chardet](https://pypi.org/project/chardet/)
- [Openpyxl](https://openpyxl.readthedocs.io/)
- [jinja2](https://pypi.org/project/Jinja2/)
- [SHAP](https://shap.readthedocs.io/)

```sh
pip install pandas matplotlib seaborn scikit-learn imbalanced-learn chardet openpyxl jinja2 shap
```

# About the authors

Isabel H. Manssour - Researcher and Professor Coordinator of DaVInt. 2017-current.  
Rodrigo Henrich - Master Student in Computer Science - 2023-2025.  
More information can be found at [here](https://www.inf.pucrs.br/davint/).
