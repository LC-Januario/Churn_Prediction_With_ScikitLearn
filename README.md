```markdown
# Churn Prediction in Streaming Platform

## Project Overview
Você trabalha em uma plataforma de streaming e a diretoria está preocupada com o alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça, e com base nessa informação tomar ações para reduzir o churn.

Seu objetivo é criar um modelo de classificação capaz de prever se um usuário tem mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa forneceu uma base de dados em CSV contendo dados sobre as contas dos clientes.

## Data Description
Os dados fornecidos possuem informações sobre as contas dos clientes na plataforma de streaming, divididos entre contas Basic, Standard e Premium, onde cada uma oferece uma gama maior de serviços que a anterior. 


## Requirements
- Python 3.6+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib


## Usage
### 1. Data Preprocessing
Carregue os dados e faça o pré-processamento necessário, como a conversão de datas e a codificação de variáveis categóricas.

### 2. Feature Engineering
Crie novas features se necessário, por exemplo, o tempo desde o último login.

### 3. Model Training
Treine os modelos `RandomForestClassifier` e `LogisticRegression` para prever o churn.

### 4. Model Evaluation
Avalie a performance dos modelos utilizando métricas apropriadas como acurácia, precisão, recall, e F1-score.

### 5. Deployment
Implemente o modelo selecionado em produção para monitorar e prever churn em tempo real.


## Results
Os resultados dos modelos são comparados e o modelo com melhor performance é selecionado para a implementação. As métricas de avaliação incluem acurácia, precisão, recall e F1-score. The LogisticRegression model has failed to produce any positive results, but the RandomTreeClassifier model has shown some potencial

## Contributing
Sinta-se à vontade para contribuir com este projeto. Faça um fork do repositório, crie um branch para suas modificações e envie um pull request com suas melhorias.



## Contact
[luizcl2000@gmail.com]
```
