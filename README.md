# Emotion Detection using Multi-Label Classification with Large Language Models (LLMs) 🤖

This project focuses on building a multi-label emotion detection model to classify emotions in social media tweets using large language models (LLMs).

## 🎯 Objective
The goal is to accurately classify emotions across 11 categories (e.g., anger, joy, optimism, sadness) from tweets using fine-tuned LLMs such as Google/Gemma-2b.

## 🛠️ Key Features
- Multi-label emotion classification
- LLM experimentation: Meta-LLaMA, Qwen-2.5B, Google/Gemma-2b
- Text preprocessing using the `emoji` library
- Fine-tuning using LoRA (Low-Rank Adaptation)
- Class imbalance handling with `BCEWithLogitsLoss`
- MLOps integration with `wandb` and `MLflow`

## 📊 Results
| Metric       | Score  |
|--------------|--------|
| Macro F1     | 0.614  |
| Micro F1     | 0.690  |
| Accuracy     | 85%    |

## 📂 Project Structure
