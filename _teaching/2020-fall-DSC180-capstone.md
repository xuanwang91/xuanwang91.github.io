---
title: "2020-Fall-DSC180A05-Capstone: Text Mining and NLP"
collection: teaching
type: "Undergraduate Class"
permalink: /teaching/2020-fall-DSC180a-capstone
venue: "HDSI, UCSD"
date: 2020-10-05
location: "La Jolla, CA"
---

**Class Time**: Wednesdays, 9 to 9:50 AM Pacific Time.  **Room**: [https://ucsd.zoom.us/j/91491702947](https://ucsd.zoom.us/j/91491702947).  **Piazza**: [piazza.com/ucsd/fall2020/dsc180a05](https://piazza.com/ucsd/fall2020/dsc180a05).

Overview
======

This capstone section mainly focuses on text mining and natural language processing. We will explore cutting-edge research papers in these areas together and try to replicate some experiments for a deeper, better understanding. 

We will mostly have discussions in a Q&A form, instead of traditional lectures. Due to the COVID-19, the discussions will be online over Zoom. 

Papers to Read
======

* [Mining Quality Phrases from Massive Text Corpora](https://www.dropbox.com/s/9mis5qt4d44iysp/%5BSIGMOD%2715%5DMining%20Quality%20Phrases%20from%20Massive%20Text%20Corpora.pdf?dl=1) <br/>
Jialu Liu\*, Jingbo Shang\*, Chi Wang, Xiang Ren and Jiawei Han. **SIGMOD** 2015. [[code](https://github.com/shangjingbo1226/SegPhrase)]

* [Automated Phrase Mining from Massive Text Corpora](https://www.dropbox.com/s/47urzwmmg5wp2us/%5BTKDE%2718%5DAutomated%20Phrase%20Mining%20from%20Massive%20Text%20Corpora.pdf?dl=1) <br/>
Jingbo Shang, Jialu Liu, Meng Jiang, Xiang Ren, Clare R Voss and Jiawei Han. **TKDE** 2018. [[code](https://github.com/shangjingbo1226/AutoPhrase)]

**Tips**
1. These two papers are highly related. Please read them one by one. 
2. The Github README files also provide useful information.


Schedule
======

Week | Date  | Discussion Focus
1    | 10/07 | General Overview (a short lecture by Jingbo Shang) [[recording](https://www.dropbox.com/sh/1vxupk6mm6mjfeg/AAAjj-LZhxv6t-qZ0iuzkWVTa?dl=0)]
2    | 10/14 | [Introduction & Motivation](#week2) [[recording](https://www.dropbox.com/sh/fcy4i2lo0m4aehf/AABZTWuFv0Hc8OBgGCda-pjda?dl=0)]
3    | 10/21 | [Datasets and Experiment Design](#week3) [[recording](https://www.dropbox.com/sh/pjep6vmngh8rd1m/AABOefhkHukl38qJW-U1uf4Qa?dl=0)]
4    | 10/28 | [Experimental Results - Analysis](#week4)
5    | 11/04 | [Experimental Results - Replication](#week5)
6    | 11/11 | [Case Studies](#week6)
7    | 11/18 | [Application Brainstorming](#week7)
8    | 11/25 | [Possible Extension](#week8)
9    | 12/02 | [Possible Extension](#week9)
10   | 12/09 | Elevator Pitch


Discussion Questions
======

### Week 2: Introduction & Motivation {#week2}

1. Why do we want to study phrase mining? What's the advantage of phrases over unigrams?
2. What's the major problem when someone is going to apply SegPhrase to a new corpus? Is there any human effort?
3. What's the motivation of AutoPhrase? Compared with SegPhrase, which parts do you believe are novel?

### Week 3: Datasets and Experiment Design {#week3}

1. How many datasets are used in the papers? How many domains and languages are covered?
2. Why do we want to use such a diverse set of datasets? How this is related to the claims in the papers?
3. Why do we want to evaluate the results following the pooling strategy? Think about how much human effort is required, if we are not using pooling.


### Week 4: Experimental Results - Analysis {#week4}

1. Please outline the claims in these two papers.
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


### Week 8: Possible Extension {#week8}

1. What are the drawbacks of these two papers? Do you see any limitations?
2. Can we do better in order to address these limitations?

### Week 9: Possible Extension {#week9}

1. Based on your proposed applications in Week 7, can we apply SegPhrase/AutoPhrase directly?
2. Do you think there is some necessary adaption? If yes, how? If no, why?


