# Fine-tuning BERT with LoRA for Banking Intent Classification

This repository demonstrates how to use **LoRA (Low-Rank Adaptation)** to fine-tune a BERT model on the Banking77 dataset. This approach trains less than 1% of the total parameters.

---

## 🚀 Project Overview
* **Base Model:** `bert-base-uncased`
* **Dataset:** `PolyAI/banking77` (77 categories)
* **Technique:** Parameter-Efficient Fine-Tuning (PEFT / LoRA)

---

## 📊 Technical Performance

| Metric | Value |
| :--- | :--- |
| **Total Parameters** | 109,895,578 |
| **Trainable Parameters** | 354,125 (**0.3222%**) |
| **Training Epochs** | 3 |
| **Final Test Accuracy** | **43.18%** |
| **F1 Score** | **0.3902** |

> **Note:** Performance reflects a baseline run with $r=8$.

---

## 📚 Dataset Reference
The **Banking77** dataset contains 13,083 customer service queries.
* **Training Set:** 8,502 samples
* **Validation Set:** 1,501 samples
* **Test Set:** 3,080 samples

---

## 📜 License
This project is licensed under the MIT License.
