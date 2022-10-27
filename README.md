<em>This readme was written in English and Portuguese</em><br/>

# Predict Price of Bitcoin - DataQuest Project

Bitcoin is a descentralized cryptocurrency (no control of any institution) with high market value, that is uses in internet as alternative to us dolar, real, euro and others.

In this project I was made a sentiment analysis about Bitcoin [Wikipedia Page](https://en.wikipedia.org/wiki/Bitcoin) comments by users that did revisions.

So I was extract the price of Bitcoin in Dolar(BTC-USD) with Yahoo Finance API to obtain historical data

With these features/variables/data I was be able a predictive model to predict whether Bitcoin price is going to up or down

This model wasn't perfect, with a accurancy of 53.31%. But was good to learn new tools (Machine Learning Algorithms, APIs) and time-series analysis

<em>Accepting feedbacks about project</em>
<br/>


# Prevendo o Preço do Bitcoin - Projeto DataQuest

Bitcoin é uma criptomoeda descentralizada (sem controle de uma instituição) com alto valor, sendo utilizado na internet como uma alternativa do real, dólar, euro, e outros tipos de moedas.

Nesse projeto foi feito uma ánalise de sentimento sobre comentários da página de Bitcoin do [Wikipedia em inglês](https://en.wikipedia.org/wiki/Bitcoin) nas revisões dadas aos editores da página

E também extraí o preço do Bitcoin em Dólar(BTC-USD) utilizando a API do Yahoo Finance para obter o histórico dos dados

Com essas features/variáveis/dados pude então fazer um modelo preditivo que prevê se o preço do Bitcoin irá subir ou descer.

O modelo não ficou perfeito, tendo uma precisão de 53.31%. Mas valeu para o ensino das ferramentas(Algoritmos de Machine Learning, APIs) e a análise de time-series.

<em>Aceito qualquer tipo de feedback sobre o projeto</em>

<br/>

### Files Roadmap
* `BitcoinPredictTomorrowsPrice_SentimentAnalysis.ipynb`: notebook that contain sentiment analysis about bitcoin through revision wiki page comments using `mwclient`, and creation of dataset `wikipedia_edits.csv` and `wikipedia_rolling_means_edits.csv`

* `BitcoinPredictTomorrowsPrice_PredictionAnalysis.ipynb`: notebook that contains a merged dataset about sentiment wiki page revision comments with BTC-USD historical data; model creations - Random Forest, and XGBoost Classifier; and other transforming data functions 

* `dicionario_dados_sentiment_analysis.ods`: data dictionary about `wikipedia_edits.csv` and `wikipedia_rolling_means_edits.csv`

* `wikipedia_edits.csv`: extracted dataset about edits/revisions transformed in sentiment analysis notebook

* `wikipedia_rolling_means_edits.csv`: extracted rolling function dataset about some data on `wikipedia_edits.csv`

### Project Steps
* Load in Data
* Clean and Merge Data
* Create an initial machine learning model and estimate accuracy
* Switch to a more powerful model and improve our predictors


### Python Packages
* pandas
* yfinance
* scikit-learn
* xgboost
* mwclient
* transformers

### Tools, Sources and References
<hr/>

* [Youtube Video of Project by Vik Pararuchi - DataQuest](https://www.youtube.com/watch?v=TF2Nx_ifmrU)

* [Github of Project by Vik Pararuchi - DataQuest](https://github.com/dataquestio/project-walkthroughs/tree/master/bitcoin_price)

* [mwclient docs - MediaWiki Client API to fetch wiki info](https://mwclient.readthedocs.io/en/stable/reference/index.html)

* [yfinance docs - Yahoo Finance Client API to fetch historical market](https://pypi.org/project/yfinance/)

<em>I'm want to thanks for the DataQuest and Vik Pararuchi for available this Data Science Guided Project that will help me to be a Data Scientist one day</em>






