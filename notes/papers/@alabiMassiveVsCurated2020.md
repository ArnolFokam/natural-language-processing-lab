
---
title: Massive vs. Curated Word Embeddings for Low-Resourced Languages. The Case of Yor\`ub\'a and Twi
authors: Jesujoba O. Alabi, Kwabena Amponsah-Kaakyire, David I. Adelani, Cristina España-Bonet
year: 2020
---
#nlp #word-embeddings #data-quality #ner

## Problem Indentified
- Evaluation of word embeddings for low-resources languages is often ignore due to its difficulty.

## Solution proposed 
- Proposes the evaluation of the effect of quality and quantity of data on the word embeddings of low-resourced data.

## Contributions
- Analysis of the impact of quality and quantity on word embeddings of low-resourced languages.
- Creation of a word pairs dataset for **Yoruba** and **Twi**.

## Methodology
- A *clean* and a *noisy* dataset is collected for corpora in [Yoruba](https://en.wikipedia.org/wiki/Yoruba_language) and [Twi](https://en.wikipedia.org/wiki/Twi).
- Noise in this context might mean:
	- Amoun of non-native (English) words.
	- Spelling errors.
	- L2 speakers sentence formulation.
- The paper evaluate the perfromance of the Yoruba embedings using a Fastext model
- Also, the paper the perfromance of the Yoruba dataset on Named Entity Recognition using a BERT multilingual model.

## Findings
- A **170%** improvement on the evaluation task was observed when the curated corpus was used.
- Though some languages from wikipedia would be rated as high-quality by some Native speakers, this wasn't necessary the case for speakers of other languages.

## Conslusion 
- Curation has a more important impact in low-resourced language than high-resourced.

## Limitations
- The quality of the data is not quantifiable in this case and makes it hard to investigate the relationhship between corpus quality and model performance.
- The model does not evaluate on NER for **Twi** for unidentified reasons.
- The paper makes concul

## Cross-Reference
- The work done is similar to [[@joshiWordEmbeddingsLow2019]] 
