# Deep Learning for Finance

Code examples for the course of Deep Learning for Finance
- 00 Intro to Keras
- 01 Credit scoring
- 02 Time series forecasting
- 03 RNN whit Keras for Sentiment model


# Anaconda environment in windows

- Install anaconda3 - version 5.  Default install options

- To create the environment, open an Anaconda prompt and execute

```
# Install jupyter extensions 
conda install anaconda-nb-extensions -c nb-conda
```


```
# Create the environment

conda create -n tf12 python=3.5
activate tf12

conda install graphviz
conda install pandas scikit-learn
conda install -c anaconda jupyter 
conda install matplotlib
conda install pillow 
pip install h5py
pip install nltk
pip install pydot-ng
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.2.0-cp35-cp35m-win_amd64.whl
pip install keras
```
