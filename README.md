# 🧠 Attention on Multiword Expressions

**Code and data for the NAACL 2025 paper:**  
*"Attention on Multiword Expressions: A Multilingual Study of BERT-based Models with Regard to Idiomaticity and Microsyntax"*

---

## 🔎 TL;DR

Fine-tuning BERT-based models significantly influences how they allocate attention to different types of Multiword Expressions (MWEs):

- 🧠 Models fine-tuned on **semantic tasks** tend to distribute attention to **idiomatic** expressions more evenly across layers.
- 📐 Models fine-tuned on **syntactic tasks** show increased attention to **microsyntactic units** in the lower layers—aligning with syntactic processing requirements.

---

## 📝 Abstract

This study analyzes the attention patterns of fine-tuned encoder-only models based on the BERT architecture toward two distinct types of MWEs:

- **Idioms**, which challenge semantic compositionality
- **Microsyntactic units (MSUs)**, which demonstrate unconventional syntactic behavior

We investigate whether fine-tuning on specific tasks (semantic vs. syntactic) affects how models allocate attention to MWEs. Our experiments include pre-trained and fine-tuned BERT-based models across **six Indo-European languages**: English, German, Dutch, Polish, Russian, and Ukrainian.

Key finding:  
Semantic fine-tuning smooths attention across layers for idioms, while syntactic fine-tuning emphasizes lower-layer attention for MSUs.

---

## 👩‍💻 Authors

- Iuliia Zaitova  
- Vitalii Hirak  
- Badr M. Abdullah  
- Dietrich Klakow  
- Bernd Möbius  
- Tania Avgustinova

---

## 📂 Repository Structure

- `mwe_data/`: Multilingual datasets used in the experiments
- `analysis/`: Scripts and notebooks for attention score extraction and visualization (coming soon)
- `models/`: Fine-tuned models available via Hugging Face Hub

---

## 🤖 Fine-Tuned Models on Hugging Face

### 🧠 Semantic Tasks

#### Named Entity Recognition (NER)

| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large_ner` |
| English   | `izaitova/bert-large-cased_ner` |
| German    | `izaitova/gbert-large_ner` |
| Polish    | `izaitova/herbert-large-cased-ner` |
| Russian   | `izaitova/ruBert-large_ner` |
| Ukrainian | `izaitova/liberta-large_ner` |

#### Topic Classification

| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large-topic_classification` |
| English   | `izaitova/bert-large-cased-topic_classification` |
| German    | `izaitova/gbert-large-topic_classification` |
| Polish    | `izaitova/herbert-large-cased-topic_classification` |
| Russian   | `izaitova/ruBert-large-topic_classification` |
| Ukrainian | `izaitova/liberta-large-topic_classification` |

### 📐 Syntactic Tasks

#### Dependency Relation Classification (DepRel)

| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large_deprel` |
| English   | `izaitova/bert-large-cased_deprel` |
| German    | `izaitova/gbert-large_deprel` |
| Polish    | `izaitova/herbert-large-cased-deprel` |
| Russian   | `izaitova/ruBert-large_deprel` |
| Ukrainian | `izaitova/liberta-large_deprel` |

#### Part-of-Speech Tagging (UPOS)

| Language  | Model Path |
|-----------|------------|
| Dutch     | `izaitova/robbert-2023-dutch-large-upos` |
| English   | `izaitova/bert-large-cased-upos` |
| German    | `izaitova/gbert-large-upos` |
| Polish    | `izaitova/herbert-large-cased-upos` |
| Russian   | `izaitova/ruBert-large-upos` |
| Ukrainian | `izaitova/liberta-large-upos` |

---

## 📄 Citation

If you use this code or data in your research, please cite our paper:

```bibtex
@inproceedings{Zaitova2025AttentionMWEs,
  title={Attention on Multiword Expressions: A Multilingual Study of BERT-based Models with Regard to Idiomaticity and Microsyntax},
  author={Zaitova, Iuliia and Hirak, Vitalii and Abdullah, Badr M. and Klakow, Dietrich and Möbius, Bernd and Avgustinova, Tania},
  booktitle={Findings of the Association for Computational Linguistics: NAACL},
  year={2025}
}
