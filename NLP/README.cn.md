# 数据智能实验室
[**数据智能实验室-文本智能组简介**](#数据智能实验室-文本智能组简介) |
[**展示系统 & Demo**](#展示系统-&-demo) |
[**开源代码**](#开源代码)
[**开源数据集**](#开源数据集) |
[**已发表论文**](已发表论文) |
[**成员**](#成员) |
[**English**](./README.md)

## 数据智能实验室-文本智能组简介

文本智能组主要集中在

## 展示系统 & Demo
| 系统名       | 简介                                                         |  地址链接                                                    | 相关论文 |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 川小妹 | -|![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/%E5%B7%9D%E5%B0%8F%E5%A6%B9%E5%B0%8F%E7%A8%8B%E5%BA%8F.jpg)<br>请扫描上方微信二维码<br>打开川小妹微信小程序|Deep Poetry: A Chinese Classical Poetry Generation System, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212) <br> Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| 不懂文言 | 不懂文言是一个帮助文言学习者提高兴趣和效率的微信小程序，以人工智能技术，实现文言文和白话文互译的翻译功能。除此之外，它还会每日推送一句经典的文言名句，可以将它生成海报分享。同时，不懂文言还为用户提供了文言文断句和填词两个趣味游戏。 | ![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/AI%E5%B0%8F%E7%BF%BB.jpg)<br>请扫描上方微信二维码<br>打开AI小翻微信小程序 |  Ancient-Modern Chinese Translation with a New Large Training Dataset, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738) <br> An Automatic Evaluation Metric for Ancient-Modern Chinese Translation, Neural Computing and Applications. **NCAA** 2020 <br> AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| 老中医 | AI中医开方系统 | [网页链接](http://dicalab.cn:7777) | - |

## 开源代码
| 项目     | 简介                                                         |  代码链接                                                      | 相关论文 |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Mu-Forcing文本变分自编码器模型 | 基于正则化的方法来缓解文本变分自编码器的模型训练坍塌问题。  | [项目地址](https://github.com/dayihengliu/Mu-Forcing-VRAE) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072) |
| 基于梯度搜索的文本推理填空算法 | 一种基于梯度搜索思想的迭代式文本填空推理算法，可用于主流单向生成模型完成填空任务。 | [项目地址](https://github.com/dayihengliu/Text-Infilling-Gradient-Search) | TIGS: An Inference Algorithm for Text Inﬁlling with Gradient Search, **ACL** 2019 [[Paper]](https://arxiv.org/abs/1905.10752) |
| 基于连续空间修改的文本属性控制算法 | 基于连续空间修改的文本属性控制算法，可以对多种文本细粒度属性进行控制，如情感，长度，关键词等 | [项目地址](https://github.com/dayihengliu/Fine-Grained-Style-Transfer) | Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1905.12304) |
| 先知网络 | 基于未来N元组预测的文本生成预训练语言模型| [项目地址](https://github.com/microsoft/ProphetNet) | ProphetNet: Predicting Future N-gram for Sequence-to-Sequence Pre-training, **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2001.04063) |
| 关键短语感知的多新闻标题生成算法 | 基于新闻中不同的关键词短语，生成多样化的新闻标题 | [项目地址](https://github.com/dayihengliu/KeyMultiHeadline) | Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation, **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2004.03875) |
| 基于连续空间修改的问句数据增广 | 基于连续空间修改的问句数据增广算法，可以生成上下文相关的可回答问句和不可回答问句作为增广数据 | [项目地址](https://github.com/dayihengliu/CRQDA) | Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space, **EMNLP** 2020  [[Paper]](https://arxiv.org/abs/2010.01475)|

## 开源数据集
| 数据集     | 简介                                                         |  下载地址                                                      | 相关论文 |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 中文古文-现代文对齐语料集 | 包含训练集984,611 / 验证集48,980 / 测试集50,000 条对齐的古文现代文子句语料 | [下载地址](https://github.com/dayihengliu/a2m_chineseNMT) | Ancient-Modern Chinese Translation with a New Large Training Dataset, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738) <br> An Automatic Evaluation Metric for Ancient-Modern Chinese Translation, Neural Computing and Applications. **NCAA** 2020 <br> AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473)|
| 中文造句语料集 | 包含2,445,164句以常用词汇、成语等词语进行造句的例句，每个词语包含多条例句 | [下载地址](https://drive.google.com/file/d/1z1bfMxil0mhI4TK7K0YQwjufwG_48anv/view?usp=sharing) | BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation, **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)|
| 中文互联网商品用户评论数据集 | 包含586,538条互联网商品的用户评论句子，涵盖消极情感到积极情感 | [下载地址](https://drive.google.com/file/d/1v01aGYMnhGdED-xBX9JVP-Ub5Nu_OyA-/view?usp=sharing) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE) |
| 古诗数据集 | 包含232,670首五言或七言绝句数据 | [下载地址](https://drive.google.com/file/d/1YcP6B28KsOwacr7C_j1tcstkA-QtPd61/view?usp=sharing) |Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| 对联数据集 | 包含774,491条中文对联数据 | [下载地址](https://drive.google.com/file/d/1gBBlLrfj2QxrTft0zTGoBbCrwi3kuRqn/view?usp=sharing) | AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| 中文对话数据集 | 24W条深度清洗的对话数据 eg:```{'history_utt': ['知道重庆森林这部电影吗？', '知道呀，是一部由王家卫导演的片子'], 'response': '而主演里更是有王菲，一上映便受到追捧', 'knowledge': '重庆森林主演王菲', 'label': 1, 'mention': '重庆森林'}```| [下载地址](https://github.com/wulaoshi/dialogue_train_data) |-|
| 医学问题生成预训练数据 | 106W条深度清洗的问题生成数据  eg:```{'id': 'MQNLI_0_1', 'text': '您好！咳嗽带血是肝癌肺转移主要症状之一，肝癌肺转移病症比较复杂治疗起来比较棘手，多数患者因肿瘤消耗严重身体虚弱免疫功能下降，建议接受中医中药进行治疗。中医中药治疗肝癌肺转移通过对病人情况进行仔细辨证，运用养阴清热、活血化瘀、益气生津、养肝护肝等方法，改善患者机体内部环境缓解咳血等不适症状增强免疫力，减轻患者痛苦，能达到提高生存质量延长生存期的目的。', 'label': '中医治疗肝癌晚期肺转移的优势是什么？'}``` | [下载地址](https://github.com/wulaoshi/Data-for-generating-medical-problems) |-|

## 已发表论文

### 2020
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Jiancheng Lv, Nan Duan, Ming Zhou*, **Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2010.01475)

- *Dayiheng Liu, Yeyun Gong, Jie Fu, Wei Liu, Yu Yan, Bo Shao, Daxin Jiang, Jiancheng Lv, Nan Duan*, **Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2004.03875)

- *Yu Yan\*, Weizhen Qi\*, Yeyun Gong\*, Dayiheng Liu\*, Nan Duan, Jiusheng Chen, Ruofei Zhang, Ming Zhou*, **ProphetNet: Predicting Future N-gram for Sequence-to-Sequence Pre-training**, Conference on Empirical Methods in Natural Language Processing. Findings of **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2001.04063)[[Code]](https://github.com/microsoft/ProphetNet)[[Intro]](https://www.msra.cn/zh-cn/news/features/prophetnet)
 
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Daxin Jiang, Jiancheng Lv, Nan Duan*, **RikiNet: Reading Wikipedia Pages for Natural Question Answering**, Association for Computational Linguistics. **ACL** 2020 [[Paper]](https://arxiv.org/abs/2004.14560)  

- *Dayiheng Liu, Jie Fu, Yidan Zhang, Chris	Pal, Jiancheng Lv*, **Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning**, Association for the Advancement of Artificial Intelligence. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1905.12304)[[Code]](https://github.com/dayihengliu/Fine-Grained-Style-Transfer)

- *Chanjuan Li, Dayiheng Liu, Kexin Yang, Xiaoming Huang, Jiancheng Lv*, **Herb-Know: Knowledge Enhanced Prescription Generation for Traditional Chinese Medicine**, IEEE International Conference on Bioinformatics and Biomedicine. **BIBM** 2020

- *Yusen Liu\*, Dayiheng Liu\*, Jiancheng Lv*, **Deep Poetry: A Chinese Classical Poetry Generation System**, Association for the Advancement of Artificial Intelligence, Demonstrations Program. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212)[[Video]](https://youtu.be/jD1R_u9TA3M)
  
- *Yusen Liu, Dayiheng Liu, Jiancheng Lv, Yongsheng Sang*, **Generating Chinese Poetry from Images via Concrete and Abstract Information**, International Joint Conference on Neural Networks. **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773)

- *Kexin Yang, Dayiheng Liu, Qian Qu, Jiancheng Lv, Yongsheng Sang*, **An Automatic Evaluation Metric for Ancient-Modern Chinese Translation**, Neural Computing and Applications. **NCAA** 2020

- *Liao Chen, Zhichen Lai, Dayiheng Liu, Jiancheng Lv, Yongsheng Sang*, **Exploration on the Generation of Chinese Palindrome Poetry**, International Conference on Neural Information Processing. **ICONIP** 2020  
  
- *Huishuang Tian, Kexin Yang, Dayiheng Liu, Jiancheng Lv*, **AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation**, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) 

- *Hang Zhang, Dayiheng Liu, Jiancheng Lv, Cheng Luo*, **Let's be Humorous: Knowledge Enhanced Humor Generation**, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2004.13317)  
 
 ### 2019
 
- *Dayiheng Liu, Jie Fu, Pengfei Liu, Jiancheng Lv*, **TIGS: An Inference Algorithm for Text Inﬁlling with Gradient Search**, Association for Computational Linguistics. **ACL** 2019 [[Paper]](https://arxiv.org/abs/1905.10752)[[Code]](https://github.com/dayihengliu/Text-Infilling-Gradient-Search)

- *Dayiheng Liu, Jie Fu, Qian Qu, Jiancheng Lv*, **BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation**, IEEE/ACM Transactions on Audio, Speech, and Language Processing. **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)

- *Dayiheng Liu\*, Xue Yang\*, Feng He, Yuanyuan Chen, Jiancheng Lv*, **µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE)

- *Dayiheng Liu, Kexin Yang, Qian Qu, Jiancheng Lv*, **Ancient-Modern Chinese Translation with a New Large Training Dataset**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738)[[Dataset]](https://github.com/dayihengliu/a2m_chineseNMT)[[Demo]](http://translation.dicalab.cn/ancient)

### 2018
- *Dayiheng Liu, Quan Guo, Wubo Li, Jiancheng Lv*, **A Multi-Modal Chinese Poetry Generation Model**, International Joint Conference on Neural Networks. **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1)

- *Dayiheng Liu, Jiancheng Lv, Yunxia Li*, **Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model**, IEEE Transactions on Emerging Topics in Computational Intelligence. **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485)[[Samples]](https://drive.google.com/open?id=10vAC7MweWwjdWohMe64m2imia1DBCq8o) 

## 成员

