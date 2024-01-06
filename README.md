# Avalia-o_de_compostos_bioativos_hepg2
Este repositório contém todo o projeto de avaliação de compostos bioativos para a linhagem celular HepG2, desde a extração dos dados até ML.

Arquivo 1: Obtenção de dados
  Neste documento, é possível verificar como os dados foram extraídos da biblioteca CHeMBL

Arquivo 2: Manipulação de dados
  Neste documento, verifica-se como os dados foram tratados para obter um dataframe que possuísse uma classificação por bioatividade

Arquivo 3: Análise de dados exploratória
  Neste documento, utilizou-se a visualização dos dados e comparou-se a bioatividade com as cinco regras de Lipinski. Os testes de diferença estatística foram elaborados utilizando "mannwhitney u test".

Arquivo 4: Preparação de dados ML
  O ponto mais importante deste peojeto e que foi o mais desafiador, neste documento mostro como os SMILES (Simplified Molecular Input Line Entry System) foram codificados em uma linguagem que os algoritmos de ML pudessem aproveitar.

Arquivo 5: ML comparação
  Neste documento, utiliza-se o dataframe criado no último passo para ser testado em diversos algoritmos de regressão, fez-se uso da biblioteca Lazypredict nesta etapa. Desta forma, pode-se eleger o que possuia o melhor score no dataframe de teste e menor erro (RMSE).

Arquivo 6: ML fine tuning
  Utilizando o GridSearchCV obteve-se os melhores hiperparâmetros para o algoritmo RandonFlorestRegressor
  
Este projeto foi feito graças as aulas do professor Chanin Nantasenamat.
