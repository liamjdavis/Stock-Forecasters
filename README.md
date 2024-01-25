# Stock-Forecasters
Collection of different ML/DL models for stock forecasting.

## Models - Deployed Notebooks on Web
1. LSTM: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/223e47c4874cf588a53d9b428d64524e7715f741?urlpath=lab%2Ftree%2Fmodels%2FLSTM.ipynb
2. GRU: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/223e47c4874cf588a53d9b428d64524e7715f741?urlpath=lab%2Ftree%2Fmodels%2FGRU.ipynb
3. CNN: https://mybinder.org/v2/gh/liamjdavis/Stock-Forecasters/223e47c4874cf588a53d9b428d64524e7715f741?urlpath=lab%2Ftree%2Fmodels%2FGRU.ipynb

All dependencies are installed in the web versions. To run a forecast, input the stock ticker to forecast in the first codeblock and run(further instructions in each notebook.) To run on a local machine, follow this installation process:

1. Clone the repository
```git clone https://github.com/liamjdavis/Stock-Forecasters.git```
2. Run requirements.txt
```pip install -r requirements.txt```

This will install all dependencies. To run each forecaster, go to the specific notebook in the "models" folder, change the ticker and run. 

## Python Versions
The forecasters are supported on any python version where tensorflow is supported. As of January 2024, that is python 3.9, 3.10 and 3.11. Once the new python versions support tensorflow, those versions will also be supported. 
