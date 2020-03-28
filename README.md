# WeiboTextClassification

一个简单的微博文本分类示例，使用kNN与基于PyTorch的TextCNN算法进行分类。

采用已分好词的语句文件(样例文本见ExampleText.txt)作为数据集，预训练词向量来自https://github.com/Embedding/Chinese-Word-Vectors，可以在Word2vec - Weibo 微博 - Word类别下下载。

使用顺序:

filePreprocessing.ipynb

kfold.ipynb

dataAnalysis.ipynb

kNN.ipynb

TextCNN.ipynb



kNN分类准确率 75%

TextCNN分类准确率 85%

