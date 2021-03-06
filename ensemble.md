## Decision Tree
**Removing Variance By Averaging**
- We can reduce the variance and improve our generalisation error by averaging over different models
- A number of different techniques for doing this that go by the name of ensemble methods or ensemble learning

Steps:
1. Decision trees build binary tree to partition the data $D = {(x, y)}$, into _leaves_.
![](https://github.com/werdnakof/Advanced-Machine-Learning-Notes/blob/master/images/ensembleLearning1.png?raw=true)
2. Each decision rule depends on a single feature
3. The proportion of the data points $p_c(L)$ in leaf $L$ belonging to class $c$ is:
	$$p_c(L) = \frac{1}{|L|} \sum_{(x, y) \in L} [y = c]$$
	(where $[y = c] = 1$ if $y = c$ and $0$ otherwise )
4. At each step rule is chosen that maximise the "_purity_" of the leaf.

Two different purity measures $Q_m(L)$











<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcwMDIxMzc0MSwtMTk0NTY1MDM2OV19
-->