# Motivations
* 神经网络是一种机器学习的算法

## Non-linear Hypotheses
* 首要讨论目标是表层结构
* 解决机器学习问题需要以来很复杂的非线性分类器，而且需要大量特性，进行复杂的计算

## Neurons and the Brain
* 现代机器学习最有效的算法

# Neural Networks
* Model Representation One
  * 怎么表现神经网络
  * 激励函数表示为g(z)
  * Example: layer 1 has 2 input nodes and layer 2 has 4 activation nodes. Dimension of Θ(1) is going to be 4×3 where sj=2 and sj+1=4, so sj+1×(sj+1)=4×3
  * Neural Model
    * Logistic unit
    * 非输入输出层都叫做隐藏层
  * Other network archiitectures
* 人工增加的x0=1,被称作偏置单位，偏置神经元
* 关于神经网络的术语
  * 一个神经元，一个有S型函数或者逻辑函数作为激励函数的人工神经元
  * 激励函数/逻辑激励函数只是对类似非线性函数g(z)的另外一种术语称呼，theta为模型参数或者叫模型权重
  * 激励是指由一个具体神经元读入计算并输出的值
  * 被矩阵化的theta上标(j)将成为一个波矩阵，控制着从本层到下各层的作用

* Model Representation Two
  * 计算隐藏层的激励值
  * n维度矩阵/向量的表达方式R
  * 矩阵/向量运算（矩阵向量乘法）表示符号，大写的theta
  * 前向传播

# Applications

## Examples and Intuitions
* 神经网络单个神经元在计算AND 和 OR 逻辑运算发挥作用
* And function
* Or function

## Neural Network can compute complex non linear hypothesis
* 
