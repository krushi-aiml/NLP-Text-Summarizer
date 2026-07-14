# NLP Text Summarizer

An AI-based text summarization application that generates summaries using both extractive and abstractive summarization techniques.

## Features

- Extractive summarization using LSA algorithm
- Abstractive summarization using T5 Transformer model
- Paste text input
- Upload `.txt` files
- Select summary length (Short, Medium, Long)
- Word count analysis
- Compression ratio calculation
- Download generated summary
- Interactive Gradio web interface

## Technologies Used

- Python
- Hugging Face Transformers
- T5 Transformer
- PyTorch
- NLTK
- Sumy
- Gradio

## Model Used

- T5-small (Text-To-Text Transfer Transformer)

## How to Run

### Install dependencies

```bash
pip install -r requirements.txt