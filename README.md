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

内容：使用百度贡献的DuReader_robust数据集，完成MRC任务中的答案抽取项目，在给定的context下，通过模型标注正确答案的
起始和终止位置，找到question对应的正确答案；

模型：用的是中文预训练集成模型，子模型分别是RoBERTa-wwm-ext、BERT-wwm-ext和BERT-wm；

结果： F1: 85.115和EM: 74.312；
    
