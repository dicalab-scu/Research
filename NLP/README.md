# DILab-NLP
[**Intro**](#introduction) |
[**Systems & Demos**](#systems-&-demos) |
[**Code**](#code) |
[**Datasets**](#datasets) |
[**Publications**](#publications) |
[**Members**](#members) |
[**Chinese (中文版)**](./README.cn.md)

## Introduction
The DILab-NLP group focus on the following work:
![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/NLP.jpg)

## Systems & Demos
| Project       | Introduction                                                         |  Link                                                    | Relevant publications |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Chuanxiaomei | This is an introduction to Chuanxiaomei|![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/%E5%B7%9D%E5%B0%8F%E5%A6%B9%E5%B0%8F%E7%A8%8B%E5%BA%8F.jpg)<br>Please use Wechat to scan the QR code above to open the Chuanxiaomei APP|Deep Poetry: A Chinese Classical Poetry Generation System, **AAAI** 2020 [[Paper]](https://arxiv.org/abs/1911.08212) <br> Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| Budongwenyan xiaofan | This is an introduction to Budongwenyan| ![image](https://github.com/GeorgeLan/Research/blob/main/NLP/images/AI%E5%B0%8F%E7%BF%BB.jpg)<br>Please use Wechat to scan the QR code above to open the Budongwenyan APP| Ancient-Modern Chinese Translation with a New Large Training Dataset, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738) <br> An Automatic Evaluation Metric for Ancient-Modern Chinese Translation, Neural Computing and Applications. **NCAA** 2020 <br> AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| Laozhongyi | An AI system for Chinese medicine prescriptions | [Link](http://dicalab.cn:7777) | -------- |


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
| Chinese Sentence Making Corpus  | This datasts contains 2,445,164 sentences consisting of daily used words and idioms, each word and idioms have more than one example sentence.  | [Download](https://drive.google.com/file/d/1z1bfMxil0mhI4TK7K0YQwjufwG_48anv/view?usp=sharing) | BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation, **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)|
|Dataset about users giving comments to items on Chinese websites | The dataset contains 586,538 sentences about user comments, which cover both positive and negetive comments. | [Download](https://drive.google.com/file/d/1v01aGYMnhGdED-xBX9JVP-Ub5Nu_OyA-/view?usp=sharing) | µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation, **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE) |
| Ancient Poems Dataset | The datasets contains 232,670 quatrains. Each quatrain consists of 4 lines of sentences, and the length of each line is fixed to 5 or 7 characters.  | [Download](https://drive.google.com/file/d/1YcP6B28KsOwacr7C_j1tcstkA-QtPd61/view?usp=sharing) |Generating Chinese Poetry from Images via Concrete and Abstract Information, **IJCNN** 2020 [[Paper]](https://arxiv.org/abs/2003.10773) <br> A Multi-Modal Chinese Poetry Generation Model, **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1) <br> Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model, **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485) |
| Ancient Chinese Couplet Dataset | The dataset contains 774,491 ancient chinese couplets | [Download](https://drive.google.com/file/d/1gBBlLrfj2QxrTft0zTGoBbCrwi3kuRqn/view?usp=sharing) | AnchiBERT: A Pre-Trained Model for Ancient ChineseLanguage Understanding and Generation, **arXiv** 2020. [[Paper]](https://arxiv.org/abs/2009.11473) |
| Chinese Dialogue Dataset | Prepocessed dataset containing 240k QA examples | [Download](https://github.com/wulaoshi/dialogue_train_data) |-|
| Medical Questions Generating Dataset| Preprocessed dataset containing 1.06 million medical QA examples| [Download](https://github.com/wulaoshi/Data-for-generating-medical-problems) |-|


## Publications
### 2021
- *Kexin Yang, Wenqiang Lei, Dayiheng Liu, Weizhen Qi and Jiancheng Lv*, **POS-constrained Parallel Decoding for Non-autoregressive Generation**, Association for Computational Linguistics. **ACL** 2021

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

- *Mingfeng Xue, Hang Zhang, Jiancheng Lv*, **Key Factors of Email Subject Generation**, International Conference on Neural Information Processing. **ICONIP** 2020. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-63820-7_76) 
 
 ### 2019
 
- *Dayiheng Liu, Jie Fu, Pengfei Liu, Jiancheng Lv*, **TIGS: An Inference Algorithm for Text Inﬁlling with Gradient Search**, Association for Computational Linguistics. **ACL** 2019 [[Paper]](https://arxiv.org/abs/1905.10752)[[Code]](https://github.com/dayihengliu/Text-Infilling-Gradient-Search)

- *Dayiheng Liu, Jie Fu, Qian Qu, Jiancheng Lv*, **BFGAN: Backward and Forward Generative Adversarial Networks for Lexically Constrained Sentence Generation**, IEEE/ACM Transactions on Audio, Speech, and Language Processing. **TASLP** 2019 [[Paper]](https://arxiv.org/abs/1806.08097)

- *Dayiheng Liu\*, Xue Yang\*, Feng He, Yuanyuan Chen, Jiancheng Lv*, **µ-Forcing: Training Variational Recurrent Autoencoders for Text Generation**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1905.10072)[[Code]](https://github.com/dayihengliu/Mu-Forcing-VRAE)

- *Dayiheng Liu, Kexin Yang, Qian Qu, Jiancheng Lv*, **Ancient-Modern Chinese Translation with a New Large Training Dataset**, ACM Transactions on Asian and Low-Resource Language Information Processing. **TALLIP** 2019 [[Paper]](https://arxiv.org/abs/1808.03738)[[Dataset]](https://github.com/dayihengliu/a2m_chineseNMT)[[Demo]](http://translation.dicalab.cn/ancient)

### 2018
- *Dayiheng Liu, Quan Guo, Wubo Li, Jiancheng Lv*, **A Multi-Modal Chinese Poetry Generation Model**, International Joint Conference on Neural Networks. **IJCNN** 2018 [[Paper]](https://arxiv.org/abs/1806.09792v1)

- *Dayiheng Liu, Jiancheng Lv, Yunxia Li*, **Generating Style-specific Chinese Tang Poetry with a Simple Actor-Critic Model**, IEEE Transactions on Emerging Topics in Computational Intelligence. **TETCI** 2018 [[Paper]](https://ieeexplore.ieee.org/document/8482485)[[Samples]](https://drive.google.com/open?id=10vAC7MweWwjdWohMe64m2imia1DBCq8o) 

## Members

[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqb45AZx.74cjUKCBKIsXn3TSVFg56yIuaavk0Vmqsk*51Y3begpGYlilsyv69Ukn76ST06GxqSMIX4XDuLdBGnE!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/dayihengliu)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqeJPFfZk6AbpvpWl5.2UA5VwVXSyyifJx1pVPrkVOQ92wDyqj*29ej3QKVYarQuiXlMZ.y426tOlAC9Dr8GPiQE!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/yangkexin)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqWFTkDA7vaHZPECx*5A4WEKKuHJnK*tVeUYjVJpYWCu2CoYZPhTkvmud1zWCMDq.8LmLqcZVu9Ylt4stMHPDS08!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/kylinaive)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqf.oDN8OsQsjNaQjxj*UleBWDkUX3uzxg1t7ffaNs6NDxku2UE9ZvTIHWLmaWe8iU62D2uaOFrntW2ITdgIeQnM!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://mingfengxue.github.io/)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqQYjT7KPQSe4LwHs7zxMdhJmlQj0KlLt9HO66sozCLFwmhxc0YNZs.XyryRYiL25xFHzjNXwKR8o2OB2eEdCAu4!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://moon290.github.io/)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqXgyEnCmcEu4J2ja3x9*Ia1JK4N6Ifsv6hFtzolL895Vmnh2oq8sPcWIhb4t5Xh4FjKPyU1kjL66h.vckatoGZA!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/ttzHome)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqREY8R8pOl9GOQ4L.XcYAjc1Y.atoWw60A**ieqmthWewdjsd4X0Aks96NdrPmxB20Hjv3L5WBbb7HPhOcuKlPE!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/wulaoshi)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqXq150kftYcugSw.sLAfQitdAF0HANXN1rr.pj4mV4D5KsiWhjBiLAjukoux8MJaNx.8sR6x78jjvXbbuwPyFEw!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/GeorgeLan)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqThCEqbAo2DB.IFtyt92k98M5kXu4d3vSTBLcfTTAIFJndtj6egA3*qvOmoTaiOG*cz2kHmYYxX0MAthTvvKq04!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/onedoge)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqa7yEK9dAvu8q*36TBri2r1T5BCgYZNnycUYYVUtRZDBMteQs.2wfHlK3XKTX1CKhvHwS9HpEUPc9XoL.XmHBb8!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/voosil)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqRc3faBwbxCnI6IuiKsOoEBM1Dq7MdvaWjKxeYujEtGskKQ8iLhxPjsqFAt*I7bzjhFsngzqkvF96kisMIDeupU!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)](https://github.com/JasonLiuys)[![](http://m.qpic.cn/psc?/V12UsmyA3Ss9Ff/bqQfVz5yrrGYSXMvKr.cqXfn7bMxgnLCts.dLBlfp8NV8E7mQUF4Pg8Q9*krb5QSt2SOHIq8T5*i7VlVwO1ZuHIjK4GAvmrx.gBjS6cTyNg!/mnull&bo=ZACgAGQAoAABCS4!&rf=photolist&t=5)]( https://liaochan.github.io/leo/)
