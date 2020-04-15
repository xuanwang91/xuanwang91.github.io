---
layout: post
title: Automatic Textual Evidence Mining for COVID-19 Literature Search
---

On *March 16th, 2020*, White House released this [Call to Action to the Tech Community on New Machine Readable COVID-19 Dataset](https://www.cccblog.org/2020/03/16/news-call-to-action-to-the-tech-community-on-new-machine-readable-covid-19-dataset/?utm_source=feedblitz&utm_medium=FeedBlitzRss&utm_campaign=cccblog). Our [Data Mining Group](http://dm1.cs.uiuc.edu/) in [CS@UIUC](https://cs.illinois.edu/) has generated a comprehensieve named entity annotation dataset, **CORD-NER**, on the [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) corpus (2020-03-13). 


## CORD-NER: NER Methods 
CORD-NER annotation is a combination from 4 sources:
1. Pretrained NER on **18 general entity types**: [Spacy](https://spacy.io/api/annotation#named-entities).
2. Pretrained NER on **18 biomedical entity types**: [SciSpacy](https://allenai.github.io/scispacy/).
3. Knowledge base (KB)-guided NER on **127 biomedical entity types**: our distantly-supervised NER method without requiring any human annotated training data. We use [UMLS](https://www.nlm.nih.gov/research/umls/META3_current_semantic_types.html) as the input KB for distant supervision.
3. Seed-guided NER on **9 new entity types related to COVID-19 studies**: our weakly-supervised NER method only requiring several human-input seeds for each new type.
  - **Coronavirus**: COVID-19, SARS-COV, MERS-COV, etc.
  - **Viral Protein**: Hemagglutinin, GP120, etc.
  - **Livestock**: cattle, sheep, pig, etc.
  - **Wildlife**: bats, pangolins, African green monkey, etc
  - **Evolution**: genetic drift, natural selection, mutation rate, etc
  - **Physical Science**: atomic charge, Amber force fields, Van der Waals force, etc.
  - **Substrate**: blood, sputum, urine, etc.
  - **Material**: copper, stainless steel, plastic, etc.
  - **Immune Response**: adaptive immune response, cell mediated immunity, innate immunity, etc.

We reorganized all the entity types from the 4 sources and merged into one entity type hierarchy with **75 fine-grained entity types** for annotation. The entity type hierarchy (**CORD-NER-types.xlsx**) used in CORD-NER can be found in our dataset.


## CORD-NER: Dataset Download
The CORD-NER dataset (**CORD-NER-full.json**) can be downloaded [here](https://uofi.box.com/s/k8pw7d5kozzpoum2jwfaqdaey1oij93x). It includes all the related information (meta-data, full-text corpus and NER results) into one file for users' convenience. The size of the dataset is about 1.2GB. The input corpus is generated from the 29,500 documents in [COVID-19 Open Research Dataset Challenge (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) corpus (2020-03-13). A detailed description of the file schemas can be found in the **README** file in our dataset.

### NER Annotation Results
Below is the NER performance comparison between SciSpacy and our annotation results on the COVID-19 corpus.

![evaluation](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/evaluation.png?raw=True)


Below is an example of our annotation results on the CORD-19 corpus.

![annotation example](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/annotation.png?raw=True)


Our NER methods are domain-independent that can be applied to corpus in different domains. Below is an example of our annotation on the New York Times corpus.

![annotation example](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/annotation-nyt.png?raw=True)


Below are some annotation comparisons with existing supervised NER methods.

- Example 1:

![comparison 1](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/annotation-comparison-1.png?raw=True)

- Example 2:

![comparison 2](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/annotation-comparison-2.png?raw=True)

- Example 3:

![comparison 3](https://github.com/xuanwang91/xuanwang91.github.io/blob/master/img/annotation-comparison-3.png?raw=True)


### Top-Frequent Entity Summarization
Below are some examples of the most frequent entities for each type.

New entity types:

**CORONAVIRUS** | **EVOLUTION** | **WILDLIFE** | **PHYSICAL_SCIENCE**
sars | mutation | bat | positively charged
cov | phylogenetic | wild birds | negatively charged
mers | evolution | wild animals | force field
covid-19 | recombination | fruit bats | highly hydrophobic
sars-cov-2 | substitutions | pteropus | van der waals interactions
**LIVESTOCK** | **MATERIAL** | **SUBSTRATE** | **IMMUNE_RESPONSE**
pigs | air | blood | immunization
poultry | plastic | urine | immunity
calves | fluids | sputum | immune cells
chicken | copper | saliva | innate immune
pig | silica | fecal | inflammatory response

UMLS types that have not been annotated before:

**SOCIAL_BEHAVIOR** | **INDIVIDUAL_BEHAVIOR** | **THERAPEUTIC_PROCEDURE**
collaboration | hand hygiene | detection 
sharing | disclosures | vaccination
herd | absenteeism | isolation
mediating | compliance | stimulation
adoption | empathy | inoculation
**RESEARCH_ACTIVITY** | **EDUCATIONAL_ACTIVITY** | **MACHINE_ACTIVITY**
rt-pcr | health education | machine learning 
sequencing | workshops | data processing
screening | nursery | automation
diagnosis | medical education | deconvolution
prevention | residency | telecommunication


## Contact
Our team for creating this CORD-NER dataset:
- **Xuan Wang** ([xwang174@illinois.edu](xwang174@illinois.edu)): Please contact me if you have any questions or suggestions related to this CORD-NER dataset.
- **Xiangchen Song** ([xs22@illinois.edu](xs22@illinois.edu))
- **Bangzheng Li** ([bl17@illinois.edu](bl17@illinois.edu))
- **Yingjun Guan** ([yingjun2@illinois.edu](yingjun2@illinois.edu))


## Citation
If you find our CORD-NER dataset useful, please cite our [paper](https://arxiv.org/abs/2003.12218). Thanks!



