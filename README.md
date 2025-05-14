# ML_Credit_Score

## Projeto de Credit Scorring

Este projeto foi desenvolvido como parte dos meus estudos em Data Science, seguindo um curso da Alura. Apesar do curso estar um pouco desatualizado, decidi seguir em frente, adaptando o conteúdo com conhecimentos mais recentes que fui adquirindo ao longo do caminho.

## O que aprendi

Durante o projeto, tive contato com diversas áreas importantes do ciclo de concessão de crédito. Descobri que ele é sustentado por quatro pilares fundamentais:
Prospecção
Concessão
Gestão de Risco
Recuperação

Além disso, compreendi que o Credit Score é, na prática, um problema de classificação, onde buscamos prever a probabilidade de inadimplência a partir de uma base de dados.

## Tecnicas Aplicadas 

Mesmo tendo como base a regressão logística, proposta pela instrutora do curso, resolvi ir além e explorei outras abordagens e boas práticas de Machine Learning. 
Aqui estão algumas etapas e decisões que tomei no processo:

- Carregamento e limpeza dos dados
- Pré-processamento personalizado, usando:
OneHotEncoder para variáveis categóricas
StandardScaler para normalização
- Busca por melhores hiperparâmetros com GridSearchCV
- Avaliação com:
Matriz de Confusão
Curva ROC
Comparação com DummyClassifier (baseline)
- Feature Engineering guiada por boas práticas e pela LGPD
- TESTE A/B com outros algoritmos: Comecei com RandomForest e depois fiz teste com LogisticRegression e XGBoost

## Tecnologias e bibliotecas utilizadas
- Python
- Pandas, NumPy
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Matplotlib/ Seaborn
- RandomForest, XGBoost, LogisticRegression

## Possíveis melhorias futuras
- implementar um dashboard com Streamlit para uma analise interativa
- Criar uma API com FastAPI
- Testar modelos mais robustos com validacao cruzada estratificada

## Consideracoes Finais
A regressao Logisitica se mostrou o melhor modelo no meu A/B tanto em AUC quanto no F1-score da classe possitiva. O XGBoost teve o pior desempenho o que podiamos ver a necessidade de um tunning nos hiperparametros e o RandomForest ficou muito proximo. Gostei de fazer o projeto, quero aprender mais sobre Features Engineering ter o pensamento critico para melhorar cada vez mais os modelos, esse tambem foi meu primeiro projeto de Machine Learning feito sozinho com a ajuda do GPT, pretendendo fazer mais por que é uma area que gosto muito de fazer e futuramente implementar no ambiente de execucao. 

  
