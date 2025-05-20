# Sarcasm Detection using BERT and XAI (LIME)

This project demonstrates how to detect sarcasm in news headlines using the **BERT** language model. To increase interpretability, the model is explained using **LIME (Local Interpretable Model-agnostic Explanations)** - a popular Explainable AI (XAI) technique.

---

## 🔍 Objective

- Train a BERT-based classifier to identify sarcastic headlines.
- Use LIME to provide local explanations for the model’s predictions.

---

## 📁 Dataset

- **Source**: [Sarcasm Headlines Dataset v2](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection)
- **File used**: `Sarcasm_Headlines_Dataset.json`
- **Fields**:
  - `headline` — The news headline (string)
  - `is_sarcastic` — Target label (`1` = sarcastic, `0` = not sarcastic)
---

🔗 **Saved Model File**  
To avoid GitHub file size limits, the fine-tuned model (`model.safetensors`) is not uploaded.   
- Uncomment the codes and run them if you want to run without saved files.
- Comment the saving part.

---
