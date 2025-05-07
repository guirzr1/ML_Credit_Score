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

## Tecnologias e bibliotecas utilizadas
- Python
- Pandas, NumPy
- Scikit-Learn
- Imbalanced-Learn (SMOTE)
- Matplotlib/ Seaborn
- RegressionLogistic

## Possíveis melhorias futuras
- implementar um dashboard com Streamlit para uma analise interativa
- Criar uma API com FastAPI
- Testar modelos mais robustos com validacao cruzada estratificada

## Consideracoes Finais
Mais do que um projeto técnico, esse trabalho representa uma jornada de aprendizado. Mesmo com obstáculos (como o curso desatualizado), aprendi sobre risco de crédito, ética no uso de dados (LGPD), e ganhei mais segurança para aplicar técnicas de Machine Learning de forma responsável.

  
