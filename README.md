# Multi-Turn Response Selection in Retrieval-Based Chatbots

Multi-turn response selection in retrieval-based chatbots is a task which aims to select the best-matched response from a set of candidates, given the context of a conversation. This task is attracting more and more attention in academia and industry. However, no one has maintain a leaderboard and a collection of popular papers and datasets yet. The main objective of this repository is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art studies on this task, which serves as a stepping stone for further research. 


## Datasets

### Ubuntu Dialogue Corpus V1

- [Lowe et al. (2015)](https://www.aclweb.org/anthology/W15-4640.pdf) released the original version. [Download](https://github.com/npow/ubottu) <br>
- [Xu et al. (2016)](https://arxiv.org/pdf/1605.05110.pdf) released a version in which numbers, paths and URLs were replaced by placeholders. [Download](https://www.dropbox.com/s/2fdn26rj6h9bpvl/ubuntu_data.zip) <br>
- [Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version based on Xu et al. (2016) in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1-rNv34hLoZr300JF3v7nuLswM7GRqeNc/view)

### Ubuntu Dialogue Corpus V2

- [Lowe et al. (2017)](http://dad.uni-bielefeld.de/index.php/dad/article/view/3698) released the original version. [Download](https://github.com/rkadlec/ubuntu-ranking-dataset-creator) <br>
- [Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1tS_VC47z8CVPr-tZu0U4JEEwBT04N6ks/view)

### Douban Conversation Corpus

- [Wu et al. (2017)](https://www.aclweb.org/anthology/P17-1046.pdf) released the original version. [Download](https://github.com/MarkWuNLP/MultiTurnResponseSelection) <br>
- [Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1Cwt5BC_WDr1N_-TYaOMSHuOXLKAxXoMQ/view)

### E-commerce Corpus

- [Zhang et al. (2018)](https://www.aclweb.org/anthology/C18-1317.pdf) released the original version. [Download](https://drive.google.com/file/d/154J-neBo20ABtSmJDvm7DK0eTuieAuvw/view) <br>
- [Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1vy2bcTCLm1Dzsdvh0cvPIw0XzrTK06us/view)



## Leaderboard

### Ubuntu Dialogue Corpus V1

| Model                   |  R_2@1  |  R_10@1  |  R_10@2  |  R_10@5  |  Paper and Code  |
| ----------------------- | ------- | -------- | -------- | -------- | ---------------- |
| MSN (Yuan et al, 2019)  | -       |  0.800   |  0.899   |  0.978   | Multi-hop Selector Network for Multi-turn Response Selection in Retrieval-based Chatbots |
| IOI (Tao et al., 2019)  |  0.947  |  0.796   |  0.894   |  0.974   | [One Time of Interaction May Not Be Enough: Go Deep with an Interaction-over-Interaction Network for Response Selection in Dialogues](https://github.com/chongyangtao/IOI) |
| IMN (Gu et al., 2019)   |  0.946  |  0.794   |  0.889   |  0.974   | [Interactive Matching Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/JasonForJoy/IMN) |
| MRFN (Tao et al., 2019) |  0.945  |  0.786   |  0.886   |  0.976   | [Multi-Representation Fusion Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/chongyangtao/MRFN) |
| DAM (Zhou et al., 2018) |  0.938  |  0.767   |  0.874   |  0.969   | [Multi-Turn Response Selection for Chatbots with Deep Attention Matching Network](https://github.com/baidu/Dialogue/tree/master/DAM) |
| DUA (Zhang et al., 2018)|  -      |  0.752   |  0.868   |  0.962   | [Modeling Multi-Turn Conversation with Deep Utterance Aggregation](https://github.com/cooelf/DeepUtteranceAggregation) |
| SMN (Wu et al., 2017)   |  0.926  |  0.726   |  0.847   |  0.961   | [Sequential Matching Network: A New Architecture for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/MarkWuNLP/MultiTurnResponseSelection) |


### Ubuntu Dialogue Corpus V2

| Model                        |  R_2@1  |  R_10@1  |  R_10@2  |  R_10@5  |  Paper and Code  |
| ---------------------------- | ------- | -------- | -------- | -------- | ---------------- |
| IMN (Gu et al., 2019)        |  0.945  |  0.771   |  0.886   |  0.979   | [Interactive Matching Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/JasonForJoy/IMN) |
| HRDE-LTC (Yoon et al., 2018) |  0.915  |  0.652   |  0.815   |  0.966   | [Learning to Rank Question-Answer Pairs using Hierarchical Recurrent Encoder with Latent Topic Clustering](https://github.com/david-yoon/QA_HRDE_LTC) |


### Douban Conversation Corpus

| Model                   |  MAP  |  MRR  |  P@1  |  R_10@1  |  R_10@2  |  R_10@5  |  Paper and Code  |
| ----------------------- | ----- | ----- | ----- | -------- | -------- | -------- | ---------------- |
| MSN (Yuan et al, 2019)  | 0.587 | 0.632 | 0.470 |  0.295   |  0.452   |  0.788   | Multi-hop Selector Network for Multi-turn Response Selection in Retrieval-based Chatbots |
| IOI (Tao et al., 2019)  | 0.573 | 0.621 | 0.444 |  0.269   |  0.451   |  0.786   | [One Time of Interaction May Not Be Enough: Go Deep with an Interaction-over-Interaction Network for Response Selection in Dialogues](https://github.com/chongyangtao/IOI) |
| IMN (Gu et al., 2019)   | 0.570 | 0.615 | 0.433 |  0.262   |  0.452   |  0.789   | [Interactive Matching Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/JasonForJoy/IMN) |
| MRFN (Tao et al., 2019) | 0.571 | 0.617 | 0.448 |  0.276   |  0.435   |  0.783   | [Multi-Representation Fusion Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/chongyangtao/MRFN) |
| DAM (Zhou et al., 2018) | 0.550 | 0.601 | 0.427 |  0.254   |  0.410   |  0.757   | [Multi-Turn Response Selection for Chatbots with Deep Attention Matching Network](https://github.com/baidu/Dialogue/tree/master/DAM) |
| DUA (Zhang et al., 2018)| 0.551 | 0.599 | 0.421 |  0.243   |  0.421   |  0.780   | [Modeling Multi-Turn Conversation with Deep Utterance Aggregation](https://github.com/cooelf/DeepUtteranceAggregation) |
| SMN (Wu et al., 2017)   | 0.529 | 0.569 | 0.397 |  0.233   |  0.396   |  0.724   | [Sequential Matching Network: A New Architecture for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/MarkWuNLP/MultiTurnResponseSelection) |


### E-commerce Corpus

| Model                   |  R_10@1  |  R_10@2  |  R_10@5  |  Paper and Code  |
| ----------------------- | -------- | -------- | -------- | ---------------- |
| IMN (Gu et al., 2019)   |  0.621   |  0.797   |  0.964   | [Interactive Matching Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/JasonForJoy/IMN) |
| MSN (Yuan et al, 2019)  |  0.606   |  0.770   |  0.937   | Multi-hop Selector Network for Multi-turn Response Selection in Retrieval-based Chatbots |
| IOI (Tao et al., 2019)  |  0.563   |  0.768   |  0.950   | [One Time of Interaction May Not Be Enough: Go Deep with an Interaction-over-Interaction Network for Response Selection in Dialogues](https://github.com/chongyangtao/IOI) |
| DUA (Zhang et al., 2018)|  0.501   |  0.700   |  0.921   | [Modeling Multi-Turn Conversation with Deep Utterance Aggregation](https://github.com/cooelf/DeepUtteranceAggregation) |
| SMN (Wu et al., 2017)   |  0.453   |  0.654   |  0.886   | [Sequential Matching Network: A New Architecture for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/MarkWuNLP/MultiTurnResponseSelection) |



## Papers
In addition to the studies mentioned above, there are stil a lot of great studies on multi-turn response selection worth reading. We list a part of them below. <br>

- **Utterance-to-Utterance Interactive Matching Network for Multi-Turn Response Selection in Retrieval-Based Chatbots**. *Jia-Chen Gu, Zhen-Hua Ling, Quan Liu*. TASLP.
- **Dually Interactive Matching Network for Personalized Response Selection in Retrieval-Based Chatbots**. *Jia-Chen Gu, Zhen-Hua Ling, Xiaodan Zhu, Quan Liu*. EMNLP 2019.
- **Sampling Matters! An Empirical Study of Negative Sampling Strategies for Learning of Matching Models in Retrieval-based Dialogue Systems**. *Jia Li, Chongyang Tao, wei wu, Yansong Feng, Dongyan Zhao, Rui Yan*. EMNLP 2019.
- **Learning a Matching Model with Co-teaching for Multi-turn Response Selection in Retrieval-based Dialogue Systems**. *Jiazhan Feng, Chongyang Tao, Wei Wu, Yansong Feng, Dongyan Zhao, Rui Yan*. ACL 2019.
- **Training Neural Response Selection for Task-Oriented Dialogue Systems**. *Matthew Henderson, Ivan Vulić, Daniela Gerz, Iñigo Casanueva, Paweł Budzianowski, Sam Coope, Georgios Spithourakis, Tsung-Hsien Wen, Nikola Mrkšić, Pei-Hao Su*. ACL 2019.
- **DSTC7 Task 1: Noetic End-to-End Response Selection**. *Chulaka Gunasekara, Jonathan K. Kummerfeld, Lazaros Polymenakos, Walter Lasecki*. ACL 2019 Workshop.
- **Sequential Attention-based Network for Noetic End-to-End Response Selection**. *Qian Chen, Wen Wang*. AAAI 2019 Workshop on DSTC 7.
- **Building Sequential Inference Models for End-to-End Response Selection**. *Jia-Chen Gu, Zhen-Hua Ling, Yuping Ruan, Quan Liu*. AAAI 2019 Workshop on DSTC 7.
- **Learning Matching Models with Weak Supervision for Response Selection in Retrieval-based Chatbots**. *Yu Wu, Wei Wu, Zhoujun Li, Ming Zhou*. ACL 2018.
- **Response Ranking with Deep Matching Networks and External Knowledge in Information-seeking Conversation Systems**. *Liu Yang, Minghui Qiu, Chen Qu, Jiafeng Guo, Yongfeng Zhang, W. Bruce Croft, Jun Huang, Haiqing Chen*. SIGIR 2018.
- **Improving Response Selection in Multi-turn Dialogue Systems by Incorporating Domain Knowledge**. *Debanjan Chaudhuri, Agustinus Kristiadi, Jens Lehmann, Asja Fischer*. CONLL 2018.
- **Enhance word representation for out-of-vocabulary on Ubuntu dialogue corpus**. *Jianxiong Dong, Jim Huang*. ArXiv.
- **Multi-view Response Selection for Human-Computer Conversation**. *Xiangyang Zhou, Daxiang Dong, Hua Wu, Shiqi Zhao, Dianhai Yu, Hao Tian, Xuan Liu, Rui Yan*. EMNLP 2016.
- **Learning to Respond with Deep Neural Networks for Retrieval-Based Human-Computer Conversation System**. *Rui Yan, Yiping Song, Hua Wu*. SIGIR 2016.



## Update
Although we work very hard to list more work, the studies we select to present in this repository are by no means complete. To this end, we welcome more people to participate in the maintenance of this project. Please feel free to open issues, pull requests or contact us (gujc@mail.ustc.edu.cn).
