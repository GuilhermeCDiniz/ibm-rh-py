# ibm-rh-py

# 1. Introdução
Este projeto envolve a análise de dados de RH da IBM, disponíveis no site do Kaggle.

Este projeto forneceu insights sobre a distribuição de idade e salários dos funcionários, as taxas de atrito por departamento, e as possíveis disparidades salariais entre gêneros. Utilizando visualizações e análises estatísticas, foi possível entender melhor os fatores que influenciam a retenção e o atrito dos funcionários na IBM.

# Fonte do Dataset
O conjunto de dados foi obtido do Kaggle: IBM HR Analytics Employee Attrition & Performance Dataset.

# 2. Carregando Bibliotecas
As bibliotecas utilizadas no projeto incluem:

pandas para manipulação de dados
numpy para operações numéricas
seaborn e matplotlib para visualização de dados

# 3. Carregando Dataset
O dataset é carregado e analisado com os seguintes comandos:

rh = pd.read_csv('WA_Fn-UseC_-HR-Employee-Attrition.csv')
rh.head()
rh.info()
rh.describe()

![image](https://github.com/user-attachments/assets/4364f829-9685-46b1-8bbf-bb666756465c)
