# Exam Solutions

**_Explain what are (1) the bias and (2) the variance terms in the expected generalisation error,
 and explain (3) the bias-variance dilemma. (6 marks)_**

1. The bias is the expected generalisation error averaged over machines trained on all possible data sets of a given size
2. The variance measures the expected variation from the average machine due to the fluctuations caused by using a finite training set 
3. The bias-variance dilemma is that a simple machine is likely to have a high bias but low variance while a complex machine will have a low bias but high variance

**_Briefly describe the Bagging (bootstrap aggregating) algorithm, describe why it works, and give an example of a machine learning algorithm that uses it._**

- Bagging is an ensemble learning technique that averages over a number of different machines. 
- Each machine is trained on a different data set. 
- The datasets are created by bootstrapping. 
- That is, we sample the training set with replacement to create new training sets. 
- We train a learning machine on each data set and then take the mean response of the set of machines. 
- This reduces the variance (in the bias-variance dilemma) through averaging over different datasets, thereby improving generalisation performance. 
- random forest algorithm uses bagging which averages decision trees.

**_Explain the difference between a discriminative probabilistic model and a generative model. Describe the advantages of each._**

- A discriminative probabilistic model predicts the probability of a target y given features x, i.e. P (y|x). 
- In generative models we generate both the target and the features using the joint probability P (y, x). 
- Discriminative models are usually easier as we don’t need to model the process of generating features. 
- Generative models can provide a more accurate model and can be used in many different ways.


<!--stackedit_data:
eyJoaXN0b3J5IjpbODkzODIzMDc4LC0yMTEyNDY1MDU4XX0=
-->