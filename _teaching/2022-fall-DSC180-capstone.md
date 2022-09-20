---
title: "2022-Fall-DSC180B14-Capstone: Weakly Supervised NLP"
collection: teaching
type: "Undergraduate Class"
permalink: /teaching/2022-fall-DSC180B14-capstone
venue: "HDSI, UCSD"
date: 2022-09-28
location: "La Jolla, CA"
---

**Class Time**: Wednesdays, 11 to 11:50 AM Pacific Time.  **Room**: [https://ucsd.zoom.us/j/91491702947](https://ucsd.zoom.us/j/91491702947).

Overview
======

This capstone section talks about text mining and natural language processing with a focus on (extremely) weakly supervsed methods. We will explore cutting-edge research papers in these areas together and try to replicate some experiments for a deeper, better understanding. 

We will mostly have discussions in a Q&A form, instead of traditional lectures. The discussions will be online over Zoom. 

Papers to Read
======

* [Contextualized Weak Supervision for Text Classification](https://www.dropbox.com/s/9pn0pg9pm5raj86/%5BACL%2720%5DContextualized%20Weak%20Supervision%20for%20Text%20Classification.pdf?dl=1) <br/>
Dheeraj Mekala and Jingbo Shang. **ACL** 2020. [[code](https://github.com/dheeraj7596/ConWea)]

* [X-Class: Text Classification with Extremely Weak Supervision](https://arxiv.org/abs/2010.12794) <br/>
Zihan Wang, Dheeraj Mekala and Jingbo Shang. **NAACL** 2021. [[code](https://github.com/ZihanWangKi/XClass)]


**Tips**
1. These two papers are both working on weakly supervised text classification. Please read them one by one. 
2. The Github README files also provide useful information.
3. PDFs of these papers can be found online for free.


Schedule
======

Week | Date  | Discussion Focus
1    | 09/28 | General Overview (a short lecture by Jingbo Shang)
2    | 10/05 | [Introduction & Motivation](#week2)
3    | 10/12 | [Datasets and Experiment Design](#week3)
4    | 10/19 | [Experimental Results - Analysis](#week4)
5    | 10/26 | [Experimental Results - Replication](#week5)
6    | 11/02 | [Case Studies](#week6)
7    | 11/09 | [Application Brainstorming](#week7)
8    | 11/16 | [Possible Extension](#week8)
9    | 11/23 | [Report Writing Discussion](#week9)
10   | 11/30 | [Elevator Pitch](#week10)


Discussion Questions
======

### Week 2: Introduction & Motivation {#week2}

1. Why do we want to study weakly supervised text classification? What's the advantage of weak supervision over full supervision?
2. What's the major problem when someone is going to build a fully supervised text classifier for a new corpus? Is there any human effort?
3. What's the motivation of ConWea? Compared with traditional weak supervision (e.g., counting keywords via string match), which parts do you believe are novel?
4. What's the motivation of X-Class? Compared with ConWea and traditional weak supervision, what are the major invotations in X-Class?


### Week 3: Datasets and Experiment Design {#week3}

1. How many datasets are used in the papers? How many domains and classification scenarios are covered?
2. Why do we want to use such a diverse set of datasets? How this is related to the claims in the papers?
3. Why does ConWea have slightly different evaluation settings than X-Class? Is the experiment design related to the claims in the paper?


### Week 4: Experimental Results - Analysis {#week4}

1. Please outline the claims in these two papers.
2. How can we understand each table and figure? What are the takeaways? One or two sentences per table/figure should be enough.
3. For each claim, where are the experimental results supporting it?


### Week 5: Experimental Results - Replication {#week5}

We will do something based on X-Class repo and a small dataset. The details will come soon. Stay tuned.


### Week 6: Case Studies {#week6}

1. Why do we need case studies in addition to the quantitative results?
2. How case studies further the claims in the papers?
3. Do you have any interesting findings from either the case studies presented in the papers or the results you got from Week 5?


### Week 7: Application Brainstorming {#week7}

1. What kind of applications do you think could be benefited from weakly supervised text classification? Why?
2. Try to think broadly for more domains/languages.
3. Based on your proposed applications, can we apply ConWea/X-Class directly?
2. Do you think there is some necessary adaption? If yes, how? If no, why?


### Week 8: Possible Extension {#week8}

1. What are the drawbacks of these two papers? Do you see any limitations?
2. Can we do better in order to address these limitations?


### Week 9: Report Writing Discussion {#week9}

1. Do you have any questions about the final report writing?
2. How to prepare informative Figures and Tables?
3. How to properly cite previous work?
4. How to make the proposal look more promising?


### Week 10: Elevator Pitch {#week10}

We will have a timed rehearsal for the evevator pitch. 