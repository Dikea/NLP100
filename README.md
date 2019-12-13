# NLP100 速问速答

> 一个问题，一段回答，一张图片，简洁明了的呈现 NLP 世界的轮廓


   * [NLP100 速问速答](#nlp100-速问速答)
      * [速问速答](#速问速答)
         * [什么是自然语言处理](#什么是自然语言处理)
         * [自然语言处理的主要任务有哪些](#自然语言处理的主要任务有哪些)
         * [文本分词的常见方法有哪些](#文本分词的常见方法有哪些)
         * [常见的分词工具包有哪些](#常见的分词工具包有哪些)
         * [词语可以通过哪些数学方式表示](#词语可以通过哪些数学方式表示)
         * [有哪些好用的 NLP 工具包](#有哪些好用的-nlp-工具包)
      * [版权问题](#版权问题)
      * [参考文献](#参考文献)


## 速问速答


### 什么是自然语言处理

英语称谓为 Natural Language Processing，简称 NLP。**自然语言**指的是生活中人们使用的语言，如中文、英语，**处理**包含了对语言文本的分析、理解和生成等部分。

<div align="center"><img src="images/001.png" height="160"></div>


### 自然语言处理的主要任务有哪些

自然语言处理的主要任务有：语音合成、语音识别、自动分词、词性标注、句法分析、文本生成、文本分类、信息检索、信息抽取、问答系统、机器翻译、自动摘要、文本逻辑推理、命名实体识别、语言模型等。

<div align="center"><img src="images/002.png" height="300"></div>


### 文本分词的常见方法有哪些

- 基于词典的分词算法
    - 正向最大匹配法
    - 逆向最大匹配法
    - 双向匹配法
- 基于统计的机器学习算法
    - HMM 
    - CRF 
    - SVM
    - 深度学习


### 常见的分词工具包有哪些

- [Hanlp分词器](https://github.com/hankcs/HanLP)
- [结巴分词](https://github.com/yanyiwu/cppjieba)
- [Stanford分词器](https://nlp.stanford.edu/software/segmenter.shtml)
- [清华大学THULAC](https://github.com/thunlp/THULAC)
- [中科院计算所NLPIR](http://ictclas.nlpir.org/nlpir/)


### 词语可以通过哪些数学方式表示

数学表示，一般是指将词映射为向量表示，分为稀疏表示和分布表示。

- **稀疏表示**：常使用 one-hot 表示，将词映射为 n 维向量，n 为词的数目，例如总共有 10 个词，「我们」是第一个词，则其的 one-hot 向量表示为：`[1, 0, 0, 0, 0, 0, 0, 0, 0, 0]`；
- **分布表示**：较为稠密的词向量表述，可以将每个词表示为一个固定维度（例如 300 维）的向量，通常方法有 word2vec、fasttext、glove 等。


### 有哪些好用的 NLP 工具包

NLP 工具包一般包含了常见的文本处理功能，例如文本分词、词性标注、语法分析、文本分类等。国内外有一些有名的 NLP 工具包，如下：

- [HanLP](http://hanlp.com/) 中文文本处理工具包，性能较好，方法齐全；
- [NLTK](https://www.nltk.org/) 该工具包常用于教学，官方的学习资料可[在线阅读](http://www.nltk.org/book/)；
- [CoreNlP](https://stanfordnlp.github.io/CoreNLP/index.html) 由斯坦福大学开发；
- [SpaCy](https://spacy.io/) 具有工业级强度的Python NLP工具包；
- [Gensim](https://radimrehurek.com/gensim/) 从文档中自动提取语义主题，集成了多种文本表示方法；


### 聊天机器人的常见类型有哪些

聊天机器人的常见类型有任务式对话机器人、检索式对话机器人和生成式对话机器人：

- 任务式对话机器人
- 检索式对话机器人
- 生成式对话机器人


## 版权问题

未经授权，禁止转载，翻版必究。


## 参考文献

- [维基百科](https://zh.wikipedia.org/wiki/%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86)