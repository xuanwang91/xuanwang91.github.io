---
title: "2020-Fall-CSE291-Advanced Data-Driven Text Mining"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2020-fall-CSE291-TM
venue: "CSE, UCSD"
date: 2020-09-28
location: "La Jolla, CA"
---

**Class Time**: Tuesdays and Thursdays, 9:30AM to 10:50AM.  **Room**: [https://ucsd.zoom.us/j/93162206472](https://ucsd.zoom.us/j/93162206472).  **Piazza**: [piazza.com/ucsd/fall2020/cse291a00](https://piazza.com/ucsd/fall2020/cse291a00)


Online Lecturing
======

Due to the COVID-19, this course will be delivered over Zoom. All lectures will be recorded.

Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world text data. It will put emphasis on unsupervised, weakly supervised, and distantly supervised methods for text mining problems, including information retrieval, open-domain information extraction, text summarization (both extractive and generative), and knowledge graph construction. Bootstrapping, comparative analysis, learning from seed words and existing knowledge bases will be the key methodologies.

There is no textbook required, but there are recommended readings for each lecture (at the end of the slides).

- You MUST enroll for 4 units
    - We need your time commitment for projects
    - Feel free to audit the course with 0 unit


Prerequisites
======

Knowledge about Machine Learning and Data Mining; Comfortable coding using Python, C/C++, or Java; Math and Stat skills.

TA and Office Hours
======

- Jingbo Shang
    - Office Hour: Wednesdays, 10 to 11 AM
    - Zoom link: https://ucsd.zoom.us/my/jshang

- **TA**: Dheeraj Mekala (dmekala AT eng.ucsd.edu)
    - Office Hour: Tuesdays, 5 to 6 PM
    - Zoom Link: https://ucsd.zoom.us/j/97330988404

Note: all times are in **Pacific Time**.

Grading
======

- Homework: 20%. There will be two homework assignments. 10% each. 
- Text Mining Challenge: 30%.
- Project: 50%.
- You should complete all work individually, except for the Project.
- Late submissions are NOT accepted.

Lecture Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

**HW Note**: All HWs due before the lecture time 9:30 AM PT in the morning. 

Week | Date        | Topic & Slides                                                  | Events
1    | 10/01 (Thu) | Intro, Logistics, and Course Project [[slides](https://www.dropbox.com/s/reh9cdupvef8z34/lecture0_intro.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/7dxwc218edt4069/AAD9T0Q6F33cJd57PooHl5j-a?dl=0)] |
2    | 10/06 (Tue) | Basics: Zipf's Law, Bags-of-words, and TF-IDF [[slides](https://www.dropbox.com/s/fu4uk8gz2nc1v15/lecture1_text_basics.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/l5u2ictdekrtzm1/AADYRXzoAilCTfsGkMpV8Ngaa?dl=0)] | HW1 out
2    | 10/08 (Thu) | Word Embedding: word2vec and GloVe [[slides](https://www.dropbox.com/s/2xkgrjggiy98l1m/lecture2_word2vec.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/gynerol8jqnmn0h/AAD-QdWWheQnG_GmSmwYTpEra?dl=0)] |
3    | 10/13 (Tue) | Language Models: from N-Gram to Neural LMs [[slides](https://www.dropbox.com/s/day8thlstztykuf/lecture3_lm.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/wj4bc5u2ekp228l/AAAyt3FxdhOQbwgvBKQ_ecTEa?dl=0)] |
3    | 10/15 (Thu) | Information Retrieval: from BM25 to Learning to Rank [[slides](https://www.dropbox.com/s/j81l7prcg87ifus/lecture4_ir.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/z2zzmq9rug844cp/AAAKRr6ughK_RBa-IWeEVfUIa?dl=0)] | Project Proposal Due (End of the Day)
4    | 10/20 (Tue) | Sentiment Analysis and Document Classification [[slides](https://www.dropbox.com/s/wljpuhvox9hxnbc/lecture5_sentiment.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/gcbvawtx5hnd5vy/AABanutPv3ZsuUJ2iRyqkU24a?dl=0)] |
4    | 10/22 (Thu) | Topic Modeling: PLSA, LDA, and HMM [[slides](https://www.dropbox.com/s/es7k0dievp1l3g3/lecture6_lda.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/r1bk26e1qdhx718/AACxdvf6p9o4MjX17n-pMK8Ca?dl=0)] | HW1 Due (before lecture time), DM challenge roll-out
5    | 10/27 (Tue) | Phrase Mining: from Unigrams to Multi-word Phrases [[slides](https://www.dropbox.com/s/ajehhah026vh0w8/lecture7_phrase.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/z6nfgt4wnz6eb69/AAAwo0Vytybtvn6mnQADTGm8a?dl=0)]            | HW2 out
5    | 10/29 (Thu) | Entity Set Expansion: from Seed Words to Sets [[slides](https://www.dropbox.com/s/6znm25o1tr9prg5/lecture8_set_expan.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/rlf2nn99fj5zjpg/AADNalVIPdoHE_BV6buZ-Jy4a?dl=0)] |
6    | 11/03 (Tue) | Entity Recognition: from Supervised to Data-Driven [[slides](https://www.dropbox.com/s/5e4puq198iwlg81/lecture9_ner.pdf?dl=1)] [[recording](https://www.dropbox.com/sh/5ngvwkqu3y3c3yx/AAAChta-14LfWv-wzA830sqza?dl=0)] |
6    | 11/05 (Thu) | Relation Extraction and Attribute Discovery [[slides](https://www.dropbox.com/s/xomolpsns48lozy/lecture10_open_ie.pdf?dl=1)] |
7    | 11/10 (Tue) | Text-Rich Network: a Collaboration between Texts and Networks   |
7    | 11/12 (Thu) | Topic Taxonomy Construction                                     |
8    | 11/17 (Tue) | Weakly Supervised Text Classification                           |
8    | 11/19 (Thu) | Text Summarization: Extractive vs. Generative                   | HW2 due (before lecture time)
9    | 11/24 (Tue) | Question-Answering and Machine Reading Comprehending            | DM challenge due
9    | 11/26 (Thu) | (Thanksgiving Break)                                            |
10   | 12/01 (Tue) | Domain-Specific Applications: Biomedical Text Mining            |
10   | 12/03 (Thu) | Project Presentations                                           |
11   | 12/08 (Tue) | Project Presentations                                           |
11   | 12/10 (Thu) | Project Presentations                                           |

Homework (20%)
======

- **HW1.** Text Classification with Different Techniques. [[zip](https://www.dropbox.com/s/59b5mwx82xxfc3n/HW-1.zip?dl=1)]
    - Due: Oct 22, before lecture time
- **HW2.** Phrase Mining Applications and Future Work. [[PDF](https://www.dropbox.com/s/42xtzd12uljy4mb/CSE291_Text_Mining___HW2.pdf?dl=1)].
    - Due: Nov 19, before lecture time

Data Mining Challenge (30%)
======

It is a individual-based text mining competition with quantitative evaluation. 
The challenge runs **from Oct 20 2020 0:00:01 AM to Nov 24, 2020 4:59:59 PM PT**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: [[dataset](https://www.dropbox.com/s/pc7hb7m0x62fsi9/Challenge.zip?dl=1)] [[challenge statement](https://www.dropbox.com/s/5nzjspyhd8a5r2u/CSE291_Text_Mining___DM_Challenge.pdf?dl=1)]
- Kaggle challenge link: [https://www.kaggle.com/c/cse291-data-driven-text-mining](https://www.kaggle.com/c/cse291-data-driven-text-mining)

Project (50%)
======

**Overview**
- Team-Based Open-Ended Project
    - 1 to 4 members per team. More members, higher expectation.
    - 3 to 4 members are recommended, given the limited presentation slots.

**Final Deliverables**
- Project Proposal (5%)
    - Define your own research problem and justify its importance
    - Be ambitious! We could aim for ACL 2021 conference!
- Research Paper (20%)
    - Report due on Dec 13, End of the day, Pacific Time. 
    - Write a 5 to 9 pages report (research-paper like following ACL template). The pages here do not include references.
    - Come up with your hypothesis and find some datasets for verification
    - Design your own models or try a large variety of existing models
    - Submit your codes and datasets; Github repos are welcome
    - Up to 5% bonus for working demos/apps towards the total course grades
- Presentation (20%)
    - The orders will be decided randomly after the teams are formed.
    - The slides must be ready 2 days before the presentation date. So other students can have the access and think about questions.
    - The presentation follows a typical conference style: 20 mins for each team including Q&A
- Question Asking and Handling (5%)
    - Asking questions is an important part of research. You are strongly encouraged to ask 
    questions to other teams. It will be a part of your presentation grade.
    - Handling questions is also an important skill for researchers. 
