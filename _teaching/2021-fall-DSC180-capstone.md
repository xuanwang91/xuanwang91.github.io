---
title: "2021-Fall-DSC180A02-Capstone: Text Mining and NLP"
collection: teaching
type: "Undergraduate Class"
permalink: /teaching/2021-fall-DSC180a-capstone
venue: "HDSI, UCSD"
date: 2021-09-29
location: "La Jolla, CA"
---

**Class Time**: Wednesdays, 1 to 1:50 PM Pacific Time.  **Room**: [https://ucsd.zoom.us/j/91491702947](https://ucsd.zoom.us/j/91491702947).

Overview
======

This capstone section mainly focuses on text mining and natural language processing. We will explore cutting-edge research papers in these areas together and try to replicate some experiments for a deeper, better understanding. 

We will mostly have discussions in a Q&A form, instead of traditional lectures. Due to the COVID-19, the discussions will be online over Zoom. 

Papers to Read
======

* Mining Quality Phrases from Massive Text Corpora <br/>
Jialu Liu\*, Jingbo Shang\*, Chi Wang, Xiang Ren and Jiawei Han. **SIGMOD** 2015. [[code](https://github.com/shangjingbo1226/SegPhrase)]

* Automated Phrase Mining from Massive Text Corpora <br/>
Jingbo Shang, Jialu Liu, Meng Jiang, Xiang Ren, Clare R Voss and Jiawei Han. **TKDE** 2018. [[code](https://github.com/shangjingbo1226/AutoPhrase)]

* UCPhrase: Unsupervised Context-aware Quality Phrase Tagging <br/>
Xiaotao Gu\*, Zihan Wang\*, Zhenyu Bi, Yu Meng, Liyuan Liu, Jiawei Han and Jingbo Shang. **KDD 2021**. [[arXiv:2105.14078](https://arxiv.org/abs/2105.14078)] [[code](https://github.com/xgeric/UCPhrase-exp)]

**Tips**
1. These three papers are highly related. Please read them one by one. 
2. The Github README files also provide useful information.
3. PDFs of these papers can be found online or [here](https://www.dropbox.com/sh/42hsaq4zsod7j8w/AACv2e2FJPjIDOVvYP22GmrVa?dl=0)


Schedule
======

Week | Date  | Discussion Focus
1    | 09/29 | General Overview (a short lecture by Jingbo Shang)
2    | 10/06 | [Introduction & Motivation](#week2)
3    | 10/13 | [Datasets and Experiment Design](#week3)
4    | 10/20 | [Experimental Results - Analysis](#week4)
5    | 10/27 | [Experimental Results - Replication](#week5)
6    | 11/03 | [Case Studies](#week6)
7    | 11/10 | [Application Brainstorming](#week7)
8    | 11/17 | [Possible Extension](#week8)
9    | 11/24 | [Report Writing Discussion](#week9)
10   | 12/01 | [Elevator Pitch](#week10)


Discussion Questions
======

### Week 2: Introduction & Motivation {#week2}

1. Why do we want to study phrase mining? What's the advantage of phrases over unigrams?
2. What's the major problem when someone is going to apply SegPhrase to a new corpus? Is there any human effort?
3. What's the motivation of AutoPhrase? Compared with SegPhrase, which parts do you believe are novel?
4. What's the motivation of UCPhrase? Compared with AutoPhrase and SegPhrase, what are the major invotations in UCPhrase?


### Week 3: Datasets and Experiment Design {#week3}

1. How many datasets are used in the papers? How many domains and languages are covered?
2. Why do we want to use such a diverse set of datasets? How this is related to the claims in the papers?
3. Why do we want to evaluate the results following the pooling strategy? Think about how much human effort is required, if we are not using pooling.
4. Why the UCPhrase has some different evaluation settings than AutoPhrase and SegPhrase?


### Week 4: Experimental Results - Analysis {#week4}

1. Please outline the claims in these three papers.
2. How can we understand each table and figure? What are the takeaways? One or two sentences per table/figure should be enough.
3. For each claim, where are the experimental results supporting it?


### Week 5: Experimental Results - Replication {#week5}

1. Carefully check the README file in the AutoPhrase repo. What is the relation between `autophrase.sh` and `phrasal_segmentation.sh`? 
2. Try to run AutoPhrase using the `DBLP.5k.txt` and `DBLP.txt` datasets as the input corpus. It should be runnable on your laptop. Let me know if you encounter any issue.
3. Please eyeball the results from the two runs and try to compare them from the following aspects:
   - The number of high-quality phrases (e.g., > 0.5)
   - Unigram phrase vs. multi-word phrase
   - Top a few high-quality phrases (e.g., >0.9) vs. those borderline phrases (e.g., ~0.5)


### Week 6: Case Studies {#week6}

1. Why do we need case studies in addition to the quantitative results?
2. How case studies further the claims in the papers?
3. Do you have any interesting findings from either the case studies presented in the papers or the results you got from Week 5?


### Week 7: Application Brainstorming {#week7}

1. What kind of applications do you think could be benefited from phrase mining? Why?
2. Try to think broadly for more domains/languages.
3. Based on your proposed applications, can we apply SegPhrase/AutoPhrase directly?
2. Do you think there is some necessary adaption? If yes, how? If no, why?


### Week 8: Possible Extension {#week8}

1. What are the drawbacks of these three papers? Do you see any limitations?
2. Can we do better in order to address these limitations?


### Week 9: Report Writing Discussion {#week9}

1. Do you have any questions about the final report writing?
2. How to prepare informative Figures and Tables?
3. How to properly cite previous work?
4. How to make the proposal look more promising?


### Week 10: Elevator Pitch {#week10}

We will have a timed rehearsal for the evevator pitch. 