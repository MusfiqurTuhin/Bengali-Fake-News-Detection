# 🇧🇩 Bengali Fake News Detection Dataset

![Language](https://img.shields.io/badge/Language-Bengali-green?style=for-the-badge&logo=google-translate&logoColor=white)
![Task](https://img.shields.io/badge/Task-Fake%20News%20Detection-red?style=for-the-badge&logo=mediafire&logoColor=white)
![Size](https://img.shields.io/badge/Size-12K%20Docs-blue?style=for-the-badge&logo=files&logoColor=white)
![License](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?style=for-the-badge)

## 📄 Context
**Official dataset** for the research paper:
> **"Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach"**
> *Published in: 2025 International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN)*

In the digital age, fake news affects everything from political stability to public opinion. While most studies focus on social media rumors, our work diverges by focusing on **mainstream Bangladeshi journalism**. This dataset aggregates news from credible top TV channels and newspapers to provide a robust benchmark for authentic vs. fabricated news detection.

---

## 🔗 Associated Resources

| Resource | Link |
| :--- | :--- |
| 📄 **Paper (IEEE Xplore)** | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-blue?style=flat&logo=ieee)](https://ieeexplore.ieee.org/abstract/document/11171927) |
| 🐙 **GitHub Repository** | [![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=flat&logo=github)](https://github.com/MusfiqurTuhin/Bengali-Fake-News-Detection) |
| 🤗 **Hugging Face** | [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?style=flat&logo=huggingface)](https://huggingface.co/datasets/musfiqurtuhin/bengali-fake-news) |

---

## 💾 Dataset Specifications

The dataset contains **11,839 documents** collected from mainstream news media, balanced between authentic and fake news.

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
| `domain` | The source publication or website (e.g., Ittefaq). |
| `category` | The news category (e.g., National, Sports). |
| `headline` | The title of the news article. |
| `content` | The full text of the news article. |
| `label` | **`1`** for Authentic, **`0`** for Fake. |

---

## 🧠 Benchmarks

The dataset was benchmarked using a **Multi-Layered LSTM Ensemble** model, achieving an accuracy of **82.43%**.

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

---

## 📬 Contact

For questions, please contact the authors via the [GitHub Repository](https://github.com/MusfiqurTuhin/Bengali-Fake-News-Detection).
