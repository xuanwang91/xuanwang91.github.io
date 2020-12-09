---
title: "2021-Winter-MGTA415-Working with Unstructured Data"
collection: teaching
type: "Graduate Class"
permalink: /teaching/2021-winter-MGTA415-Unstructured-Data
venue: "Rady Management School, UCSD"
date: 2021-01-04
location: "La Jolla, CA"
---

**Class Time**: Wednesdays, 6PM to 9PM.  **Room**: [https://ucsd.zoom.us/j/95861287987](https://ucsd.zoom.us/j/95861287987).  **Piazza**: TBD


Online Lecturing
======

Due to the COVID-19, this course will be delivered over Zoom: [https://ucsd.zoom.us/j/95861287987](https://ucsd.zoom.us/j/95861287987)

Overview
======

This course mainly focuses on introducing current methods and models that are useful in analyzing and mining real-world unstructured text data. 

As the starting points, we will cover text preprocessing, text classification (e.g., sentiment analysis), topic modeling, word embedding, language models, etc. This course will not only cover the theories and high-level understandings but also some tricks about implementation (e.g., how to use 3rd-party libs, and how to set hyper-parameters). 

For the advanced part, we will talk about unsupervised, weakly supervised, and distantly supervised methods for text mining problems, including information retrieval, open-domain information extraction, text summarization (both extractive and generative), and knowledge graph construction. Bootstrapping, comparative analysis, learning from seed words and existing knowledge bases will be the key methodologies.

We will have a take-home midterm, a few homework assignments, a Kaggle-like competition, and a final (team-based) project. These four parts will have roughly the same weights. 

There is no textbook required, but there are recommended readings for each lecture (at the end of the slides).

If you don't have much experience in data mining, machine learning, etc. Here are some recommended textbooks to review.


- The classical data mining textbook "[Data Mining: Concepts and Techniques](https://books.google.com/books/about/Data_Mining_Concepts_and_Techniques.html?id=pQws07tdpjoC&source=kp_book_description)" by Jiawei Han et al.
- The classical data mining/machine learning book "[Pattern Recognition and Machine Learning](https://books.google.com/books/about/Pattern_Recognition_and_Machine_Learning.html?id=HL4HrgEACAAJ&source=kp_book_description)" by Christopher M. Bishop
- The new "[Dive into Deep Learning](https://d2l.ai/)" book by Aston Zhang et al.


Prerequisites
======

Knowledge about Machine Learning and Data Mining; Comfortable coding using Python, C/C++, or Java; Math and Stat skills.

TA
======

- **Teaching Assistant**: TBD

Office Hours
======

- Jingbo Shang
    - Office Hour: Wednesdays, 10 to 11 AM
    - Zoom link: [https://ucsd.zoom.us/my/jshang](https://ucsd.zoom.us/my/jshang)

Note: all times are in **Pacific Time**.

Grading
======

- Homework: 8% each. Your lowest (of four) homework grades is dropped (or one homework can be skipped).
- Midterm: 26%.
- Data Mining Challenge: 25%.
- Project: 25%.
- You should complete all work individually, except for the Project.
- Late submissions are NOT accepted.

Lecture Schedule
======

**Recording Note**: Please download the recording video for the full length. Dropbox website will only show you the first one hour.

**HW Note**: All HWs due before the lecture time 6PM PT in the afternoon. 

Week | Date        | Topic & Slides                                                  | Events
1    | 01/06 (Wed) | Intro, Logistics, Course Project; Text Preprocessing | HW1 out
2    | 01/13 (Wed) | Text Classification using Bag-of-Words  | DM Challenge out
3    | 01/20 (Wed) | Word Embedding & Language Models: from N-Gram to Neural LMs | HW1 due, HW2 out
4    | 01/27 (Wed) | Information Retrieval & Topic Modeling  | 
5    | 02/03 (Wed) | Midterm Exam |
6    | 02/10 (Wed) | Phrase Mining and its Applications | HW2 due, HW3 out
7    | 02/17 (Wed) | Open-Domain Information Extraction: Entity Recognition, Relation Extraction, and Attribute Discovery  | DM challenge due
8    | 02/24 (Wed) | Weakly Supervised Text Classification | HW3 due, HW4 out
9    | 03/03 (Wed) | Document Summarization, Aspect-based Sentiment Analysis, and Opinion Summarization|
10   | 03/10 (Wed) | | HW4 due

Homework (24%)
======

Your lowest (of four) homework grades is dropped (or one homework can be skipped).

- **HW1: Text Pre-processing and Classification (8%).** This homework mainly focuses on the impact of the pre-processing on the classification results.
- **HW2: Word Embedding and Neural Language Models (8%).** This homework mainly focuses on trying out the word embedding and neural language models (e.g., BERT using HuggingFace). 
- **HW3: Phrase Mining (8%).** This homework mainly focuses on phrase mining applications and future work.
- **HW4: Weakly Supervised Text Classification (8%).** This homework mainly focuses on weakly supervised aspect classification and opinion summarization.

Midterm (26%)
======

It is an open-book, take-home exam, which covers all lectures given before the Midterm. Most of the questions will be open-ended. Some of them might be slightly more difficult than homework. You will have 24 hours to complete the midterm, which is expected for about 3 hours.

- **Start**: Feb 3, 6 PM PT
- **End**: Feb 4, 6 PM PT
- Midterm problems download: TBD.

Data Mining Challenge (25%)
======

It is a individual-based data mining competition with quantitative evaluation. The challenge runs **from Jan 13, 0:00:01 AM to Feb 17 4:59:59 PM PT**. Note that the time displayed on Kaggle is in UTC, not PT.

- Challenge Statement, Dataset, and Details: TBD
- Kaggle challenge link: TBD

Project (25%)
======

**Overview**
- Team-Based Open-Ended Project
    - 1 to 4 members per team. More members, higher expectation.
    - Define your own research problem and justify its importance
    - Final Deliverables: Research Paper-like Report
        - Report due on Mar 12, End of the day, Pacific Time. 
        - Write a 5 to 9 pages report (research-paper like following ACL template). The pages here do not include references.
        - Come up with your hypothesis and find some datasets for verification
        - Design your own models or try a large variety of existing models
        - Submit your codes and datasets; Github repos are welcome
        - Up to 5% bonus for working demos/apps towards the total course grades
