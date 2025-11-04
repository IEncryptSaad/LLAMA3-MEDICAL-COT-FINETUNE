# LLAMA3-MEDICAL-COT-FINETUNE

Fine-tuning the LLaMA 3.2 (3B) model on a Medical Chain of Thought dataset using parameter efficient fine tuning techniques with Unsloth.  
The goal is to develop a model capable of performing structured medical reasoning and producing accurate, step by step responses.

---

## PROJECT OVERVIEW
This project focuses on supervised fine tuning of the LLaMA 3.2 (3B) model using a medical reasoning dataset.  
The fine tuning approach is designed to be lightweight and cloud based, using only free resources.

---

## KEY OBJECTIVES
- Fine tune the LLaMA 3.2 (3B) model using Unsloth and Low Rank Adaptation (LoRA).
- Train on a Medical Chain of Thought dataset to enhance step by step reasoning ability.
- Apply parameter efficient fine tuning (PEFT) for optimized resource usage.
- Track training performance and metrics using Weights and Biases.
- Evaluate model quality using ROUGE L scores before and after fine tuning.
- Deploy the fine tuned model and tokenizer to Hugging Face Hub.
- Provide an inference interface on Hugging Face Spaces.

---

## TOOLS AND TECHNOLOGIES
- GOOGLE COLAB for cloud GPU based training.
- UNSLOTH for parameter efficient fine tuning.
- TRANSFORMERS, PEFT, BITSANDBYTES, and ACCELERATE libraries.
- HUGGING FACE DATASETS for loading and preprocessing the medical dataset.
- WEIGHTS AND BIASES (WANDB) for experiment tracking.
- HUGGING FACE HUB for model hosting and deployment.
- GRADIO for creating an interactive demo interface.

---

## EXPECTED OUTCOME
- A fine tuned LoRA adapter for LLaMA 3.2 (3B) trained on medical reasoning data.
- A quantized and optimized model ready for deployment.
- A Hugging Face Space demo for real time medical question answering.
- Evaluation results comparing model performance before and after fine tuning.
