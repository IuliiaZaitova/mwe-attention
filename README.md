# Attention on Multiword Expressions
Code and data for the paper "Attention on Multiword Expressions: A Multilingual Study of BERT-based Models with Regard to Idiomaticity and Microsyntax" (Findings of NAACL 2025)

## Authors
- Iuliia Zaitova
- Vitalii Hirak
- Badr M. Abdullah
- Dietrich Klakow
- Bernd Möbius
- Tania Avgustinova

## MWE dataset
- `mwe_data/`: Contains datasets used in the experiments

## Fine-tuned Models
All models are available on HuggingFace Hub under the following paths:

Here are the tables with languages arranged alphabetically:

### Dependency Relation Classification (DepRel)
| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large_deprel` |
| English   | `izaitova/bert-large-cased_deprel` |
| German    | `izaitova/gbert-large_deprel` |
| Polish    | `izaitova/herbert-large-cased-deprel` |
| Russian   | `izaitova/ruBert-large_deprel` |
| Ukrainian | `izaitova/liberta-large_deprel` |

### Part-of-Speech Tagging (UPOS)
| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large-upos` |
| English   | `izaitova/bert-large-cased-upos` |
| German    | `izaitova/gbert-large-upos` |
| Polish    | `izaitova/herbert-large-cased-upos` |
| Russian   | `izaitova/ruBert-large-upos` |
| Ukrainian | `izaitova/liberta-large-upos` |

### Named Entity Recognition (NER)
| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large_ner` |
| English   | `izaitova/bert-large-cased_ner` |
| German    | `izaitova/gbert-large_ner` |
| Polish    | `izaitova/herbert-large-cased-ner` |
| Russian   | `izaitova/ruBert-large_ner` |
| Ukrainian | `izaitova/liberta-large_ner` |

### Topic Classification
| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large-topic_classification` |
| English   | `izaitova/bert-large-cased-topic_classification` |
| German    | `izaitova/gbert-large-topic_classification` |
| Polish    | `izaitova/herbert-large-cased-topic_classification` |
| Russian   | `izaitova/ruBert-large-topic_classification` |
| Ukrainian | `izaitova/liberta-large-topic_classification` |


## Citation
If you use this code or data in your research, please cite our paper: