# Projeto de Predição de Valores de Ouro

Este projeto tem como objetivo fornecer um código em Jupyter Notebook para prever o preço do ouro usando diversos métodos de previsão de séries temporais. O conjunto de dados utilizado para a análise consiste nos preços diários do ouro em USD no período de 1950-01 a 2020-07, totalizando 847 pontos de dados. O Notebook Jupyter incluído neste repositório contém o código para construir e avaliar três modelos de previsão de séries temporais diferentes: Modelo de Regressão Linear, Modelo Ingênuo e Modelo de Suavização Exponencial. O Modelo de Suavização Exponencial obteve o melhor desempenho com um MAPE de 17,235%. As previsões dos preços do ouro para o período de 2020-08 a 2025-02 usando o Modelo de Suavização Exponencial também são fornecidas em um arquivo CSV chamado "gold_price_predictions.csv". O conjunto de dados, código e resultados podem ser acessados através do projeto Kaggle e do repositório GitHub fornecidos nas referências.

## Arquivos do Projeto

- `gold_price_predictions.csv`: Arquivo CSV contendo as previsões dos preços do ouro para o período de 2020-08 a 2025-02.

- `gold_price_prediction.ipynb`: Jupyter Notebook contendo o código para construir e avaliar os modelos de previsão de séries temporais.

## Requisitos de Instalação

Para executar o código neste projeto, você precisará das seguintes bibliotecas Python:

- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- scikit-learn

Você pode instalar as bibliotecas necessárias usando o seguinte comando:

```
pip install numpy pandas seaborn matplotlib statsmodels scikit-learn
```

## Como Usar

1. Faça o download dos arquivos do projeto.

2. Certifique-se de ter todas as bibliotecas necessárias instaladas.

3. Execute o arquivo `gold_price_prediction.ipynb` em um ambiente Jupyter Notebook.

4. Siga as instruções no notebook para construir e avaliar os modelos de previsão de séries temporais.

## Contribuição

Contribuições são bem-vindas! Se você quiser contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Referências

- Conjunto de dados original: [Gold Prices - Monthly](https://www.kaggle.com/akdurai/gold-prices)

- Projeto Kaggle: [Time Series Prediction on Gold Prices](https://www.kaggle.com/akdurai/time-series-prediction-on-gold-prices)
