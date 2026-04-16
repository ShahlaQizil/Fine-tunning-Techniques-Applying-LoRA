# Fine-tunning-Techniques-Applying-LoRA
Intent Classification on Banking77 using BERT & LoRA
This repository demonstrates the application of Parameter-Efficient Fine-Tuning (PEFT) using LoRA (Low-Rank Adaptation) to fine-tune a BERT model for financial intent classification.
By using LoRA, we significantly reduce the number of trainable parameters while maintaining the model's ability to categorize complex banking queries.
🚀 Project Overview
•	Base Model: bert-base-uncased
•	Dataset: PolyAI/banking77 (77 categories of banking queries)
•	Technique: LoRA (Low-Rank Adaptation)
•	Primary Goal: Efficiently adapt a Large Language Model (LLM) to a specific domain with minimal computational overhead.
________________________________________
📊 Technical Performance
Using LoRA allowed us to train a tiny fraction of the total model weights. This is ideal for scenarios with limited GPU memory.
Metric	Value
Total Parameters	109,895,578
Trainable Parameters	354,125 (0.3222%)
Training Epochs	3
Final Test Accuracy	43.18%
F1 Score	0.3902
Note: The current accuracy reflects a baseline run with a small rank (r=8). Performance can be further improved by increasing epochs or adjusting the rank and alpha parameters.
________________________________________
📚 Dataset Reference
The Banking77 dataset contains 13,083 customer service queries labeled across 77 intents.
•	Training Set: 8,502 samples
•	Validation Set: 1,501 samples
•	Test Set: 3,080 samples
________________________________________
📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

