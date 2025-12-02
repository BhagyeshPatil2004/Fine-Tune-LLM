# Medicine Side Effects Prediction - Fine-Tuned LLM

This project involves fine-tuning a Large Language Model (LLM) to predict side effects of medicines based on user queries.

## Project Overview
The goal is to create a specialized model that can accurately identify and list potential side effects of various medications. This is achieved by training a base model on a specific dataset related to medical side effects.

## Key Concepts

### Fine-Tuning
Fine-tuning is the process of taking a pre-trained model (which has learned general language patterns from a vast amount of data) and training it further on a smaller, specific dataset. This adapts the model to perform better on a particular task—in this case, answering medical questions about side effects—without losing its general language capabilities.

### Quantization
Quantization is a technique used to reduce the memory footprint and computational resources required to run an LLM. It involves representing the model's weights with lower precision (e.g., using 4-bit integers instead of 16-bit or 32-bit floating-point numbers). This allows the model to run faster and on hardware with less RAM, with minimal loss in accuracy.

## Tools Used
- **Unsloth**: A library used for faster and more memory-efficient fine-tuning.
- **Base Model**: (Specify the base model if known, e.g., Llama-3, Mistral)
