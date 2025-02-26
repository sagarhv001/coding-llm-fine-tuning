### Fine-Tuning LLaMA 3.1 (8B) for Python Code Generation
This project fine-tunes Meta’s LLaMA 3.1 (8B) model for Python code generation using LoRA (Low-Rank Adaptation). The fine-tuned model is trained on a dataset containing Python code snippets and their descriptions. The training is conducted on Kaggle, and evaluation is performed using statistical methods and manual examples.

## Project Overview
Model: LLaMA 3.1 (8B)
Fine-tuning Method: LoRA (Parameter-efficient adaptation)
Training Dataset: Python code and documentation pairs
Training Platform: Kaggle (30-hour GPU limit, resumed training implemented)
Evaluation: Quantitative and qualitative accuracy testing
Storage: Results saved to Google Drive due to Kaggle’s lack of persistent storage
