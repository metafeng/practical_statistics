# 实用统计

了解如何将推论统计和概率应用于重要的现实场景，例如分析A / B测试和构建监督学习模型。

- 01：[描述性统计 - 第一部分](01.descriptive_statistics_part1.ipynb)，介绍了数据类型，中心度量和统计表示法的基础知识。

- 02：[描述性统计 - 第二部分](02.descriptive_statistics_part2.ipynb)，介绍了与定量数据相关的离散程度，形状和异常值的度量。将预先了解推论统计数据。

- 03：[概率](03.probability.ipynb)

	- 概率使用硬币和模具获得概率的基础知识。
    - 二项分布，了解概率中最受欢迎的分布之一 ：二项分布
    - 条件概率，并非所有事件都是独立的。了解依赖事件的概率规则
    - 学习所有统计学中最受欢迎的规则之一：贝叶斯规则
	
- 04：[正态分布理论](04.normal_istribution_theory.ipynb)

	- 正态分布理论，学习从硬币翻转到正常分布的数学背后的数学知识
    - 学习大数法则和中心极限定理
	- 了解所有关于置信区间和假设检验的基础：抽样分布
	- 学习放回抽样：自助法
	
- 05：[置信区间](05.confidence_intervals.ipynb)，了解如何使用采样分布和引导为任何感兴趣的参数创建置信区间。

  - 利用自助法和抽样分布的知识，创建任一总体参数的置信区间
  - 构建总体平均数和均数差的置信区间
  - 如何使用 python 嵌入函数构建置信区间

- 06：[假设检验](06.hypothesis_testing.ipynb)，学习在假设检验中创建和分析结果的必要技能。

  - 如何设置假设检验
  - 学习了 I 类错误和 II 类错误
  - 如何根据 p 值做出决定
  - 邦弗朗尼(Bonferroni)校正

- 07：[案例研究：A / B测试](07.A_B_tests.ipynb)，通过一个案例研究，了解A / B测试如何为一家名为Audacity的在线教育公司工作。

  - 分析漏斗模型，从点击率、注册率、平均浏览时长、平均教室逗留时长、完成率这5个维度进行测试
  - 总结A/B 测试的难点

- 08：[回归](08.regression.ipynb)，使用python拟合线性回归模型，以及理解如何解释线性模型的结果。

  - 学习了斜率、截距和决定系数的解释方法
  - 可视化简单线性回归的最常用方法为散点图
  - 用 Python 的 **statsmodels** 库来找到决定回归线的截距和斜率
  - 分析钻石重量以及相应以美元为单位的钻石价格、预测波士顿房价

- 09：[多元线性回归](09.multiple_linear_regression.ipynb)，使用python拟合线性回归模型，以及理解如何解释线性模型的结果。

  - 如何在 python 里创建多元线性回归模型
  - 如何编码虚拟数据并解释相应的系数
  - 学习了模型选择和特征工程技巧
  - 学习了交叉验证

- 10：[Logistic回归](10.logistic_regression.ipynb)，学习在python中应用逻辑回归模型。学习解释结果并了解模型是否适合。

  - 如何使用 python 来实现逻辑回归，用 statsmodels 和 sklearn 包来预测二元分类反应值
  - 如何解释 statsmodels 逻辑回归输出的系数
  - 如何用多个指标来评估模型效果
  - 如何在 python 里评估模型拟合效果

- [项目：分析A / B测试结果](https://github.com/hufe09/practical_statistics/blob/master/A-B-testing/A-B_testing_of_%20e-commerce_website_operations.ipynb)
- 分析电子商务网站运行的A / B测试的结果。目标是通过帮助公司了解他们是否应该实施新的页面设计。

