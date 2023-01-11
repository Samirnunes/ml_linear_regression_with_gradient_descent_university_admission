# Modelo de Regressão Linear via Gradiente Descendente Estocástico com Mini-lotes

Link do artigo associado do Medium: https://medium.com/@samir.silva12342/regress%C3%A3o-linear-com-gradiente-descendente-estoc%C3%A1stico-com-mini-lotes-857818864b6a

Há três notebooks neste repositório:

- 01_linreg_model_implementation.ipynb: contém a implementação passo-a-passo do modelo de regressão linear utilizando Gradiente Descendente Estocástico com Mini-lotes.
- 02_linreg_training_validation_test.ipynb: contém uma aplicação prática do modelo, apresentando também as funções utilizadas para dividir os dados em training, validation e test.
- 03_linreg_L2_regularization.ipynb: contém a implementação passo-a-passo do modelo utilizando também minimização do structural risk e regularização de complexidade via fórmula de regularização L2.
 
A regressão linear é um dos modelos mais conhecidos no contexto do aprendizado de máquina, resumindo-se à adequação de um modelo linear a dados cujos preditores (features) são altamente correlacionados com o valor que se quer estimar (target). Ela pode ser implementada através do algoritmo de Gradiente Descendente Estocástico: um algoritmo iterativo de otimização dos parâmetros da função de regressão baseado na minimização da função de custo (ou de perda). Essa minimização é feita com o cálculo do gradiente negativo da função de custo em relação aos parâmetros da função de regressão (weights e bias).

Os notebooks desenvolvem passo-a-passo o modelo de regressão linear seguindo uma lógica para aprendizado de sua aplicação e implementação, seguindo as boas práticas utilizadas no aprendizado de máquina.

## Dados e Definições (disponíveis também no notebook)

![alt text](https://github.com/Samirnunes/gradient_descent_implementation/blob/main/Imagens/dados_e_definicoes.PNG)

## Tecnologias e Bibliotecas Utilizadas

- Jupyter Notebook
- Python
- Pandas
- Numpy
- Matplotlib
