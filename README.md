# CodeGen LoRA Fine-Tuning

**CodeGen LoRA Fine-Tuning** is a project focused on fine-tuning the Salesforce **CodeGen-350M-mono** model for Python code generation using **LoRA (Low-Rank Adaptation)**. The goal is to create a lightweight, efficient model capable of generating accurate Python code for various programming tasks.

## Project Overview
- Fine-tuned the CodeGen-350M-mono model on the **flytech/python-codes-25k** dataset.
- Applied **LoRA** and **PEFT** techniques to reduce trainable parameters and optimize training efficiency.
- Utilized **4-bit quantization** with BitsAndBytes to significantly reduce memory usage while maintaining performance.

## Features
- Generates Python code from natural language instructions.
- Supports tasks like function implementation, data processing, and automation scripts.
- Trained with masked prompt-response pairs to focus learning on assistant outputs.
- Efficient and scalable training pipeline suitable for medium-sized datasets and limited hardware.

## Results
- Achieved high-quality Python code generation for a variety of programming prompts.
- Reduced memory footprint with 4-bit quantization and LoRA, enabling fine-tuning on consumer-grade GPUs.
- Demonstrated practical application of LLM fine-tuning for code generation tasks.

## Skills & Tools
- **Machine Learning & NLP:** PyTorch, Transformers, Hugging Face, LoRA, PEFT  
- **Optimization Techniques:** 4-bit quantization, low-rank adaptation, efficient training pipelines  
- **Dataset & Preprocessing:** flytech/python-codes-25k, prompt engineering, tokenization  

## Outcome
This project showcases the practical implementation of LLM fine-tuning for domain-specific code generation and demonstrates efficiency improvements with modern parameter-efficient techniques.
