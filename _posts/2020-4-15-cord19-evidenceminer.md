---
layout: post
title: Automatic Textual Evidence Mining in COVID-19 Literature
---

On *March 16th, 2020*, White House released this [Call to Action to the Tech Community on New Machine Readable COVID-19 Dataset](https://www.cccblog.org/2020/03/16/news-call-to-action-to-the-tech-community-on-new-machine-readable-covid-19-dataset/?utm_source=feedblitz&utm_medium=FeedBlitzRss&utm_campaign=cccblog). Our [Data Mining Group](http://dm1.cs.uiuc.edu/) in [CS@UIUC](https://cs.illinois.edu/) has created a literature search interface, **EvidenceMiner**, for automatic textual evidence mining for COVID-19 on the [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) corpus (2020-03-13). 


## EvidenceMiner: System Architecture
Our EvidenceMiner system on COVID-19 can be found [here]().

Below is the overal architecture of the EvidenceMiner system. It consists of two major components: an open information extraction pipeline and a textual evidence retrieval and analysis pipeline. The open information extraction pipeline includes two functional modules: (1) distantly supervised NER, and (2) meta-pattern-based open information extraction; whereas the textual evidence retrieval and analysis pipeline includes three functional modules: (1) textual evidence search, (2) annotation result visualization in the original document, and (3) the most frequent entity and relation summarization. 

![architecture](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/architecture.png?raw=True)


## EvidenceMiner: Results on COVID-19

### Textual Evidence Retrieval

Method | nDCG@1 | nDCG@5 | nDCG@10
--- | --- | --- | --- | ---
BM25 | 0.714 | 0.720 | 0.746 
LitSense | 0.599 | 0.624 | 0.658 
EvidenceMiner | **0.855** | **0.861** | **0.889**

### Case Studies

Here are some case studies to demonstrate that EvidenceMiner can help scientific discoveries on COVID-19. In the example shown below, scientists want to find some evidence for using ultraviolet (UV) to kill the SARS-COV-2 virus. In the top-retrieved results shown below, we see many supporting sentences such as the top one "Ultraviolet-C (UV-C) radiation represents an alternative to chemical inactivation methods". More interestingly, we found the fifth sentence "Whole UV-inactivated SARS-CoV (UV-V), bearing multiple epitopes and proteins, is a candidate vaccine against this virus" indicating that UV-inactivation also has the potential for vaccine development against the virus. Scientists are very interested in this result that inspired them to conduct UV-related COVID-19 vaccine development.

![sars-cov-2-uv](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/sars-cov-2-uv.png?raw=True)

Moreover, EvidenceMiner allows more flexible queries, such as the relational patterns, if the users are not sure which specific entity to search. In the example shown below, scientists want to find some evidence related to "CORONAVIRUS cause DISEASEORSYNDROME". In the top-retrieved results shown below, we see many highly-related evidence sentences, such as "HCoV-OC43, HCoV-229E, HCoV-HKU1, and HCoV-NL63 cause mild, self-limiting upper respiratory tract infections". This function is supported by our meta-pattern discovery methods and has not been incorporated by any existing systems.

![CORONAVIRUS_cause_DISEASEORSYNDROME](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/CORONAVIRUS_cause_DISEASEORSYNDROME.png?raw=True)

We show some more examples. In the example shown below, doctors want to study if remdesivir is a potential drug treatment for COVID-19. Remdesivir is currently a very actively studied drug that has the potential to be repurposed for COVID-19 treatment. Similarly, in the top-retrieved results shown below, we can see many sentences regarding the clinical trials for remdesivir against COVID-19. An additional example is shown for amodiaquine as a potential drug for COVID-19.

![covid-19-remdesivir](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/covid-19-remdesivir.png?raw=True)

![sars-cov-2-amodiaquine](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/sars-cov-2-amodiaquine.png?raw=True)

Last, we show that EvidenceMiner is also useful for evidence finding for contraversial topics. In the example shown below, people are interested to see if wearing masks can help prevent the COVID-19 spreading. In the top-retrieved results shown below, we see many related statements, among them are clearly two opposite opinions. For example, some statements support the use of masks to prevent the virus, such as "COVID-19 is transmitted by saliva droplets, ..., which can be prevented by wearing masks". While other statements are against the effectiveness of wearing masks, such as "Although surgical masks are in widespread use ..., there is no evidence that wearing these masks can prevent the acquisition of COVID-19 ...". An interesting future work is to classify the opinions by their semantic polarity and even automatically generate summarizations of the evidence retrieval results.

![covid-19-masks](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/covid-19-masks.png?raw=True)


## Contact
Our team for creating this EvidenceMiner for COVID-19:
- **Xuan Wang** ([xwang174@illinois.edu](xwang174@illinois.edu)): Please contact me if you have any questions or suggestions for this system.
- **Weili Liu** ([weilil2@illinois.edu](xs22@illinois.edu))
- **Aabhas Chauhan** ([aabhasc2@illinois.edu](bl17@illinois.edu))
- **Yingjun Guan** ([yingjun2@illinois.edu](yingjun2@illinois.edu))


## Citation
If you find our EvidenceMiner for COVID-19 useful, please cite our [paper](https://arxiv.org/abs/2004.12563). Thanks!



