# Stock-Forecasters
Collection of different ML/DL models for stock forecasting.

## Models - Deployed Notebooks on Web
1. LSTM: [https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-9qd2yu6e/doc/tree/models/LSTM.ipynb](https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-le8stpfx/lab/tree/models/LSTM.ipynb)
2. GRU: [https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-9qd2yu6e/doc/tree/models/GRU.ipynb](https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-le8stpfx/lab/tree/models/GRU.ipynb)
3. CNN: [https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-9qd2yu6e/doc/tree/models/CNN.ipynb](https://hub.binder.curvenote.dev/user/liamjdavis-stock-forecasters-le8stpfx/lab/tree/models/CNN.ipynb)

All dependencies are installed in the web versions. To run a forecast, input the stock ticker to forecast in the first codeblock and run(further instructions in each notebook.) To run on a local machine, follow this installation process:

1. Clone the repository
```git clone https://github.com/liamjdavis/Stock-Forecasters.git```
2. Run requirements.txt
```pip install -r requirements.txt```

This will install all dependencies. To run each forecaster, go to the specific notebook in the "models" folder, change the ticker and run. 

## Python Versions
The forecasters are supported on any python version where tensorflow is supported. As of January 2024, that is python 3.9, 3.10 and 3.11. Once the new python versions support tensorflow, those versions will also be supported. 
