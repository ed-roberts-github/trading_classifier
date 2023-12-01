# trading_classifier
Learning resource to make algorithmic ML trading model. Trains a Classifier on lagged return data of EUR/USD.

Note this model is fundamentally flawed due to the efficient markets hypothesis. However, it is still a useful resource for practicing manipulating market data, training ML models, vectorised backtesting etc.  

* load_data.ipynb downloads market data from the API, preprocesses and saves CSVs
* SVM_model.ipynb builds a simple Support vector classifier to predict market direction
* NN_model.ipynb builds a simple neural network classifier to predict market direction. Note this is done in PyTorch lightning... which is overkill but good learning