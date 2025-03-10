# Linear Models for Regression

本次主要讨论线性回归的问题, 主要内容围绕ESL的第三章展开.

给定一组数据(含有干扰项)$D_n=\{x_i,y_i\}_{i=1}^n$, 其中$x_i\in\mathbb{R}^p$是输入, $y_i\in\mathbb{R}$是一个**连续**的输出. 我们希望通过观测得到的数据, 获得对$x$与$y$之间的对应关系：即通过$D_n$给出$y=f(x)+\varepsilon$的一个估计$\hat{f}$, 也就是一个**回归**.

## Linear Regression

首先讨论最简单的, 线性回归.
我们假定如下的回归模型:
$$y_i=\sum_{j=1}^p x_j\beta_j$$
其中$\beta_j(j=1,2,\cdots,p)$是模型参数, 关于参数是线性的模型称为**线性模型**.

