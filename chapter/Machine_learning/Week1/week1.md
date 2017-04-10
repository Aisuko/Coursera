## Indroduce
* 在复杂的现实场景中，编程只能让机器来完成一些基础工作，例如A到B的最短距离。但是在大多数情况下，我们并不知道如何显示地编写人工智能程序

## Machine learning algorithms

Supervised learning
* Supervised learning refers to the fact that we gave the algorithm a data set in which the "right answers" were given.(对训练集中的每个数据都有正确答案)
  * Regression problems belongs to supervised learning(回归问题指：预测一个连续值的输出)
  * Classification problems

Unsupervised learning
* Unsupervised learning allows us to approach problems with little or no idea what our results should look like
  * 无监督学习中，(聚类算法)把数据集分成多个不同的聚类，事先我们并不知道哪些类型，因为对于这些数据样本来说，我们没有给算法一个正确答案，这就是无监督学习
  * 应用于组织大型计算机集群、社交网络的分析

Model and Cost Function
* Model Representation 
  * The function h is called a hypothesis
  * When the target variable that we're trying to predict continuous, such as in housing example, we call the learning problem a `regression` problem
  * when y can take on only a small number of discrete values(such as if ,given the living area,we wanted to predict if a dweling is a house or an apartment, say), we call it a `classfication` problem
* Cost Function
  * We can measure the accuracy of our hypothesis function by using a `cost function`
  * This function is otherwise called the "Squared error function", or "Mean squared error"
  * i表示数据x在训练集中的位置
  * 1/2m m表示训练集个数，此项为了减小误差
  * Thus as a goal, we should try to minimize the cost function. In this case, θ1=1 is our global minimum.



## Linear Regression with One Variable


## Parameter Learning

* Gradient Descent
* Gradient Descent For Linear Regression

