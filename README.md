# Stock-Forecasters
This is a collection of ML/DL models for stock forecasting. There are 3 forecasters:
1. LSTM Network
2. GRU Network
3. Convolutional Neural Network

The models are run in jupyter notebooks that are in the "models" folder. Each notebook both runs and visualizes the forecast. Each of them currently have a S&P 500 forecast as an example. Each model is also deployed on the web through binder, linked below.

## Models - Deployed Notebooks on Web
1. LSTM: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/ed47656b1c03f77b4a874a2d7e1d49f070d0b454?urlpath=lab%2Ftree%2Fmodels%2FLSTM.ipynb
2. GRU: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/ed47656b1c03f77b4a874a2d7e1d49f070d0b454?urlpath=lab%2Ftree%2Fmodels%2FGRU.ipynb
3. CNN: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/ed47656b1c03f77b4a874a2d7e1d49f070d0b454?urlpath=lab%2Ftree%2Fmodels%2FCNN.ipynb

All dependencies are installed in the web versions. To run a forecast, input the stock ticker to forecast in the first codeblock and run(further instructions in each notebook.) But, the build process on binder is slow. To run it on your local machine, follow this installation process:

1. Clone the repository
```git clone https://github.com/liamjdavis/Stock-Forecasters.git```
2. Run requirements.txt
```pip install -r requirements.txt```

This will install all dependencies. To run each forecaster, go to the specific notebook in the "models" folder, change the ticker and run. 

## Python Versions
The forecasters are supported on any python version where tensorflow is supported. As of January 2024, that is python 3.9, 3.10 and 3.11. Once the new python versions support tensorflow, those versions will also be supported. 
