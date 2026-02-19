# Duelo_de_Modelos

🚢 Projeto de Machine Learning – Titanic Survival Prediction
📌 1. Coleta de Dados

Os dados foram obtidos da competição Titanic do Kaggle.
O conjunto contém informações demográficas e socioeconômicas dos passageiros, como:

Idade

Sexo

Classe

Tarifa

Número de familiares

Porto de embarque

Total de registros: 891 (treino).

 2. Modelagem
 Pré-processamento

Tratamento de valores ausentes (mediana/moda)

Extração de título a partir do nome

Criação das variáveis:

FamilySize

IsAlone

Padronização de variáveis numéricas

OneHotEncoding para variáveis categóricas

🔹 Técnicas Utilizadas

XGBoost Classifier

SMOTE (balanceamento)

GridSearchCV (otimização de hiperparâmetros)

Validação cruzada (5-fold)

🔹 Métrica

Accuracy utilizada como métrica principal.

Score obtido no Kaggle: (coloque seu score aqui)

📊 3. Visualizações
Matriz de Confusão

(Insira imagem)

Curva ROC

(Insira imagem)

Importância das Variáveis

(Insira imagem)

📌 4. Conclusões

Sexo é a variável mais relevante para sobrevivência.

Passageiros da 1ª classe tiveram maior taxa de sobrevivência.

Passageiros sozinhos tiveram menor probabilidade de sobrevivência.

Modelos ensemble apresentaram melhor desempenho.
