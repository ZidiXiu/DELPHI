# DELPHI: Data for Evaluating LLMs' Performance in Handling controversial Issues

This repository contains the DELPHI dataset and appendix. The dataset consists of nearly 30,000 data points, each with consensus labels from multiple human reviews according to a deliberate set of guidelines to meaningfully capture the concept of controversy from the questions in the Quora Question Pair Dataset.

This dataset was introduced in our paper:

> **DELPHI: Data for Evaluating LLMs' Performance in Handling Controversial Issues**  
> Published in EMNLP, 2023.  
> [link](https://arxiv.org/abs/2310.18130)

## Abstract

Controversy is a reflection of our zeitgeist, and an important aspect to any discourse. The rise of large language models (LLMs) as conversational systems has increased public reliance on these systems for answers to their various questions. Consequently, it is crucial to systematically examine how these models respond to questions that pertaining to ongoing debates. However, few such datasets exist in providing human-annotated labels reflecting the contemporary discussions. To foster research in this area, we propose a novel construction of a controversial questions dataset, expanding upon the publicly released Quora Question Pairs Dataset. This dataset presents challenges concerning knowledge recency, safety, fairness, and bias. We evaluate different LLMs using a subset of this dataset, illuminating how they handle controversial issues and the stances they adopt. This research ultimately contributes to our understanding of LLMs' interaction with controversial issues, paving the way for improvements in their comprehension and handling of complex societal debates.

## Repository Link

Please refer to [https://github.com/apple/ml-delphi](https://github.com/apple/ml-delphi) for the appendix and dataset. 


## Citing

If you use this dataset in your research, please cite our paper:

<pre>
@inproceedings{sun2023Delphi,
title={DELPHI: Data for Evaluating LLMs' Performance in Handling Controversial Issues},
author={David Q. Sun, Artem Abzaliev, Hadas Kotek, Zidi Xiu, Christopher Klein, Jason D. Williams},
booktitle={EMNLP},
year={2023}
}
</pre>
