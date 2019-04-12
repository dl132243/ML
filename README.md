# KNN
一.KNN一般流程：
1.收集数据： 可以采用任何方式
2.准备数据：整理计算距离所需要的数值，最好是结构化的数据格式
3.分析数据：可以使用任何方法
4.训练算法：此步骤不适合KNN算法
  KNN伪代码思想：
      对未知类别属性的数据进行如下操作：
      （1）计算已知类别的点到未知类别点的距离
      （2）按照距离递增的数据进行排序
      （3）选取与当前数据点距离最小的前K个点
      （4）确定前K个点标签出现的次数
      （5）返回前K个点出现次数最多的标签作为当前数据的标签
5.测试算法： 计算算法的错误率
6.使用算法
二.

