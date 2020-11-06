# DILab-NLP
[**Intro**](#introduction) |
[**Systems & Demos**](#systems-&-demos) |
[**Code**](#code) |
[**Datasets**](#datasets) |
[**Publications**](publications) |
[**Members**](#members) |
[**Chinese (中文版)**](./README.cn.md)

## Introduction

## Systems & Demos
| Project       | Introduction                                                         |  Link                                                    | Relevant publications |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Chuanxiaomei | -|![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/%E5%B7%9D%E5%B0%8F%E5%A6%B9%E5%B0%8F%E7%A8%8B%E5%BA%8F.jpg)<br>Please use Wechat to scan the QR code above to open the Chuanxiaomei APP|Deep Poetry: A Chinese Classical Poetry Generation System, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212) <br> Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| AI xiaofan | ---------- | ![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/AI%E5%B0%8F%E7%BF%BB.jpg)<br>Please use Wechat to scan the QR code above to open the AI xiaofan APP| -------- |
| Laozhongyi | An AI system generating Chinese medicine presripts | [网页链接](http://dicalab.cn:7777) | -------- |

## Code 
| Project     | Introduction                                                         |  Code Link                                                      | Paper |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| mu-Forcing: Training Variational Recurrent Autoencoders for Text Generation | In this work, we explore the reason why training Variational Recurrent Autoencoders (VRAE) for text generation suffers from serious uninformative latent variables problem and propose an effective regularizer based approach to address it.  | [code](https://github.com/dayihengliu/Mu-Forcing-VRAE) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072) |
| TIGS: An Inference Algorithm for Text Infilling with Gradient Search | In this work, we propose an iterative inference algorithm based on gradient search, which is the first inference algorithm that can be broadly applied to any neural sequence generative models for text infilling tasks.  | [code](https://github.com/dayihengliu/Text-Infilling-Gradient-Search) | TIGS: An Inference Algorithm for Text Inﬁlling with Gradient Search, **ACL** 2019 [[Paper]](https://arxiv.org/abs/1905.10752) |
| Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning | We propose a new framework that utilizes the gradients to revise the sentence in a continuous space during inference to achieve text style transfer. Moreover, the proposed method naturally has the ability to simultaneously manipulate multiple fine-grained attributes, such as sentence length and the presence of specific words, when performing text style transfer tasks. | [code](https://github.com/dayihengliu/Fine-Grained-Style-Transfer) | Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1905.12304) |
| ProphetNet | This work presents a new sequence-to-sequence pre-training model called ProphetNet, which introduces a novel self-supervised objective named future n-gram prediction and the proposed n-stream self-attention mechanism.| [code](https://github.com/microsoft/ProphetNet) | ProphetNet: Predicting Future N-gram for Sequence-to-Sequence Pre-training, **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2001.04063) |
| Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation|  In this work, we propose generating multiple headlines with keyphrases of user interests | [code](https://github.com/dayihengliu/KeyMultiHeadline) | Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation, **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2004.03875) |
| Question Data Augmentation with Controllable Rewriting in Continuous Space | In this work, we propose a novel data augmentation method, referred to as Controllable Rewriting based Question Data Augmentation (CRQDA), for machine reading comprehension (MRC), question generation, and question-answering natural language inference tasks.  | [code](https://github.com/dayihengliu/CRQDA) | Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space, **EMNLP** 2020  [[Paper]](https://arxiv.org/abs/2010.01475)|

## Datasets
| Datasets     | Introduction                                                         |   Download Link                                                      | Paper |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Ancient-Modern Chinese Dataset| We create a new large-scale Ancient-Modern Chinese parallel corpus which contains 1.24M bilingual pairs. To our best knowledge, this is the first large high-quality Ancient-Modern Chinese dataset which includes 984,611 pairs in training set, 48,980 pairs in validation set, and 50,000 pairs in test set.| [Download](https://github.com/dayihengliu/a2m_chineseNMT) | Ancient-Modern Chinese Translation with a New Large Training Dataset, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738) <br> An Automatic Evaluation Metric for Ancient-Modern Chinese Translation, Neural Computing and Applications. **NCAA** 2020 <br> AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473)|
| Chinese Sentence Making Corpus  | 包含2,445,164句以常用词汇、成语等词语进行造句的例句，每个词语包含多条例句 | [Download](https://drive.google.com/file/d/1z1bfMxil0mhI4TK7K0YQwjufwG_48anv/view?usp=sharing) | BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation, **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)|
| 中文互联网商品用户评论数据集 | 包含586,538条互联网商品的用户评论句子，涵盖消极情感到积极情感 | [Download](https://drive.google.com/file/d/1v01aGYMnhGdED-xBX9JVP-Ub5Nu_OyA-/view?usp=sharing) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE) |
| 古诗数据集 | 包含232,670首五言或七言绝句数据 | [Download](https://drive.google.com/file/d/1YcP6B28KsOwacr7C_j1tcstkA-QtPd61/view?usp=sharing) |Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| 对联数据集 | 包含774,491条中文对联数据 | [Download](https://drive.google.com/file/d/1gBBlLrfj2QxrTft0zTGoBbCrwi3kuRqn/view?usp=sharing) | AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| 中文对话数据集 | 24W条左右 基于知识库的对话系统，训练数据，已经初步处理，可以直接食用| [Download](https://github.com/wulaoshi/dialogue_train_data) |-|
| 医学问题生成预训练数据 | 106W条左右 经过清洗处理，可直接用于预训练医学问题生成模型 | [Download](https://github.com/wulaoshi/Data-for-generating-medical-problems) |-|


## Publications

### 2020
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Jiancheng Lv, Nan Duan and Ming Zhou*, **Tell Me How to Ask Again: Question Data Augmentation with Controllable Rewriting in Continuous Space**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2010.01475)

- *Dayiheng Liu, Yeyun Gong, Jie Fu, Wei Liu, Yu Yan, Bo Shao, Daxin Jiang, Jiancheng Lv, Nan Duan*, **Diverse, Controllable, and Keyphrase-Aware: A Corpus and Method for News Multi-Headline Generation**, Conference on Empirical Methods in Natural Language Processing. **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2004.03875)

- *Yu Yan\*, Weizhen Qi\*, Yeyun Gong\*, Dayiheng Liu\*, Nan Duan, Jiusheng Chen, Ruofei Zhang, Ming Zhou*, **ProphetNet: Predicting Future N-gram for Sequence-to-Sequence Pre-training**, Conference on Empirical Methods in Natural Language Processing. Findings of **EMNLP** 2020 [[Paper]](https://arxiv.org/abs/2001.04063)[[Code]](https://github.com/microsoft/ProphetNet)[[Intro]](https://www.msra.cn/zh-cn/news/features/prophetnet)
 
- *Dayiheng Liu, Yeyun Gong, Jie Fu, Yu Yan, Jiusheng Chen, Daxin Jiang, Jiancheng Lv and Nan Duan*, **RikiNet: Reading Wikipedia Pages for Natural Question Answering**, Association for Computational Linguistics. **ACL** 2020 [[Paper]](https://arxiv.org/abs/2004.14560)  

- *Dayiheng Liu, Jie Fu, Yidan Zhang, Chris	Pal, Jiancheng Lv*, **Revision in Continuous Space: Unsupervised Text Style Transfer without Adversarial Learning**, Association for the Advancement of Artificial Intelligence. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1905.12304)[[Code]](https://github.com/dayihengliu/Fine-Grained-Style-Transfer)

- *Yusen Liu\*, Dayiheng Liu\*, Jiancheng Lv*, **Deep Poetry: A Chinese Classical Poetry Generation System**, Association for the Advancement of Artificial Intelligence, Demonstrations Program. **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212)[[Video]](https://youtu.be/jD1R_u9TA3M)
  
- *Yusen Liu, Dayiheng Liu, Jiancheng Lv, Yongsheng Sang*, **Generating Chinese Poetry from Images via Concrete and Abstract Information**, International Joint Conference on Neural Networks. **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773)

- *Kexin Yang, Dayiheng Liu, Qian Qu, Jiancheng Lv, Yongsheng Sang*, **An Automatic Evaluation Metric for Ancient-Modern Chinese Translation**, Neural Computing and Applications. **NCAA** 2020

- *Liao Chen, Zhichen Lai, Dayiheng Liu, Jiancheng Lv and Yongsheng Sang*, **Exploration on the Generation of Chinese Palindrome Poetry**, International Conference on Neural Information Processing. **ICONIP** 2020  
  
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

## Members

[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqTupTs40DfVnayWxEX0z.NrD9xg1orzTHs*n6BrfPaeCPuYzhtADQJJXDgyQEu5HoQOKUuDLn1*e97.YgaryvWA!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/dayihengliu)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqVWXXZC5PODCURy0LbUJ2.2RMH6U3hZxn5IH35Wb3AX*6dJbT*nRbOyguXlI0TPDt3Bd2xLk4daOnPE3TvnhPwM!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/yangkexin)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqZly.bU6lQZflNBBE1qlVjJjSSnsbXMS96Ob9b97LYE*IUdB*2KsAsB2I3v4Gs5VJjUbBNr0n3QG*9wg5R2Ean8!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/kylinaive)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqYZWikiBvOWvEMno7iDRRLDUXJIqXztjfGiW*cyFTki8w7MalJSnSIlJU4OknY1p5SPRk.GdcPMqwH2aVAtDvM4!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://mingfengxue.github.io/)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqR4mtZI98tepXgYbn68ub9Vp1f3QzQQdat3P9bIQjHMW*wYwQ6VKIlx*c6NESfWHxnSC5g5mD8kLs.9XgK7C.cY!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://moon290.github.io/)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqbLHFnS9m.Bniy4IfYJtdx23qpYRwsTx3GoMrMwpvvbiia*IZX1Oposx.pU8vOy4firn1sx6VR9rjMYvT1zFC6U!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/ttzHome)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqXRPMhNJQYEEhkcKcJWsCYIjzUuYdARCy0r4DJB11McVITQ4.Art2pAdD6ELjrKYjlB0Cpl1ghiQjj6v9SOyHDE!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/wulaoshi)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqXYIMz2FSBHGXAznF.4fvqpyqwG5UrKT0EXDaC0HDdSXgliwBhzJzOkityAryu4pjNL1lf4NUfcLgBwq5pzOWis!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/GeorgeLan)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqZhC1aJHQSCBLCcQn4H5UwLjNmZsqD0Iqeu5i9z7xWD2TtxI7LP6txEFscELV*gnolT*2rIh54Ss.4dmleSlKAI!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/onedoge)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqXPZn2.2F27qXyYxPuMBqpcPdw1fLU6PMi5yXbn*RXdOXh4U.FZdBkI6MoSxghrN4QJN2U7gFgdplex0dmxHXFk!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/voosil)[![](http://m.qpic.cn/psc?/da8d1fe0-aaf6-4861-8680-25d2a7b02707/bqQfVz5yrrGYSXMvKr.cqXPZn2.2F27qXyYxPuMBqpcPdw1fLU6PMi5yXbn*RXdOXh4U.FZdBkI6MoSxghrN4QJN2U7gFgdplex0dmxHXFk!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/JasonLiuys)

