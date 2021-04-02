# EstimatingEconomicGrowth

A Deep Learning model which predicts the economic growth in terms of the change in GDP per capita of a country using several economic variables. 

The data has been taken from the World Development Indicators Data Bank of the World Bank. 

1. `data.csv` contains the original dataset. 
2. `data_analysis.ipynb` analyses the dataset and creates `data_final.csv` and `data_change_final.csv` which contains the pre-processed data for estimating the GDP per capita and the change in GDP per capita respectively. 
3. `train.ipynb` trains the model using the data in `data_final.csv`. 
4. `train_change.ipynb` trains the model using the data in `data_change_final.csv`. 