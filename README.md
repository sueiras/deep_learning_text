# Deep learning use case

Sentiment analysis and word tagging


# Anaconda environment

1.- Install anaconda3 version 5. All default options.

2.- Start an Anaconda terminal and execute...

```
# Install jupyter extensions 
conda install anaconda-nb-extensions -c nb-conda
```


```
# Create environment and install deep learning packages
conda create -n tf12 python=3.5
activate tf12

conda install graphviz
conda install pandas scikit-learn
conda install -c anaconda jupyter 
conda install matplotlib
conda install pillow 
pip install h5py
pip install pydot-ng
pip install --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.2.0-cp35-cp35m-win_amd64.whl
pip install keras
```



- Download the next linguistic resources from the web
  - Sentiment corpus: [https://s3-eu-west-1.amazonaws.com/text-mining-course/aclImdb.zip]()
  - ATIS database: [https://s3-eu-west-1.amazonaws.com/text-mining-course/atis.zip]()
	- Glove embeddings: [https://s3-eu-west-1.amazonaws.com/dl-finance-course/glove.6B.100d.txt.zip]()
