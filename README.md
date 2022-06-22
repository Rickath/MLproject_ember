# ML project on EMBER dataset

This repository is just a project to toy with machine learning applied to malware detection, using the EMBER dataset, for a machine learning course

## Dataset

The EMBER dataset can be found [there](https://github.com/elastic/ember). Ember package should be installed and 2018 dataset with v2 features should be used

## Notebooks

* Approche_ML_Linear contains a notebook with different linear machine learning techniques (Decision tree, bagging tree, random forest...) using scikit learn
* Approche_Deep_Learning_scaled contains deep learning techniques (ffn and cnn) and in he end a comparison between best linear and deep learning methods

## Saved files

* Pickles of linear models are saved to be easily loaded for reproducibility purposes. For KNN, prediction scores and prediction for threshold > 0.5 have been saved
* Keras save of neural networks are also included
* Pickles of neural networks history are included (for accuracy/loss by epochs graphs)
