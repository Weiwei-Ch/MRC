# MRC
MRC机器阅读理解笔记和集成代码

一、机器阅读理解笔记包括：

1.MRC简介

2.a.Glove介绍；

  b.Attention机制；
  
3.a.R-Net模型；

  b.FusionNet模型；
  
4.Transformer概览；

5.ERNIE简介(百度)

6.RetroReader概览(交大)

7.模型集成

8.a.MRC模型总结；

  b.MRC模型区别和改进；
  
二、附MRC集成模型代码运行结果，包括集成结果以及单独模型运行结果

模型题目：答案抽取项目  

内容：此为百度2020语言与智能技术竞赛中机器阅读理解任务。使用DuReader_robust数据集，完成MRC任务中的答案抽取项目，在给定的context下，通过模型标注正确答案的
起始和终止位置，找到question对应的正确答案；

模型：此项目用的是集成方法，集成了三个基于Bert的中文预训练模型，分别为RoBERTa-wwm-ext、BERT-wwm-ext和BERT-wm；

结果： F1: 85.115和EM: 74.312（高于竞赛排行榜中第一名提交的结果);

集成模型代码见

比赛网址：https://aistudio.baidu.com/aistudio/competition/detail/28?isFromCcf=true

子模型下载地址：本人用的是Pytorch版本，https://github.com/ymcui/Chinese-BERT-wwm
    
