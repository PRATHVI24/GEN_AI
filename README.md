# GEN_AI

# Project Name: HuggingFace Model Integration with Transformers

## Overview
This repository demonstrates how to integrate and fine-tune large language models using HuggingFace's `transformers` library. It includes examples of how to load models like `Mistral-7B-v0.1` and `Zephyr-7b-alpha` in 4-bit precision for efficient inference.

## Features
- Load models with `transformers` in 4-bit precision for optimal performance on CUDA devices.
- Prompt-based generation using tokenizers and causal language models.
- Custom templates for chat-based generation.
- Example scripts for generating text with models like `Mistral` and `Zephyr`.

## Requirements
Ensure you have the following dependencies installed:
- `transformers`
- `bitsandbytes>=0.39.0`
- `accelerate`

## Libraries Used
- `transformers`: A library by Hugging Face for state-of-the-art NLP models.
- `bitsandbytes`: A library for efficient quantization of models.
- `accelerate`: A library by Hugging Face to optimize and accelerate training and inference.
- `torch`: PyTorch, an open-source machine learning library used for tensor computations and model training.

## Notes
To use models from HuggingFace that are behind gated access, ensure you have logged in using your HuggingFace credentials.

--from huggingface_hub import login
--login(token='YOUR_HF_TOKEN')

## Output







