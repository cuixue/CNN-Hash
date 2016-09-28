## 我的九月份论文

【1】颜水成老师在AAAI2014上发表了第一篇将深度学习和哈希学习结合在一起的工作，不是一个端到端的工作。在第一阶段使用了坐标下降的方法。

    [Supervised Hashing for Image Retrieval via Image Representation Learning(AAAI14)]
    
【2】不是一个端到端的方法，很多地方处理的比较粗糙。考虑词嵌入和位置嵌入，卷积后结合，得到隐式特征，再将显示特征加进来，最后还得使用tf-idf得到的进过进行监督。

    [Convolutional Neural Networks for Text Hashing(ijcai15)]
    
【3】RNN文本分类，用了线性的上下文，将时间的复杂度降为O(N)

    [Recurrent convolutional neural networks for text classification (AAAI15)]
    
【4】曹樾的将CNN 和 RNN 结合起来的cross-modal模型。将各个目标函数放在一起。

    [Deep Visual-Semantic Hashing for Cross-Modal Retrieval(KDD16)]
    
【5】将编码的学习和哈希函数的学习进行相互促进。

    [Optimizing Affinity-Based Binary Hashing Using Auxiliary Coordinates(Nips16)]
 
## 要看
【1】google的文章，以后要关注

    [Wide  Deep Learning for Recommender Systems]
【2】Learning text representation using recurrent convolutional neural network with highway layers

【3】Sequential Short-Text Classification with Recurrent and Convolutional Neural Networks

【4】Supervised and Semi-Supervised Text Categorizationusing LSTM for Region Embeddings

【5】Deep Fusion LSTMs for Text Semantic Matching
