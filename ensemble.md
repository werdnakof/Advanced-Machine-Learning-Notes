## Decision Tree
**Removing Variance By Averaging**
- We can reduce the variance and improve our generalisation error by averaging over different models
- A number of different techniques for doing this that go by the name of ensemble methods or ensemble learning

Steps:
1. Decision trees build binary tree to partition the data $D = {(x, y)}$, into _leaves_.
2. Each decision rule depends on a single feature
3. At each step rule is chosen that maximise the "_purity_" of the leaf.

![](https://github.com/werdnakof/Advanced-Machine-Learning-Notes/blob/master/images/ensembleLearning1.png?raw=true)





<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNzkyNzI4NzYsLTExNzU4MTg1NzcsLT
MyNDM0MTI0OSwxOTQwMDM5ODE3LDE3MjU5MTk5MjRdfQ==
-->