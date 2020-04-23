---
layout: post
title: Automatic Textual Evidence Mining in COVID-19 Literature
---

On *March 16th, 2020*, White House released this [Call to Action to the Tech Community on New Machine Readable COVID-19 Dataset](https://www.cccblog.org/2020/03/16/news-call-to-action-to-the-tech-community-on-new-machine-readable-covid-19-dataset/?utm_source=feedblitz&utm_medium=FeedBlitzRss&utm_campaign=cccblog). Our [Data Mining Group](http://dm1.cs.uiuc.edu/) in [CS@UIUC](https://cs.illinois.edu/) has created a literature search interface, **EvidenceMiner**, for automatic textual evidence mining for COVID-19 on the [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) corpus (2020-03-13). 


## EvidenceMiner: System Architecture
Our EvidenceMiner system on COVID-19 can be found [here]().

Below is the overal architecture of the EvidenceMiner system. It consists of two major components: an open information extraction pipeline and a textual evidence retrieval and analysis pipeline. The open information extraction pipeline includes two functional modules: (1) distantly supervised NER, and (2) meta-pattern-based open information extraction; whereas the textual evidence retrieval and analysis pipeline includes three functional modules: (1) textual evidence search, (2) annotation result visualization in the original document, and (3) the most frequent entity and relation summarization. More details of the EvidenceMiner system can be found in our [ACL paper]().

![architecture](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/architecture.png?raw=True)


## EvidenceMiner: Results on COVID-19

### Textual Evidence Retrieval

Method | nDCG@1 | nDCG@5 | nDCG@10
-----------------------------------
BM25 | 0.714 | 0.720 | 0.746 
LitSense | 0.599 | 0.624 | 0.658 
EvidenceMiner | **0.855** | **0.861** | **0.889**

### Case Studies



## Contact
Our team for creating this EvidenceMiner for COVID-19:
- **Xuan Wang** ([xwang174@illinois.edu](xwang174@illinois.edu)): Please contact me if you have any questions or suggestions for this system.
- **Weili Liu** ([weilil2@illinois.edu](xs22@illinois.edu))
- **Aabhas Chauhan** ([aabhasc2@illinois.edu](bl17@illinois.edu))
- **Yingjun Guan** ([yingjun2@illinois.edu](yingjun2@illinois.edu))


## Citation
If you find our EvidenceMiner for COVID-19 useful, please cite our [paper](). Thanks!



