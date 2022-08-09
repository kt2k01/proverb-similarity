# Proverb Similarity

## Introduction
 
I calculate the similarities between proverbs in French and their literal translations in English. I use this [proverb set](https://github.com/GITenberg/A-Polyglot-of-Foreign-Proverbs-Comprising-French-German-Dutch-Spanish-Portuguese-and-Danish-w__51090) and [xlm-roberta-base](https://huggingface.co/xlm-roberta-base).

## Results

For Fr-En, the MRR and P@K values are shown in the table below.

|Metric|Value|
|---|---|
|MRR|0.139|
|P@1|0.099|
|P@5|0.177|
|P@10|0.200|
|P@20|0.236|
|P@50|0.337|

## TBA

- [ ] Other language pairs
- [ ] Use the embedding from layers other than the last one
- [ ] Case studies