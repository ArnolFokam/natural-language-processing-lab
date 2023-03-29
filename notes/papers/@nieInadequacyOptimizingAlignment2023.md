---
title: On The Inadequacy of Optimizing Alignment and Uniformity in Contrastive Learning of Sentence Representations
authors: Zhijie Nie, Richong Zhang, Yongyi Mao
year: 2023
---


#contrastive-learning #representation-learning

## Problem Indentified
- In self supervised learning, the objective known to optimize are alignment and uniformity
- Some methods even proposed a way to optimize these metrics seperately
- However such methods fails when implemented in the context of sentece representations
- The paper observes a significant performance gap between that of the original contrastive objective and the decoupled objective (alignment and uniformity)

## Solution proposed 
- The paper proposes a gradient analysis to show why this is the case
- The paper proposes a remedy to the problem for sentence representation learning

## Contributions
- A detailed analysis of the contrastive objective
- A new contrastive learning objective for object representation.

## Methodology
- Evaluate the two criterion on **semantic textual similarity** and **transfer tasks**
	- Original InfoNCE
	- Alignment and Uniformity
	- Decoupled InfoNCE
- 

## Findings
- 

## Limitations
- 

## Cross-Reference
- 
