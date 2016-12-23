# Introduction: ML大体的分类

> In this class we'll talk about supervised learning. And the idea is that, in supervised learning, in every example in our data set, we are told what is the "correct answer" that we would have quite liked the algorithms have predicted on that example. Such as the price of the house, or whether a tumor is malignant or benign. We also talked about the regression problem. And by regression, that means that our goal is to predict a continuous valued output. And we talked about the classification problem, where the goal is to predict a discrete value output.



- ## 监督学习

  > In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function. In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

  - ### 回归问题（预测一个连续值的输出）

    - right answers given，以根据面积-房价数据集预测房价为例  需要部分数据集已经有正确答案、可以给出某一平米房屋对应房价的正确答案

    > Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.

    > We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

  - ### 分类问题（discrete valued output 离散的变量）

    - 肿瘤大小与良性/恶性的关系（0 or 1）


    - SVM（支持向量机处理无限多的特征）

    ​



- ## 非监督学习

  ##### - 这里有一个数据集，你能找出它的结构吗？比如这个数据集是不是形成了两个聚类？是不是有回归关系？

  > Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.
  >
  > We can derive this structure by clustering the data based on relationships among the variables in the data.
  >
  > With unsupervised learning there is no feedback based on the prediction results.

  - ### 聚类算法（Clustering algorithm）

    - 例如Google新闻专题，将不同网站关于同一新闻的报道进行聚类形成专题
    - 大三时间序列分析课里做过一个收入水平的聚类分析，根据数据的特征将数据分为8类并对每一类的特征进行说明
    - 可以对用户数据进行聚类分析，形成不同的用户画像，实现精准的推荐和营销

  - ### 非聚类的问题，例如鸡尾酒会 Cocktail party problem algorithm

    - 可以对语音做处理，分离叠加在一起的声音

  ​

#### 

