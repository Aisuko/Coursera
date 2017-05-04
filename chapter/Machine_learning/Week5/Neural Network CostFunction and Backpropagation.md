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
* 计算矩阵维度的表达式
* 矩阵全部展开为向量，被叫做DVec
* 从向量返回到矩阵表达式thetaVec
  For example:
  D1 is a 10*6 matrix and D2 is a 1*11 matrix, Set DVec = [D1(:);D2(:)]; D2 back from DVec?

  reshape(DVec(61:71),1,11)
