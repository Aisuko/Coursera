# Classification and Representation

## Classification
* To attempt classification, one method is to use linear regression and map all predictions greater than 0.5 as a 1 and all less than a0.
* This method doesn't work well because classification is not actually a linear function.

## Hypothesis Representation
* Logistic Regression Model(函数g())
  * Sigmoid function
  * Logistic function
* `假设函数(0.7=P(y=1|x;theta)` --给定特性x,y等1的概率的参数是theta

## Decision Boundary
* 理解逻辑回归函数在计算什么
* 决策边界是函数的一个属性，函数的特性是属性的参数

## Non-linear decision boundaries
* 多项式回归，特征变量，得到复杂的决策边界

# Logistic Regression Model

## Cost Function
* 分y=0和y=1两种情况

## Simplified Cost Function and Gradient Descent

* 将cost function的两种情况压缩在一起，形成一个公式
* Gradient Descent
  * 最后对函数进行矢量化

# Multiclass Classification:One-vs-all
* We are basically choosing one class and then lumping all the others into a single second class. We do this repeatedly, applying binary logistic regression to each case, and then use the hypothesis that returned the highest value as our prediction
* To summarize:
  * Train a logistic regression classifier  function for each class to predict the probability that y = i
  * To make a predictioin on a new x, pick the class that hypothesis function

The problem of overfiting
* 解决办法
  * 减少选取变量的数量（使用模型算法，算法是为了自动选择，采用哪些特征变量）
  * 正则化