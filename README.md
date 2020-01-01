# -
作业说明
数据来源：
本次作业所需的数据集可从https://www.synapse.org/#!Synapse:syn2623706/wiki/ 上下载。文件名称为GSE39582_frma_expression.tsv，（注：在该文件中行代表特征，列代表样本，包含54675行特征。）

标签来源：
本次作业所使用的标签从上述网站中下载，标签文件名称为clinical_molecular_public_all.txt，将该文件打开后，样本标签的列标题为CMS,需将该列提出作为样本的真实标签，（注：只需提取类别为CMS1,CMS2,CMS3,CMS4的样本。）

特征来源：
      本次作业所使用的所有特征均可从http://icdtools.nenu.edu.cn/deepcsd网页中的DOWNLOAD页面进行下载，特征文件类型为.Txt,该文件包含实验所需的所有特征名称。读者需要在上述expression数据集中提出相应的特征提取出来进行实验。(注：类别为.h5文件是网站作者已经训练好的深度学习模型，如需使用该模型，需将特征按照Txt文件中的顺序进行排列。)

作业具体内容：
本次作业是一个4分类问题，任务为将每个样本进行正确的分类。具体为：
1.从sklearn调用机器学习包，分析不同的机器学习方法的结果
2.构建深度学习网络，分析结果
