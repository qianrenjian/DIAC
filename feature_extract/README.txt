a.两个语句的长度上的差距.

b.两个语句的编辑距离.

c.两个语句的n-gram相似性的特征.

d.两个语句的Jaccard相似度。

e.两个语句的词向量组合的相似度.主要是根据全部训练集做语料库使用word2vec训练的词向量计算的两个语句的词向量的组合相似度。

h.两个语句神经网络编码的曼哈顿距离相似度和余弦相似度主要是根据两个语句的预训练词向量输入经过LSTM进行编码计算出两个语句的语义向量的曼哈顿距离和余弦相似度作为最后的机器学习的分类模型特征之一。

i.两个语句的神经网络编码的match vector形式计算的相似度.

j.两个语句的神经网络编码的改进的Compare-Aggregate模型的相似度
