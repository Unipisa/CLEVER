# CLEVER - Computational and Linguistic bEnchmarks for the study of VErb argument structuRe 

## Project description
The main goal of the CLEVER Project is to gather evidence on Italian argument structure from three different source of knowledge that are typically used in distinct linguistics subfields: human acceptability judgments, behavioral data, distributional representations.

The main outcome of the project will consist of two types of resources that will be made publicy available: 

- a wide-coverage dataset of sentences covering a series of linguistic phenomena concerning the verb argument structure of Italian verbs, annotated with human judgments and behavioral data;
- neural language models for Italian trained on a cognitively plausible corpus, which will be used to develop and test novel applications for the Italian language and as a source of evidence for investigating the property of the argument structure of Italian verbs.

CLEVER includes two RUs, with long-standing mutual collaborations:
Università di Pisa (UPI)
Università Ca’ Foscari Venezia (UVE)



The project consists of five work packages (WP) arranged into several activities.

  WP1. Corpus, linguistic analyses and dataset specification

  WP2. Training of the Neural Language Model

  WP3. Creation of the Linguistic Dataset

  WP4. Computational modeling and linguistic analysis

  WP5. Project Management


## Models
Trained models can be found at: https://huggingface.co/colinglab

## 🦌 **BAMBI Dataset**

### **Dataset Summary**

The **BAMBI Dataset** is an **Italian-language corpus** designed to provide **ecologically valid and cognitively plausible linguistic input** for **BabyLM-style language model training**.
It is organized into **four developmental tiers**, corresponding to different phases of linguistic growth in childhood and adolescence:

| Tier   | Age Range (years) | Approx. Tokens | Description                                   |
| ------ | ----------------- | -------------- | --------------------------------------------- |
| Tier 1 |              0–6  |          ~26M  | Early childhood and preschool exposure        |
| Tier 2 |             6–12  |          ~31M  | Primary school and literacy development       |
| Tier 3 |            12–18  |          ~32M  | Adolescent linguistic expansion               |
| Tier 4 |            18–24  |          ~31M  | Young adult and advanced language exposure    |

Each tier reflects age-appropriate linguistic input, curated from authentic Italian sources for ecological validity and developmental plausibility.

---

### **Data Composition**

The corpus integrates **transcriptions of oral materials** that mirror the linguistic environment of Italian speakers from early childhood through young adulthood.

### **Source Types**

* **Entertainment:** audiobooks, TV shows, podcasts, and films
* **Educational:** textbooks, didactic materials, and learning media
* **News and informational:** simplified news, magazines, and public media
* **Caregiver and spontaneous speech:** naturalistic speech and conversational transcriptions

Each document includes metadata indicating:

* **Source type**
* **Data origin** 
* **Intended age tier**

---

### **Linguistic Characteristics**

* **Language:** Italian 🇮🇹
* **Register:** naturalistic, age-appropriate, and cognitively plausible speech
* **Total tokens:** ~120 million
* **Format:** plain text (`.csv`) with detailed metadata

---

### **Intended Use**

The BAMBI dataset is intended for:

* Training **BabyLM-style** or other small-scale developmental language models in Italian
* **Research on cognitive and linguistic development**
* **Curriculum learning** and **ecological modeling** of language acquisition

Not intended for commercial NLP applications.

---

### **Ethical Considerations**
TBD

### **Citation**
TBD

## Evaluation resources:

*Clever Semantic Minimal Pairs* - This benchmark extends current research on the sensitivity to semantic violations in language models. Specifically, we adapted an existing minimal pair benchmark that targets knowledge about prototypical, unlikely, and impossible events (Kauf et al.,2023) to evaluate Italian Language Models. In turn, they were derived from previous cognitive and neurolinguistic studies by Fedorenko et al. (2020) and Ivanova et al. (2021), respectively. The datasets contain minimal pairs of sentences designed to assess semantic knowledge by manipulating sentence plausibility.


## Research outcomes
Capone, L.,  Bondielli, A., and Lenci, A. Proceedings of the First BabyLM Workshop. 2025.
CLASS-IT: Conversational and Lecture-Aligned Small-Scale Instruction Tuning for BabyLMs.

Suozzi, A., Capone, L., Lebani, G. E., & Lenci, A. (2025). arXiv preprint arXiv:2503.09481.
BAMBI: Developing Baby Language Models for Italian.

Capone, L., Suozzi, A., Lebani, G. E., & Lenci, A. (2025).  In Proceedings of the Eleventh Italian Conference on Computational Linguistics (CLiC-it 2025) (pp. 1-12). Università di Cagliari.
BAMBI Goes to School: Evaluating Italian BabyLMs with Invalsi-ITA.

Capone L, A Suozzi, GE Lebani, A Lenci (2024), CliC-it 2024, CEUR WORKSHOP PROCEEDINGS.
BaBIEs: A Benchmark for the Linguistic Evaluation of Italian Baby Language Models.

Capone L, A Bondielli, A Lenci (2024), The 2nd BabyLM Challenge at the 28th CoNLL.
ConcreteGPT: A Baby GPT-2 Based on Lexical Concreteness and Curriculum Learning.
