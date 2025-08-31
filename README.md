---
title: "Real-Time Detection of Cyberbullying Using Transformer Models: A Multilingual Approach"
authors:
  - Ahmad Abdullah (202114008)
  - Faria Islam (202114021)
  - Md Zakaria Hossen Emon (202114060)
supervisor: "Professor Dr. Fernaz Narin Nur"
institute: "Military Institute of Science and Technology (MIST)"
conference: "To be updated"
tags: ["NLP", "Cyberbullying Detection", "Transformers", "Ensemble Learning", "Bangla NLP"]
---

# 📘 Real-Time Detection of Cyberbullying Using Transformer Models: A Multilingual Approach

## 👥 Authors
- Ahmad Abdullah (ID: 202114008)  
- Faria Islam (ID: 202114021)  
- Md Zakaria Hossen Emon (ID: 202114060)  

**Supervisor:** Professor Dr. Fernaz Narin Nur  
**Institute:** Military Institute of Science and Technology (MIST)  

---

## 📖 Project Overview
Cyberbullying is a rising problem on social media, often expressed in subtle, sarcastic, or multilingual ways.  
This thesis focuses on building a **real-time detection system** using **transformer models** such as BanglaBERT, BanglaElectra, and XLM-R.  
We also experimented with **ensemble learning** to improve detection accuracy and robustness.

---

## 🎯 Objectives
- Develop a **real-time multilingual system** for detecting cyberbullying.  
- Handle **Bangla, Romanized Bangla, and English** text effectively.  
- Use **transformer-based models** for contextual understanding.  
- Apply **ensemble methods** to minimize false positives and improve performance.  

---

## 📂 Project Structure
```
cyberbullying-thesis/
│── data/              # Dataset (link or sample, not full upload)
│── notebooks/         # Jupyter notebooks (BanglaBERT, Electra, XLM-R, Ensemble)
│── src/               # Scripts for training and evaluation
│── results/           # Metrics, confusion matrix, plots
│── poster/            # Conference poster
│── paper/             # Published paper PDF
│── requirements.txt   # Dependencies
│── README.md          # Project documentation
```

---

## 📊 Results (Performance Comparison)
| Model         | Accuracy | Precision | Recall | F1 Score |
|---------------|----------|-----------|--------|----------|
| BanglaBERT    | 94.2%    | 93.5%     | 91.7%  | 92.6%    |
| BanglaElectra | 93.8%    | 92.9%     | 90.4%  | 91.6%    |
| XLM-R         | 94.5%    | 93.8%     | 92.2%  | 93.0%    |
| **Ensemble**  | **95.3%**| **94.5%** | **93.0%**| **93.7%** |

---

## 📑 Dataset
Due to size/privacy, the dataset is not fully uploaded here.  
- 🔗 Dataset Link: [Insert Kaggle / Hugging Face / Google Drive link]  
- Languages: Bangla, Romanized Bangla, English  
- Balanced for cyberbullying vs non-cyberbullying  

---

## ⚙️ Installation & Usage
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/cyberbullying-detection-transformers.git
cd cyberbullying-detection-transformers

# Install dependencies
pip install -r requirements.txt

# Run training
python src/train.py --model BanglaBERT
```

---

## 📌 Future Work
- Optimize for **real-time deployment** in social media platforms.  
- Expand dataset with **more Romanized Bangla & multilingual data**.  
- Improve detection of **sarcasm & indirect bullying**.  

---

## 📚 References
- Devlin et al., 2019 – BERT  
- Liu et al., 2019 – RoBERTa  
- Li et al., 2020 – Cyberbullying Detection for Bengali  
- Zhang et al., 2018 – CNN-SVM Hybrid for Cyberbullying  

---

## 🙏 Acknowledgment
We sincerely thank our supervisor **Professor Dr. Fernaz Narin Nur** for her continuous guidance and support.
