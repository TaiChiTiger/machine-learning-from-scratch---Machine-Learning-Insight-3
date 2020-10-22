# 从头编写机器学习模型-机器学习洞察3
# Machine Learning From Scratch - Machine Learning Insight 3



## 模型
模型文件命名规则：模型名+任务+（算法名/API）+数据集名

其中“任务”可以是回归、分类、聚类和降维等，“（算法名/API）”分为三种情况：1. 如果为空，则表示模型是使用本身特有的算法从头编写的；2. 如果有算法名，如"with_gradient_descent"，则表示模型是使用该算法从头编写的；3. 如果有API名，一般是sk，代表scikit-learn，也可以是pytorch和tensorflow，则表示模型是调用相应的API完成的任务，这是为了验证从头编写模型所得的结果，或者熟悉API使用。

按字母排序：
- [x] [AdaBoost](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/adaboost)
- [ ] [Bagging](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/bagging)
- [x] [Best Subset Selection](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/best-subset-selection) 
- [x] [Cubic Splines](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/cubic-splines)
- [x] [Fisher Disciminant Analysis](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/fisher-disciminant-analysis)
- [x] [Forward Stagewise Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/forward-stagewise-regression)
- [x] [Kernel Ridge Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/kernel_ridge_regression)
- [x] [L2Boosting](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/l2boosting)
- [x] [Lasso Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/lasso-regression)
- [x] [Least Absolute Deviation Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/least-absolute-deviation-regression)
- [x] [Least Angle Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/least-angle-regression)
- [x] [Linear Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/linear-regression)
- [x] [Logistic Regression](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/logistic_regression)
- [x] [LogitBoost](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/logitboost)
- [ ] [Nystroem Approximation](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/blob/main/notebooks/models/nystroem-approximation/nystroem_approximation.ipynb)
- [ ] [Orthogonal Matching Pursuit](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/orthogonal_matching_pursuit)
- [x] [Quadratic Disciminant Analysis](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/quadratic-disciminant-analysis)
- [ ] [Random Fourier Feature](https://github.com/TaiChiTiger/machine-learning-from-scratch---Machine-Learning-Insight-3/tree/main/notebooks/models/random-fourier-feature)


## 数据
回归：
- 1维线性数据集
- 1维非线性数据集
  训练集：200个样本；测试集100个样本
  
 分类：
 - 1维线性数据集
 - 2维线性数据集
 - 2维非线性（混合）数据集


## 计划
- 增加合成的混合3类数据
- 增加贝叶斯方法
