# 数据智能实验室
[**数据智能实验室-文本智能组简介**](#数据智能实验室-文本智能组简介) |
[**展示系统 & Demo**](#展示系统-&-demo) |
[**开源代码**](#开源代码)
[**开源数据集**](#开源数据集) |
[**已发表论文**](已发表论文) |
[**成员**](#成员) |
[**English**](./README.md)

## 数据智能实验室-文本智能组简介

## 展示系统 & Demo
| 系统名       | 简介                                                         |  地址链接                                                    | 相关论文 |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 川小妹 | -|![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/%E5%B7%9D%E5%B0%8F%E5%A6%B9%E5%B0%8F%E7%A8%8B%E5%BA%8F.jpg)<br>请扫描上方微信二维码<br>打开川小妹微信小程序|Deep Poetry: A Chinese Classical Poetry Generation System, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212) <br> Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| AI小翻 | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 老中医 | AI中医开方系统 | http://dicalab.cn:7777 | -------- |

## 开源代码
| 项目     | 简介                                                         |  代码链接                                                      | 相关论文 |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Mu-Forcing文本变分自编码器模型 | 一种有效的基于正则化的方法来解决文本变分自编码器的模型训练坍塌问题。  | [Mu-Forcing-VRAE](https://github.com/dayihengliu/Mu-Forcing-VRAE) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072) |
| 基于梯度搜索的文本推理填空算法 | -| - |-|

## 开源数据集
| 数据集     | 简介                                                         |  下载地址                                                      | 相关论文 |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| 中文古文-现代文对齐语料集 | 包含训练集984,611 / 验证集48,980 / 测试集50,000 条对齐的古文现代文子句语料 | [A2M (Ancient-Modern of Chinese)](https://github.com/dayihengliu/a2m_chineseNMT) | Ancient-Modern Chinese Translation with a New Large Training Dataset, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738) <br> An Automatic Evaluation Metric for Ancient-Modern Chinese Translation**, Neural Computing and Applications. **NCAA** 2020 <br> **AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation**, arXiv 2020. [[Paper]](https://arxiv.org/abs/2009.11473)|
| 中文造句语料集 | 包含2,445,164句以常用词汇、成语等词语进行造句的例句，每个词语包含多条例句 | [链接](https://drive.google.com/file/d/1z1bfMxil0mhI4TK7K0YQwjufwG_48anv/view?usp=sharing
) | BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation, **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)|
| 中文互联网商品用户评论数据集 | 586,538 | - | - |
| 古诗数据集 | 232,670| - |-|
| 对联数据集 | 774,491 | - | **AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation**, arXiv 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| 中文对话数据集 | 24W条左右 基于知识库的对话系统，训练数据，已经初步处理，可以直接食用| [https://github.com/wulaoshi/dialogue_train_data](https://github.com/wulaoshi/dialogue_train_data) |还在写...|
| 医学问题生成预训练数据 | 106W条左右 经过清洗处理，可直接用于预训练医学问题生成模型 | [https://github.com/wulaoshi/Data-for-generating-medical-problems](https://github.com/wulaoshi/Data-for-generating-medical-problems) |-|

## 已发表论文

### 2020
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Jiancheng Lv, Nan Duan, Ming Zhou*, **Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2010.01475)

- *Dayiheng Liu, Yeyun Gong, Jie Fu, Wei Liu, Yu Yan, Bo Shao, Daxin Jiang, Jiancheng Lv, Nan Duan*, **Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2004.03875)

- *Yu Yan\*, Weizhen Qi\*, Yeyun Gong\*, Dayiheng Liu\*, Nan Duan, Jiusheng Chen, Ruofei Zhang, Ming Zhou*, **ProphetNet: Predicting Future N-gram for Sequence-to-Sequence Pre-training**, Conference on Empirical Methods in Natural Language Processing. Findings of **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2001.04063)[[Code]](https://github.com/microsoft/ProphetNet)[[Intro]](https://www.msra.cn/zh-cn/news/features/prophetnet)
 
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Daxin Jiang, Jiancheng Lv, Nan Duan*, **RikiNet: Reading Wikipedia Pages for Natural Question Answering**, Association for Computational Linguistics. **ACL** 2020 [[Paper]](https://arxiv.org/abs/2004.14560)  

- *Dayiheng Liu, Jie Fu, Yidan Zhang, Chris	Pal, Jiancheng Lv*, **Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning**, Association for the Advancement of Artificial Intelligence. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1905.12304)[[Code]](https://github.com/dayihengliu/Fine-Grained-Style-Transfer)

- *Chanjuan Li, Dayiheng Liu, Kexin Yang, Xiaoming Huang, Jiancheng Lv*, **Herb-Know: Knowledge Enhanced Prescription Generation for Traditional Chinese Medicine**, IEEE International Conference on Bioinformatics and Biomedicine. **BIBM-ITCM** 2020

- *Yusen Liu\*, Dayiheng Liu\*, Jiancheng Lv*, **Deep Poetry: A Chinese Classical Poetry Generation System**, Association for the Advancement of Artificial Intelligence, Demonstrations Program. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212)[[Video]](https://youtu.be/jD1R_u9TA3M)
  
- *Yusen Liu, Dayiheng Liu, Jiancheng Lv, Yongsheng Sang*, **Generating Chinese Poetry from Images via Concrete and Abstract Information**, International Joint Conference on Neural Networks. **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773)

- *Kexin Yang, Dayiheng Liu, Qian Qu, Jiancheng Lv, Yongsheng Sang*, **An Automatic Evaluation Metric for Ancient-Modern Chinese Translation**, Neural Computing and Applications. **NCAA** 2020

- *Liao Chen, Zhichen Lai, Dayiheng Liu, Jiancheng Lv, Yongsheng Sang*, **Exploration on the Generation of Chinese Palindrome Poetry**, International Conference on Neural Information Processing. **ICONIP** 2020  
  
- *Huishuang Tian, Kexin Yang, Dayiheng Liu, Jiancheng Lv*, **AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation**, arXiv 2020. [[Paper]](https://arxiv.org/abs/2009.11473) 

- *Hang Zhang, Dayiheng Liu, Jiancheng Lv, Cheng Luo*, **Let's be Humorous: Knowledge Enhanced Humor Generation**, arXiv 2020. [[Paper]](https://arxiv.org/abs/2004.13317)  
 
 ### 2019
 
- *Dayiheng Liu, Jie Fu, Pengfei Liu, Jiancheng Lv*, **TIGS: An Inference Algorithm for Text Inﬁlling with Gradient Search**, Association for Computational Linguistics. **ACL** 2019 [[Paper]](https://arxiv.org/abs/1905.10752)[[Code]](https://github.com/dayihengliu/Text-Infilling-Gradient-Search)

- *Dayiheng Liu, Jie Fu, Qian Qu, Jiancheng Lv*, **BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation**, IEEE/ACM Transactions on Audio, Speech, and Language Processing. **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)

- *Dayiheng Liu\*, Xue Yang\*, Feng He, Yuanyuan Chen, Jiancheng Lv*, **µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE)

- *Dayiheng Liu, Kexin Yang, Qian Qu, Jiancheng Lv*, **Ancient-Modern Chinese Translation with a New Large Training Dataset**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738)[[Dataset]](https://github.com/dayihengliu/a2m_chineseNMT)[[Demo]](http://translation.dicalab.cn/ancient)

### 2018
- *Dayiheng Liu, Quan Guo, Wubo Li, Jiancheng Lv*, **A Multi-Modal Chinese Poetry Generation Model**, International Joint Conference on Neural Networks. **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1)

- *Dayiheng Liu, Jiancheng Lv, Yunxia Li*, **Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model**, IEEE Transactions on Emerging Topics in Computational Intelligence. **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485)[[Samples]](https://drive.google.com/open?id=10vAC7MweWwjdWohMe64m2imia1DBCq8o) 

## 成员

