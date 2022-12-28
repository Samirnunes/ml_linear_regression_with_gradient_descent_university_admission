# Modelo de Regressão Linear via Gradiente Descendente Estocástico com Mini-lotes

Há dois notebooks neste repositório:

- implementation.ipynb: contém a implementação passo-a-passo do modelo de regressão linear utilizando gradiente descendente estocástico com mini-lotes.
- training_validation_test.ipynb: contém uma aplicação prática do modelo, apresentando também as funções utilizadas para dividir os dados em training, validation e test.
 
A regressão linear é um dos modelos mais conhecidos no contexto do aprendizado de máquina, resumindo-se à adequação de um modelo linear a dados cujos preditores (features) são altamente correlacionados com o valor que se quer estimar (label). Ela pode ser implementada através do algoritmo de Gradiente Descendente Estocástico, um algoritmo iterativo de otimização dos parâmetros (weights e bias) da função de regressão baseado na minimização da função de custo (ou de perda) por meio do cálculo do gradiente negativo dessa função via amostragem bootstrap, no caso de feito com mini-lotes (mini-batch). 

Neste repositório, encontra-se o notebook "implementation.ipynb" com a formulação matemática do algoritmo de Gradiente Descendente Estocástico com Mini-lotes e com sua implementação em modelos de regressão linear aplicados no dataset "Data for Admission in the University", disponível no Kaggle, para prever a chance de admissão de estudantes em universidades de diferentes classificações com base em seu desempenho acadêmico anterior. São feitos dois modelos: um modelo de regressão linear com 1 feature, abordando o caso mais simples, e um modelo de regressão linear que suporta um número qualquer de features (o qual é, de fato, utilizado em ciência de dados), aplicado ao caso em que há 6 features contínuas.

Há também o notebook "training_validation_test.ipynb" com uma aplicação prática do modelo no mesmo dataset, separando-o em dados de treinamento do modelo, dados de
validação e dados de teste.

# Dados e Definições (disponíveis também no notebook)

![alt text](https://github.com/Samirnunes/gradient_descent_implementation/blob/main/Imagens/dados_e_definicoes.PNG)

# Tecnologias e Bibliotecas Utilizadas

- Jupyter Notebook
- Python
- Pandas
- Numpy
- Matplotlib
