# Data-castle 文本分类
## 工作流程
1. 问题定义
2. 获取训练集和测试集
3. 数据分析
4. 数据预处理
5. 建模，做出预测解决问题
6. 可视化，报告，表现问题解决方案
7. 提交结果
## 题目定义
题目为一个长文本分类任务，通过长文本数据正文，预测文本对应的类别
## 获取训练集和测试集
下载数据包含2个csv文件，train_set.csv和test_set.csv
## 数据分析
无空值、异常值等情况，数据已经脱敏无需脱敏处理
数据每一行对应一篇文章，每条记录都包括字article、词word两个特征属性和ID属性，训练集中的数据具有标签属性class
字、词属性取值均为Object型数字列表，列表中每一个数字对应一个字或词
## 数据预处理
1. 按数据3-7分，随机种子2019，将训练集拆分为训练集和验证集
2. tfidf
3. word2vec词向量
4. 特征工程
## 建模，做出预测解决问题
1. 使用tfidf+单机器学习模型
2. 词向量+深度学习
3. 模型融合
