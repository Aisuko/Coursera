# Have a lot of fun learning about machine learning. 

[week1](Machine_learning/week1/week1.md)


## 监督学习 （回归问题属于监督的一种）
训练集
在数据集中的每个数据都给出了正确的答案  
回归：根据之前的数据预测出一个准确的输出值  
回归问题
* 回归：意味着要预测这类连续值属性的种类/意指预测一个连续值的输出

分类问题：预测离散值的输出

算法需要使用多个属性，处理多个特征
 
* Example

邮件分类、有无糖尿病、良性恶性肿瘤

* 线性回归模型
 * 需要选择参数来和函数进行匹配

* 单变量线性回归 
* 线性回归函数
 * (x,y)代表训练集
 * M代表训练集样本数  
 * hypothesis函数 hθ(x)=θ1*x 线性函数(是假设)
 * x(i),y(i)表示在 i上的样本x与y
 * 在线性回归中，我们需要解决最小化问题(hθ(x)-y)平方
 * 对i=1到i=m的样本进行求和
 * 也就是预测值与实际值差的平方的和
 * 简单来说就是求求和值的1/2m
 * minisize
 * 代价函数(J(θ1))，又叫做平方误差函数 ：解决回归问题 [公式](https://www.coursera.org/learn/machine-learning/supplement/nhzyF/cost-function) 多用来解决回归问题
 * 根据假设函数hθ(x) 推导线性回归目标函数J(θ1)的值 minimize = J(θ)

* 轮廓图

* 矩阵 维度使用row and columns 表示、 向量 columns == 1 的矩阵
 * 多元线性回归函数，使用矩阵与向量的公式来表达

* 参数学习
 * `梯度下降算法`：可以使代价函数J最小化
  * `特征缩放`：使问题的多个特征都处在同一个范围内，使梯度下降加快收敛
  * `均值一体化`：让特征具有为零的平均值


* size of house > h > Estimated price


## 无监督学习（判断数据集中的包含的聚类，数据集没有明显的特征分别）没有给算法正确答案

聚类算法应用场景：基因片段分析、鸡尾酒party算法

* Example

市场细分、Google新闻

## 编程环境

Octave

