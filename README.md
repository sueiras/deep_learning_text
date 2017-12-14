# Deep learning use cases

Included 4 uses cases:

1.- Language model at character level

2- Word tagging

3.- Sentiment analysis with Recurrent Neural Networks

4.- Sentiment analysis with Convolutional Neural Networks



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

# Download the next linguistic resources from the web:
  - Sentiment corpus: https://s3-eu-west-1.amazonaws.com/text-mining-course/aclImdb.zip
  - ATIS database: https://s3-eu-west-1.amazonaws.com/text-mining-course/atis.zip
  - Glove embeddings: https://s3-eu-west-1.amazonaws.com/dl-finance-course/glove.6B.100d.txt.zip
  - Quijote: http://www.gutenberg.org/cache/epub/2000/pg2000.txt
  - Pretrained language model for Quijote: https://s3-eu-west-1.amazonaws.com/text-mining-course/text_generation_model1024.h5
