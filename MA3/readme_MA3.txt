MA3_ANNforClassification.ipynb:

Here the main goal is: To understand how common data like signals and images are represented as one/multi-dimensional numerical arrays and tensors in order to be useful for FANN training. Learn how to solve large-scale classification problems using FANNs in PyTorch

At the end of each file there are some reflections about each procedure.

There are two tasks in this notebook.

Task A: Two-class Signal Classification by FANNs

We Use the code in "help_code_ann_for_classification.py" to get access to the signal dataset inside the zip file folder: "1d_signal_data" :
#each "record" represents a signal and it contains a tensor with 500 csv values and a number 0 "normal" or 1 "abnormal"

Then we explore it to find answers to the following: How many signals does the dataset contains and how long (in terms of time points) is each signal?

Plot some of the signals in the dataset with their labels (normal/abnormal) shown in the plot title. 

We train the NN and finally plot Cost-entropy and Accuracy performance.

Fro more details check main readme.md
