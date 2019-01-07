# Bank-Marketing-Analysis
Desafio Data Science 
</br>Dataset : Bank Marketing 
</br>Fonte oficial do dataset  : https://archive.ics.uci.edu/ml/datasets/bank+marketing 
</br>Dados: https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip 
</br>Arquivos incluídos no link acima:  
    </br>● bank. csv: uma versão reduzida do conjunto de dados;    
    </br>● bank-full.csv: o conjunto completo;   
    </br>● bank-names.txt: com a descrição dos campos do conjunto de dados.


#Import

</br>import numpy as np
</br>import pandas as pd
</br>import random
</br>import warnings
</br>warnings.filterwarnings("ignore")
</br>import seaborn as sns
</br>import matplotlib.pyplot as plt
</br>%matplotlib inline

</br>from sklearn import preprocessing
</br>from sklearn.linear_model import LogisticRegression
</br>from sklearn.model_selection import train_test_split
</br>from sklearn.metrics import mean_squared_error
