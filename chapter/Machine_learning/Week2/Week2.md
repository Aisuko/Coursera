# Multivariate Linear Regression

## Multiple Features
* Linear regression with multiple variables is also known as "multivariate linear regression"
* theta 转置*x：
  * On the Multiple Features,(x0~xn) * (theta0 ~ theta n)= theta转置*x
  * Multivariate linear regression

## Gradient Descent for Multiple Variables
* When n>=1(n is Multiple Variables), Beaucals x0=1,so, Gradient descent function same as (n=1) gradient descent

## Gradient descent 实用技巧

### Feature Scaling(特征缩放)
* 如果问题的多个特征都在同一个相近的范围内，梯度下降就能更快的收敛
* 实用特征缩放消耗掉范围值，使连个特征在同一个量级范围

### Mean normalization(均值归一化)
* (特性x-x的average)/(max-min),让特征具有为0的平均值，梯度下降就能更快的收敛

### Gradient descent (learning rate theta)
* How to choose learning rate
* To summarize:
  * if lr(learning reate) is too small: slow convergence
  * if lr is too large: may not decrease on every iteration anf thus may not converge

### Features and ploynomial regression(使用线性方法来拟合多项式回归）
* Polynomial Regression
* Chioce of features
  * 使用特征缩放，缩放所有特性到相近范围内

# Computing Parameters Analytically

## Normal Equation
* In the "Normal Equation" method, we will minimize J by explicitly taking its derivatives with respect to the θj ’s, and setting them to zero. This allows us to find the optimum theta without iteration
* There is no need to do feature scaling with the normal equation

## Normal Equation Noninvertibility