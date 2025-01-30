# Mental Health Conversational AI - LLaMA-2 Fine-tuning

This project fine-tunes the LLaMA-2-7b-chat model to provide empathetic and supportive responses for mental health conversations. The model is trained on a specialized mental health conversations dataset from Kaggle to enhance its ability to engage with individuals experiencing mental health challenges.

## Model Details

- Base Model: `NousResearch/Llama-2-7b-chat-hf`
- Fine-tuned Model Name: `HeartTalk`
- Training Parameters:
  - LoRA attention dimension: 64
  - LoRA alpha: 16
  - LoRA dropout: 0.1
  - 4-bit precision enabled

## Dataset

The model is trained on a mental health conversations dataset containing therapeutic dialogues and responses, sourced from Kaggle. The dataset includes:
- Context/Questions from individuals seeking support
- Professional responses and therapeutic guidance
- Various mental health topics and scenarios

## Key Features

- Specialized in mental health support conversations
- Fine-tuned for empathetic responses
- Trained to handle sensitive topics appropriately
- Uses LoRA for efficient fine-tuning

## Usage

The model is designed to provide supportive responses to mental health-related queries. Example usage:

```python
input_text = "i feel that am lonely"
# Use the model to generate a supportive response
