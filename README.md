# Machine Learning for Lung Cancer Survival Prediction

O câncer de pulmão é um dos tipos mais comuns e letais de câncer em todo o mundo. O diagnóstico precoce e o tratamento adequado desempenham um papel crucial na redução da mortalidade associada a essa doença. A inteligência artificial tem se tornado uma ferramenta promissora na medicina, tendo em vista que dos 64 estudos relacionados analisados 55 mencionam o uso de alguma técnica de aprendizado de máquina. Este estudo propõe a aplicação de técnicas de aprendizado de máquina para desenvolver e avaliar modelos que classifiquem pacientes com câncer de pulmão de acordo com seu tempo de sobrevida (curta ou longa). A incorporação desses modelos na prática clínica pode apoiar a tomada de decisão e a personalização dos tratamentos, visando melhores resultados clínicos e qualidade de vida para os pacientes.


# Dados

O conjunto de dados utilizado foi obtido do [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga), contendo dados de pacientes com câncer de pulmão. O conjunto de dados conta com 56 colunas, com informações como gênero, etnia, raça, idade, ano de nascimento, ano de diagnóstico, estadiamento TNM clínico e patológico, classificação do tumor, método de diagnóstico, diagnóstico primário, dados sobre a existência de câncer anterior, progressão da doença, se existe doença residual após o tratamento, posição do tumor, presença ou não de outros tipos de tumor ao mesmo tempo e tipo de tratamento.

# Implementação 

Foram implementados cinco algoritmos de Machine learnig para analisar qual obtem o melhor desempenho na classificação dos pacientes

- Random Forest
- Logistic Regression
- K Nearest Neighbor
- Decision Tree
- Support Vector Classifier

Os modelos foram implementados de duas formas **lung_cancer_survival_prediction.ipynb**, sem aplicar customização de parâmetros e **lung_cancer_survival_prediction_with_tunning.ipynb** aplicando ferramentas para identificar qual a melhor configuração para rodar os algoritmos para o conjunto de dados.

## Requisitos 

- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Imblearn](https://imbalanced-learn.org/)
- [Chardet](https://pypi.org/project/chardet/)
- [Openpyxl](https://openpyxl.readthedocs.io/)

```sh
pip install pandas matplotlib seaborn scikit-learn imbalanced-learn chardet openpyxl
```

# Sobre os autores

Isabel H. Manssour - Professor coordenadora do DaVInt - 2017-current.  
Rodrigo Henrich - Mestrando em ciência da computação - 2023-2025.  
Mais informações podem ser encontradas [aqui](https://www.inf.pucrs.br/davint/).
