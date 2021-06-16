# LFNNXGB2N
0.Data_pp.zip 基于Paper1 Weakly-supervisedMulti-taskLearningforMultimodalAffectRecognition
              基于Paper2 LearningModality-SpecificRepresentationswithSelf-SupervisedMulti-TaskLearningforMultimodalSentimentAnalysis
整合的特征提取工具包，用以MOSI/MOSEI/SIMS的实验数据预处理
1.链接: https://pan.baidu.com/s/1RPyNyeVxKWdmhSXoTARWdQ 提取码: fgkp MOSI/MOSEI/SIMS包含提取好的数据集
2.LF_DNN.zip 基于https://github.com/rhoposit/MultimodalDNN 结构设计了包含训练、验证以及特征图提取功能的LF_DNN框架，并在MOSI、MOSEI、SIMS上完成训练分类+回归任务
3.LF_DNN-XGB.zip 基于LF_DNN框架设计了LF_DNN-XGB框架并分别在并在MOSI、MOSEI、SIMS上完成训练分类+回归任务
4.XGBdNN.zip 基于LF_DNN-XGB框架，设计了基于XGBoost树模型的树模型蒸馏算法，包含整体蒸馏、分组蒸馏以及多任务蒸馏三种方式。蒸馏后的框架在SIMS上完成验证，未调参情况下精度下降在1~2%。
