# awesome-word-segmentation
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources dedicated to word segmentation

## Contents

### Chinese Word Segmentation Packages

1. [Jieba 结巴中文分词](https://github.com/fxsjy/jieba)
1. [HanLP: Han Language Processing](https://github.com/hankcs/HanLP) 是由一系列模型与算法组成的NLP工具包，目标是普及自然语言处理在生产环境中的应用。[pyhanlp](https://github.com/hankcs/pyhanlp) 是 HanLP 的 Python 接口。 
1. [SnowNLP: Simplified Chinese Text Processing](https://github.com/isnowfy/snownlp) 提供中文分词功能，分词是基于 [Character-Based Generative Model](http://aclweb.org/anthology//Y/Y09/Y09-2047.pdf) 实现。
1. [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP) is a Java suite of core NLP tools. 它提供分词功能。[stanford-corenlp](https://github.com/Lynten/stanford-corenlp) is a python wrapper for Stanford CoreNLP.
1. [Stanford Word Segmenter](https://nlp.stanford.edu/software/segmenter.html) is a Java implementation of the CRF-based Chinese Word Segmenter.
1. [THULAC (THU Lexical Analyzer for Chinese)](https://github.com/thunlp/THULAC-Python) 由清华大学自然语言处理与社会人文计算实验室研制推出的一套中文词法分析工具包，具有中文分词和词性标注功能。
1. [kcws 深度学习中文分词](https://github.com/koth/kcws) BiLSTM+CRF 与 IDCNN+CRF
1. [FoolNLTK](https://github.com/rockyzhengwu/FoolNLTK) 可能不是最快的开源中文分词，但很可能是最准的开源中文分词
1. [ID-CNN-CWS](https://github.com/hankcs/ID-CNN-CWS) Iterated Dilated Convolutions for Chinese Word Segmentation
1. [Genius 中文分词](https://github.com/duanhongyi/genius) 采用 CRF(Conditional Random Field)条件随机场算法
1. [loso 中文分词](https://github.com/fangpenlin/loso)
1. [yaha "哑哈"中文分词](https://github.com/jannson/yaha)
1. [ChineseWordSegmentation](https://github.com/Moonshile/ChineseWordSegmentation) Chinese word segmentation algorithm without corpus（无需语料库的中文分词）
1. 语言技术平台[LTP: Language Technology Platform](https://github.com/HIT-SCIR/ltp) 提供分词功能；[pyltp](https://github.com/HIT-SCIR/pyltp) 是该平台的 Python 封装
1. [ICTCLAS](https://github.com/NLPIR-team/NLPIR-ICTCLAS) 分词工具。
1. [jcseg](https://github.com/lionsoul2014/jcseg)是基于 mmseg 算法的一个轻量级中文分词器，同时集成了关键字提取，关键短语提取，关键句子提取和文章自动摘要等功能，并且提供了一个基于Jetty的web服务器，方便各大语言直接http调用，同时提供了最新版本的lucene, solr, elasticsearch的分词接口。
1. [sego](https://github.com/huichen/sego) Go 中文分词，它的词典用双数组trie（Double-Array Trie）实现， 分词器算法为基于词频的最短路径加动态规划。支持普通和搜索引擎两种分词模式，支持用户词典、词性标注，可运行JSON RPC服务。
1. [ansj_seg](https://github.com/NLPchina/ansj_seg) 是一个基于n-Gram+CRF+HMM 的中文分词的java实现。分词速度达到每秒钟大约200万字左右（mac air下测试），准确率能达到96%以上。目前实现了中文分词、中文姓名识别、用户自定义词典、关键字提取、自动摘要、关键字标记等功能。可以应用到自然语言处理等方面,适用于对分词效果要求高的各种项目.
1. [word](https://github.com/ysc/word) 分词是一个Java实现的分布式的中文分词组件，提供了多种基于词典的分词算法，并利用ngram模型来消除歧义。能准确识别英文、数字，以及日期、时间等数量词，能识别人名、地名、组织机构名等未登录词。能通过自定义配置文件来改变组件行为，能自定义用户词库、自动检测词库变化、支持大规模分布式环境，能灵活指定多种分词算法，能使用refine功能灵活控制分词结果，还能使用词频统计、词性标注、同义标注、反义标注、拼音标注等功能。提供了10种分词算法，还提供了10种文本相似度算法，同时还无缝和Lucene、Solr、ElasticSearch、Luke集成。
