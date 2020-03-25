## 数据的探索性分析（EDA）

探索性数据分析（Exploratory Data Analysis，简称EDA）

用各种方法（其实大部分是统计方法）探索数据的特点、寻找数据的规律。

#### 1.EDA的目标

- 熟悉数据集
- 了解变量间、变量与预测值之间的相互关系
- 初步确定可使用的模型、算法

#### 2.EDA步骤

1. 数据总览

2. 判断数据的缺失和异常

3. 了解预测值的分布

   - 各特征的总体分布概况
   - 查看峰度和偏度
   - 查看预测值的具体频数

4. 特征分类

   - 数字特征

     - 相关性分析
     - 查看几个特征的偏度和峰度
     - 可视化：
       - 每个数字特征的分布
       - 数字特征之间的相互关系
       - 多变量互相回归关系

   - 类别特征

     - unique分布
   - 可视化：
     - 箱形图
     - 小提琴图
     - 柱形图
     - 特征的每个类别频数


5. 用pandas_profiling生成数据报告

#### 3. [源代码](https://github.com/Zoenamed/Learn-Data-mining/blob/master/2.EDA/Task2%20EDA.ipynb)

#### 4. 补充

##### 			[a. 零基础统计入门](https://github.com/Zoenamed/Learn-Data-mining/tree/master/2.EDA/%E9%9B%B6%E5%9F%BA%E7%A1%80%E7%BB%9F%E8%AE%A1%E5%85%A5%E9%97%A8)

##### 		[b. scipy.stats中常用分布介绍](https://blog.csdn.net/pipisorry/article/details/49515215?depth_1-utm_source=distribute.pc_relevant.none-task&utm_source=distribute.pc_relevant.none-task)

##### 		[c. seaborn统计数据可视化](https://github.com/Zoenamed/Learn-Data-mining/blob/master/2.%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90/seaborn%E7%BB%9F%E8%AE%A1%E6%95%B0%E6%8D%AE%E5%8F%AF%E8%A7%86%E5%8C%96.ipynb)

