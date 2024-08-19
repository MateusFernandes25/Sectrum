# Sectrum

# Information Security Chatbot - Fine-tuning with LLaMA and QLoRA

## Overview

This repository addresses the development of an information security chatbot in Portuguese through fine-tuning of the LLaMA (Large Language Model Meta AI) open-source language model. The project aims to create a specialized chatbot capable of understanding and responding to queries related to information security.

## Methodology

To achieve this, the project employs the QLoRA (Quantized Low-Rank Adaptation) methodology, which allows for efficient fine-tuning of large language models by adjusting their weights. The retraining was conducted using a custom database comprising questions and answers specifically focused on information security topics.

## Performance

The fine-tuned model demonstrated superior performance compared to the base LLaMA-7B model in various Portuguese language tasks. Notably, it excelled in activities related to:

- **Semantic Similarity**
- **Textual Entailment**

In question-answering tasks, the chatbot's performance closely approached the average performance of the Sabiá-7B model, making it a competitive option for Portuguese language information security applications.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher
- PyTorch
- Hugging Face Transformers
- Transformers
- Tokenizer
- Accelerate

### Installation

Clone the repository:

```bash
git clone https://github.com/MateusFernandes25/Sectrum
