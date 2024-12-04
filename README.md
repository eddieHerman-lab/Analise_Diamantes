Análise e  investigação das relações entre as variáveis de um conjunto de dados de diamantes e prever os preços com base em variáveis como o peso (WEIGHT) e características categóricas (como COLOR e RATE). Para melhorar o desempenho preditivo e lidar com multicolinearidade, foram aplicadas técnicas de regularização (Ridge, Lasso e ElasticNet).

# Diamond Price Prediction Analysis

## Descrição Técnica
- Análise preditiva de preços de diamantes
- Objetivo: Modelar preços usando características específicas

## Metodologia
- Técnicas de regularização:
 * Ridge Regression
 * Lasso Regression
 * ElasticNet
- Pré-processamento de dados
- Codificação de variáveis categóricas
- Normalização de variáveis numéricas

## Desafios Técnicos
- Lidar com multicolinearidade
- Seleção de melhores features
- Balanceamento entre precisão e generalização do modelo

## Métricas de Performance
- Mean Squared Error (MSE)
- Validação cruzada
- Comparação de performance entre modelos de regularização

## Tecnologias
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Como Reproduzir
1. Clonar repositório
2. Instalar dependências: `pip install -r requirements.txt`
3. Executar notebook: `jupyter notebook diamond_analysis.ipynb`

