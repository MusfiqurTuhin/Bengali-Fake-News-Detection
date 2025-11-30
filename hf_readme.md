---
annotations_creators:
- expert-generated
language_creators:
- expert-generated
language:
- bn
license:
- cc-by-4.0
multilinguality:
- monolingual
size_categories:
- 10K<n<100K
source_datasets:
- original
task_categories:
- text-classification
task_ids:
- fact-checking
pretty_name: Bengali Fake News Detection Dataset
tags:
- fake-news
- bangla
- nlp
- classification
- lstm
dataset_info:
  features:
  - name: domain
    dtype: string
  - name: category
    dtype: string
  - name: headline
    dtype: string
  - name: content
    dtype: string
  - name: label
    dtype:
      class_label:
        names:
          '0': Fake
          '1': Authentic
---

# 🇧🇩 Bengali Fake News Detection Dataset

![Language](https://img.shields.io/badge/Language-Bengali-green?style=for-the-badge&logo=google-translate&logoColor=white)
![Task](https://img.shields.io/badge/Task-Fake%20News%20Detection-red?style=for-the-badge&logo=mediafire&logoColor=white)
![Size](https://img.shields.io/badge/Size-12K%20Docs-blue?style=for-the-badge&logo=files&logoColor=white)
![License](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?style=for-the-badge)

## 📄 Context
**Official dataset** for the research paper:
> **"Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach"**
> *Published in: 2025 International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN)*

This dataset focuses on **mainstream Bangladeshi journalism**, aggregating news from credible top TV channels and newspapers to provide a robust benchmark for authentic vs. fabricated news detection.

---

## 🔗 Associated Resources

| Resource | Link |
| :--- | :--- |
| 📄 **Paper (IEEE Xplore)** | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-blue?style=flat&logo=ieee)](https://ieeexplore.ieee.org/abstract/document/11171927) |
| 🐙 **GitHub Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=flat&logo=github)](https://github.com/MusfiqurTuhin/Bengali-Fake-News-Detection) |
| 🐍 **Kaggle Dataset** | [![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?style=flat&logo=kaggle)](https://www.kaggle.com/datasets/musfiqurtuhin/bengali-fake-news-detection-dataset) |

---

## 💾 Dataset Specifications

| Feature | Details |
| :--- | :--- |
| **Total Documents** | **11,839** |
| **Authentic (Label 1)** | 6,000 documents |
| **Fake (Label 0)** | 5,839 documents |
| **Total Words** | 187,127 unique words |
| **Language** | Bengali (Bangla) |

### 📝 Column Description

| Column | Description |
| :--- | :--- |
| `domain` | The source publication or website. |
| `category` | The news category. |
| `headline` | The title of the news article. |
| `content` | The full text of the news article. |
| `label` | **`1`** for Authentic, **`0`** for Fake. |

---

## 🚀 Quick Start

```python
from datasets import load_dataset

# Load the dataset
dataset = load_dataset("musfiqurtuhin/bengali-fake-news")

# View a sample
print(dataset['train'][0])
```

---

## 🤝 Citation

If you use this dataset, please cite our work:

```bibtex
@INPROCEEDINGS{11171927,
  author={Rinky, Susmita Roy and Tusher, Md. Mahbubur Rahman and Rahman, Md. Musfiqur and Porag, Prithweeraj Acharjee and Islam, Jahidul and Miah, Abu Saleh Musa},
  booktitle={2025 International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN)}, 
  title={Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach}, 
  year={2025},
  pages={1-6},
  doi={10.1109/QPAIN66474.2025.11171927}
}
```
