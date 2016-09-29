## 我的九月份论文

【1】颜水成老师在AAAI2014上发表了第一篇将深度学习和哈希学习结合在一起的工作，不是一个端到端的工作。在第一阶段使用了坐标下降的方法。

    [Supervised Hashing for Image Retrieval via Image Representation Learning(AAAI14)]
    
【2】不是一个端到端的方法，很多地方处理的比较粗糙。考虑词嵌入和位置嵌入，卷积后结合，得到隐式特征，再将显示特征加进来，最后还得使用tf-idf得到的进过进行监督。

    [Convolutional Neural Networks for Text Hashing(ijcai15)]
    
【3】RNN文本分类，用了线性的上下文，将时间的复杂度降为O(N),RCNN结构很好。使用了双向RNN作为CNN-max-pooling的输入

    [Recurrent convolutional neural networks for text classification (AAAI15)]
    
【4】这篇论文就是RCNN的推崇者，在RCNN的基础上，加了一层。参考文献倒是有很多可借鉴的。分析的也还好.RNN因为更看重后面的内容，效果不好。CNN要考虑卷积大小，所以提出了一个结合的方法。词序很重要，一个文本分类的脉络。要看。序列长度对模型的影响。RCNN在short text上效果并没有那么的好

    [Learning text representation using recurrent convolutional neural network with highway layers(arxiv16)]
    
【5】曹樾的将CNN 和 RNN 结合起来的cross-modal模型。将各个目标函数放在一起。

    [Deep Visual-Semantic Hashing for Cross-Modal Retrieval(KDD16)]
    
【6】将编码的学习和哈希函数的学习进行相互促进。

    [Optimizing Affinity-Based Binary Hashing Using Auxiliary Coordinates(Nips16)]
    
【7】google的文章，以后要多关注。只用线性的方法做，泛化性能不好。用深度提取特征，在稀疏高质的情况下效果不好，将其结合。

    [Wide  Deep Learning for Recommender Systems]
 
## 要看



【3】Sequential Short-Text Classification with Recurrent and Convolutional Neural Networks

【4】Supervised and Semi-Supervised Text Categorizationusing LSTM for Region Embeddings

【5】Deep Fusion LSTMs for Text Semantic Matching

【6】Long-term Recurrent Convolutional Networks for Visual Recognition and Description

【7】sequence to sequence learning with neural networks

【8】he kai ming

【9】Long short-term memory.

【10】A convolutional neural network for modelling sentences（ACL14）

【11】Convolutional Neural Networks for Sentence Classification(引用高)

【12】Bidirectional recurrent neural networks(双向RNN)

【13】Dropout: A simple way to prevent neural networks from overfitting(dropout)
【14】
