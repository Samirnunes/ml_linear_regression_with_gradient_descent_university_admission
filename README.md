# Implementação do Gradiente Descendente Estocástico com Mini-lotes
 
A regressão linear é um dos modelos mais conhecidos no contexto do aprendizado de máquina, resumindo-se à adequação de um modelo linear a dados cujos preditores (features) são altamente correlacionados com o valor que se quer estimar (label). A regressão linear pode ser implementada através do algoritmo de Gradiente Descendente Estocástico, um algoritmo iterativo de otimização dos parâmetros (weights e bias) da função de regressão baseado na minimização da função de custo (ou de perda) por meio do cálculo do gradiente negativo dessa função via amostragem bootstrap, no caso de feito com mini-lotes (mini-batch). 

Neste repositório, encontra-se um notebook com a formulação matemática do algoritmo de Gradiente Descendente Estocástico com Mini-lotes e com sua implementação em modelos de regressão linear aplicados no dataset "Data for Admission in the University", disponível no Kaggle, para prever a chance de admissão de estudantes em universidades de diferentes classificações com base em seu desempenho acadêmico anterior.

São feitos dois modelos: um modelo de regressão linear com 1 feature, abordando o caso mais simples, e um modelo de regressão linear que suporta um número qualquer de features (o qual é, de fato, utilizado em ciência de dados), aplicado ao caso em que há 6 features contínuas.

# Dados e Definições (disponíveis também no notebook)

![alt text](https://github.com/Samirnunes/gradient_descent_implementation/blob/main/Imagens/dados_e_definicoes.PNG)

# Tecnologias e Bibliotecas Utilizadas

- Jupyter Notebook
- Python
- Pandas
- Numpy
- Matplotlib
