# Similarity Measure for LLM-based on Falcon 7B  

This repository focuses on **fine-tuning the Falcon 7B model** for **mental well-being tasks**, improving similarity measures for question-answer generation. The model is designed to enhance contextual understanding and generate more relevant responses, helping both patients and professionals in the mental health domain.  

## Overview  

The **Falcon 7B model**, based on transformer architecture, processes input efficiently by capturing long-range dependencies between words. Unlike recurrent neural networks (RNNs), Falcon’s attention mechanism enables it to focus on crucial parts of a query, making it ideal for NLP applications in sensitive fields like mental health.  

To fine-tune the model, we used the **Psych8k dataset**, which contains **8187 question-answer pairs** extracted from therapist-patient conversations. These interactions were generated via GPT-4 with instruction tuning, offering **high-context dialogue** to improve the model's understanding of mental health queries. [Psych8k Dataset on HuggingFace](https://huggingface.co/datasets/EmoCareAI/Psych8k).  

## Installation  

Clone the repository:  

```bash
git clone https://github.com/iqraRajpoot/Similarity_measure_for_llm_based_on_Falcon_7B.git
cd Similarity_measure_for_llm_based_on_Falcon_7B
```

Install dependencies using:

```bash
pip install torch transformers datasets accelerate numpy tqdm
```
## Mental Health Query Validation System

This repository also includes a system for detecting and validating mental health-related queries. It checks for relevant keywords, emotional phrases, and context to ensure the AI responds appropriately. This helps create more reliable and sensitive mental health assistants, making them better suited for real-world support.

Install dependencies using:

```bash
pip install -U bitsandbytes gradio
```
## Results

The fine-tuned Falcon 7B model provides improved question-answer similarity in the mental well-being domain. By leveraging the Psych8k dataset, the model enhances contextual awareness, leading to more relevant and coherent responses in mental health conversations.

## License & Acknowledgments

This project is licensed under the MIT License. The Falcon model is developed by Hugging Face, and the Psych8k dataset was created by J. M. Liu et al. (2023) for mental well-being research.
