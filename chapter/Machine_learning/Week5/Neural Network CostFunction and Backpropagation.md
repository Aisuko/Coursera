# Cost Function and Backpropagation

## Cost function in Neural Network
* 公式

## Backpropagation Algorithm
* 反向传播算法

## 剖析反向传播算法
* 因为反向传播算法难度比较大，之后慢慢剖析
* 正向传播(Forward Propagation)
  * 节点delta等于（本节点所有权重*来源delta的值）

## 使用反向传播算法
* 进行参数的矩阵表达式和向量表达式之间的转换
  function [jval, gradientVec] = costFunction(thetaVec)
* 矩阵全部展开为向量，被叫做DVec
* 从向量返回到矩阵表达式thetaVec
  For example:
  D1 is a 10*6 matrix and D2 is a 1*11 matrix, Set DVec = [D1(:);D2(:)]; D2 back from DVec?

  reshape(DVec(61:71),1,11)
## 梯度检验(Gradient Checking)
* 检查算法中的bug
* 右边导数
* 双边导数（准确率更高）
* What is the main reason that we use the backpropagation algorithm rather than the numerical gradient computation method during learning?
  * The numerical gradient algorithm is very slow