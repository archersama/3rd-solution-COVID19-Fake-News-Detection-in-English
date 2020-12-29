
<div align=center>
<img src="background.png" alt="background"/>
</div>

[Constraint@AAAI2021 - COVID19 Fake News Detection in English](https://competitions.codalab.org/competitions/26655)

第三名解决方案，包含全部代码、评测论文以及我们搜集的额外数据和官方数据.

## 赛题描述：
英文COVID19假新闻检测-此子任务重点在于用英语检测与COVID19相关的假新闻。数据源是各种社交媒体平台，例如Twitter，Facebook，Instagram等。给定社交媒体帖子，共享任务的目的是将其分类为假新闻或真实新闻。

### 任务分类：
* 文本分类

## 数据说明：

`Constraint_English_Train.xlsx`是官方给的训练样本示例，为xlsx数据格式。数据格式如下：

|id|tweet|label|
|---|---|---|
|0|Alfalfa is the only cure for COVID-19.	|0|


> **注意：提供的样本示例`train_data.sample`仅为帮助理解赛题以及调通代码，由于样本示例仅为两万行，因此构造的出来的特征意义不大（数据严重泄露）。**

## 模型架构：

在本文中一共使用了两个模型,分别基于双向LSTM和transformers架构

1.双向LSTM






2.transformers





------------------

感兴趣就给个star吧:-D

**最后感谢两位队友@Han和@hcccccccc**
