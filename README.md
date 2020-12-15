#########################################################################

# README

#########################################################################

This is a project on RCNs(Rule Constrained Networks). Basically RCNs are neural networks which are constructed by modifying the pretrained Deep Neural Network for a particular task.

The main purpose of RCNs are to achieve some sort of explainability or interpretability without sacrificing accuracy of the model by much. RCNs are provided with the input data and a set of decision rules on the feature representation of the data and they are trained to predict most suitable rule for every data and from the prior class probabilities of the rules we can infer the class label from the rule predicted.

For detailed description and explaination of RCNs, refer to the paper in the "Paper" folder titled "Deep Neural Network Constrained By Decision Rules"


## DATASETS

_All dataset files can be found in the data folder_

First we start off our work by 2 very simple datasets
1. Heart Disease UCI dataset
1. Breast Cancer Wisconcin dataset

As these are very basic datasets, we will not do much preprocessing on them and will just train simple Deep Neural Networks on them and then convert the DNNs into RCNs 
