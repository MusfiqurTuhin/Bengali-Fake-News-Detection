# 🇧🇩 Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![License](https://img.shields.io/badge/License-CC--BY--4.0-lightgrey?style=for-the-badge)

Official repository for the conference paper:
**"Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach"**

> *Published in: 2025 International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN)*

---

## 📄 Abstract
In the contemporary digital landscape, combatting the spread of fake news remains an utmost challenge in the contemporary digital industry that affects everything from political forces to public opinion. Since most available studies tend to focus on detecting misinformation through obscure newspapers or rumors on Facebook, our study diverges from this trend, primarily focusing on **mainstream Bangladeshi journalism**.

Taking a critical review of credible sources to include top TVs and newspapers, our work propounds a new direction in the field of fake news detection. As we tap into their long-standing credibility and high readership counts, we have a very strong database to back our ensemble model. A good model would use a special type of recurrent neural network, known as **Long Short-Term Memory (LSTM)** networks, to be able to take care of the sequence data, which is inherent in news content.

Our rigorous experiments and model iterations result in an **accuracy rate of 82.43%**, which stands remarkably high vis-à-vis previous benchmarks. These give a high motivation for our approach toward accurately discerning which piece of news is authentic and which one is fabricated.

---

## 🔗 Quick Links

| Resource | Link |
| :--- | :--- |
| 📄 **Paper (IEEE Xplore)** | [![IEEE](https://img.shields.io/badge/IEEE-Xplore-blue?style=flat&logo=ieee)](https://ieeexplore.ieee.org/abstract/document/11171927) |
| 🐍 **Kaggle Dataset** | [![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-blue?style=flat&logo=kaggle)](https://www.kaggle.com/datasets/musfiqurtuhin/bengali-fake-news-detection-dataset) |
| 🤗 **Hugging Face** | [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Dataset-yellow?style=flat&logo=huggingface)](https://huggingface.co/datasets/musfiqurtuhin/bengali-fake-news) |

---

## 💾 Dataset Description

Our dataset focuses on **mainstream news outlets**, a previously unexplored domain in Bengali fake news research.

-   **Total Documents:** 11,839
-   **Authentic (Class 1):** ~6,000 documents
-   **Fake (Class 0):** ~5,839 documents
-   **Total Words:** 187,127 unique words
-   **Sources:** Top TV channels and newspapers in Bangladesh.

| Class | Label | Count | Description |
| :--- | :---: | :---: | :--- |
| **Authentic** | `1` | 6,000 | Verified news from credible mainstream sources. |
| **Fake** | `0` | 5,839 | Fabricated news collected from various sources. |

---

## 🧠 Methodology

We employed a **Multi-Layered LSTM Ensemble** approach to capture the sequential nature of news content effectively.

-   **Model Architecture:** Long Short-Term Memory (LSTM) Networks
-   **Strategy:** Ensemble Learning
-   **Accuracy:** **82.43%**

---

## 📊 Result Analysis

We evaluated our **Multi-Layered LSTM Ensemble** against traditional Machine Learning models (SVM) and other Ensemble methods. Our proposed model outperformed others with an accuracy of **82.43%**.

### 🏆 Performance Comparison

| Model | Accuracy | Precision (Fake) | Precision (Real) | Recall (Fake) | Recall (Real) | F1-Score (Fake) | F1-Score (Real) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **SVM** | 80.00% | 0.83 | 0.77 | 0.76 | 0.84 | 0.79 | 0.81 |
| **Ensemble (Voting)** | 81.00% | 0.85 | 0.78 | 0.76 | 0.86 | 0.80 | 0.82 |
| **LSTM Ensemble (Ours)** | **82.43%** | 0.74 | **0.84** | **0.87** | 0.70 | **0.80** | 0.77 |

> **Key Observation:** The LSTM Ensemble achieved the highest **Recall for Fake News (0.87)**, making it highly effective at identifying misinformation (minimizing False Negatives), which is crucial for this domain.

### 📈 Visual Insights
-   **ROC-AUC Score:** The model achieved an AUC score of **85%**, demonstrating strong discrimination capability between real and fake news.
-   **Confusion Matrix:** The model shows a balanced classification ability, with a slight trade-off between precision and recall for the "Fake" class to maximize detection rate.

---

## 📝 Citation

If you use this dataset or code in your research, please cite our paper:

```bibtex
@INPROCEEDINGS{11171927,
  author={Rinky, Susmita Roy and Tusher, Md. Mahbubur Rahman and Rahman, Md. Musfiqur and Porag, Prithweeraj Acharjee and Islam, Jahidul and Miah, Abu Saleh Musa},
  booktitle={2025 International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN)}, 
  title={Bengali Fake News Detection: A Multi-Layered LSTM Ensemble Approach}, 
  year={2025},
  pages={1-6},
  keywords={Accuracy;TV;Recurrent neural networks;Social networking (online);Reviews;Organizations;Market research;Fake news;Long short term memory;Photonics;Bangla fake news;fake news;Mainstream news media;LSTM ensemble},
  doi={10.1109/QPAIN66474.2025.11171927}
}
```

---

## 👥 Authors

-   **Susmita Roy Rinky**
-   **Md. Mahbubur Rahman Tusher**
-   **Md. Musfiqur Rahman**
-   **Prithweeraj Acharjee Porag**
-   **Jahidul Islam**
-   **Abu Saleh Musa Miah**

---

## 📬 Contact

For any questions, please open an issue in this repository or contact the authors.