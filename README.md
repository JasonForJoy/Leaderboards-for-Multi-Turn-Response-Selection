# Multi-Turn Response Selection in Retrieval-Based Chatbots

Multi-turn response selection in retrieval-based chatbots is a task which aims to select the best-matched response from a set of candidates, given the context of a conversation. This task is attracting more and more attention in academia and industry. However, no one has maintain a leaderboard and a collection of popular papers and datasets yet. To make it convenient for researchers to get in touch with the state-of-the-art studies on this task, we did this in this repository.

## Datasets

### Ubuntu Dialogue Corpus V1

[Lowe et al. (2015)](https://www.aclweb.org/anthology/W15-4640.pdf) released the original version. [Download](https://github.com/npow/ubottu) <br>
[Xu et al. (2016)](https://arxiv.org/pdf/1605.05110.pdf) released a version in which numbers, paths and URLs were replaced by placeholders. [Download](https://www.dropbox.com/s/2fdn26rj6h9bpvl/ubuntu_data.zip) <br>
[Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version based on Xu et al. (2016) in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1-rNv34hLoZr300JF3v7nuLswM7GRqeNc/view)

### Ubuntu Dialogue Corpus V2

[Lowe et al. (2017)](http://dad.uni-bielefeld.de/index.php/dad/article/view/3698) released the original version. [Download](https://github.com/rkadlec/ubuntu-ranking-dataset-creator) <br>
[Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1tS_VC47z8CVPr-tZu0U4JEEwBT04N6ks/view)

### Douban Conversation Corpus

[Wu et al. (2017)](https://www.aclweb.org/anthology/P17-1046.pdf) released the original version. [Download](https://github.com/MarkWuNLP/MultiTurnResponseSelection) <br>
[Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1Cwt5BC_WDr1N_-TYaOMSHuOXLKAxXoMQ/view)

### E-commerce Corpus

[Zhang et al. (2018)](https://www.aclweb.org/anthology/C18-1317.pdf) released the original version. [Download](https://drive.google.com/file/d/154J-neBo20ABtSmJDvm7DK0eTuieAuvw/view) <br>
[Gu et al. (2019)](https://dl.acm.org/citation.cfm?id=3358140) released a version in which contexts and responses are assigned ids to track them. [Download](https://drive.google.com/file/d/1vy2bcTCLm1Dzsdvh0cvPIw0XzrTK06us/view)


## Leaderboard

### Ubuntu Dialogue Corpus V1

| Model                   |  R_2@1  |  R_10@1  |  R_10@2  |  R_10@5  |  Paper and Code  |
| ----------------------- | ------- | -------- | -------- | -------- | ---------------- |
| IOI (Tao et al., 2019)  |  0.947  |  0.796   |  0.894   |  0.974   | [One Time of Interaction May Not Be Enough: Go Deep with an Interaction-over-Interaction Network for Response Selection in Dialogues](https://github.com/chongyangtao/IOI) |
| IMN (Gu et al., 2019)   |  0.946  |  0.794   |  0.889   |  0.974   | [Interactive matching network for multi-turn response selection in retrieval-based chatbots](https://github.com/JasonForJoy/IMN) |
| MRFN (Tao et al., 2019) |  0.945  |  0.786   |  0.886   |  0.976   | [Multi-Representation Fusion Network for Multi-Turn Response Selection in Retrieval-Based Chatbots](https://github.com/chongyangtao/MRFN) |
| DAM (Zhou et al., 2018) |  0.938  |  0.767   |  0.874   |  0.969   | [Multi-turn response selection for chatbots with deep attention matching network](https://github.com/baidu/Dialogue/tree/master/DAM) |
| DUA (Zhang et al., 2018)|  -      |  0.752   |  0.868   |  0.962   | [Modeling multiturn conversation with deep utterance aggregation](https://github.com/cooelf/DeepUtteranceAggregation) |
| SMN (Wu et al., 2017)   |  0.926  |  0.726   |  0.847   |  0.961   | [Sequential matching network: A new architecture for multi-turn response selection in retrieval-based chatbots](https://github.com/MarkWuNLP/MultiTurnResponseSelection) |
