A/B Split Testing Tools https://vwo.com/blog/15-free-ab-split-testing-resources/ 
深度好文：

https://vwo.com/ab-testing/?utm_source=google&utm_medium=paid&utm_campaign=mof_ca_search_category_ab-testing_educational&utm_content=483088283016&utm_term=ab%20testing&gclid=CjwKCAiAi_D_BRApEiwASslbJ-xT-VSOrb9BmGktXKSsL-g8ZdqoT5Fe-h5nZepF6VvxsFlEgcv4vhoChzgQAvD_BwE

https://zhuanlan.zhihu.com/p/34061065

# Hypothesis test

1.给出null hypo(null hypothesis或其临界的意思都是没用，没影响，无差别)和alternative hypo

2.根据备择假设确定检验方向：

  备择假设含≠则为双尾；含<或>则为单尾，含<为左尾，含>为右尾

3.判断抽样分布类型

  是否近似正态分布
 
4.确定检验类型及检验统计量：取决于样本量和总体服从的分布

  样本大小>=30: z-test
  
  < 30,近似服从正态分布，总体标准差已知 z-test
  
  < 30,近似服从正态分布，总体标准差未知 t-test

  < 30,不服从正态分布：不能用Z检验和T检验
  
5.给出显著性水平alpha

# A/B Testing

A/B testing in marketing allows you to make the most out of your existing traffic.

CRO: Conversion Rate Optimization

Industry application:

- Landing-page optimization

- Ad creative optimization 如何选择广告的形式和内容。当我们决定将要进行广告展示，以及确定了广告的价格后，在这个广告位上选择放置什么广告呢？我们需要对大量的决策进行测试，选出正确的广告创意组合。

⚠️要解决的问题：

- 怎样验证对照Control Group和实验组Treatment Group的用户的行为是无偏差、完全相同的

- 当两个组的用户行为不完全相同时（例如分组不够随机或者组内用户数量较小时），该如何设计AB测试以实现期望的验证结果

- 当用户基础行为受其他因素影响发生整体变化了呢？例如季节、时间波动、热度等因素影响下，怎样更好的剔除干扰来评估结果



一个完整的A/B testing：

1、分析现状，建立假设：分析业务，确定最高优先级的改进点，作出假设，提出优化建议。

2、设定指标：设置主要指标来衡量版本的优劣；设置辅助指标来评估其他影响。

3、设计与开发：设计优化版本的原型并完成开发。

4、确定测试时长：确定测试进行的时长。

5、确定分流方案：确定每个测试版本的分流比例及其他分流细节。

6、采集并分析数据：收集实验数据，进行有效性和效果判断。

7、给出结论：①确定发布新版本；②调整分流比例继续测试；③优化迭代方案重新开发，回到步骤1。
