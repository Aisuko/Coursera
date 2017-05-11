# 通过已掌握的算法对假设函数进行评估

* Evaluating a Hypothesis
  * Typically, the training set consists of 70 % of your data and the test set is the remaining 30 %
  * 
* The test set error
  * For linear regression

  * For classification

# 诊断算法


# Bias(偏差)与Variance(方差)两种问题

* 提高算法的性能表现
  * 如果你的算法处于高偏差情况， 那么你的训练集误差会很大吗因为你的假设不能很好的你和训练集数据
  * 当你处于高方差的问题时，你的训练误差通常都会很小， 并且远远小于交叉验证误差 

## Learning Curves(学习曲线) - 讨论在High bias 和 High variance 情况下的联众误差集与训练样本数量m的关系

* J(cv) 交叉验证误差集
* J(training) 测试误差集

* High bias
  * 当算法处于高偏差的情况下的时候，增加训练集的样本数量对两种误差集曲线没有效果
* High variance
  * 在算法处于高方差的情况下，增加训练样本的数量，会使交叉验证误差集曲线下降，证明对算法误差有用

