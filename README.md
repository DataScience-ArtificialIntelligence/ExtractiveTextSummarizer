# ExtractiveTextSummarizer

## This project is involved in dealing with the mechanism and the effectiveness of the T5 (Text-To-Text Transfer Transformer) model for text summarization. Our study examines the working of the component blocks and the sublayers used by T5. It also examines the impact of hyperparameters and dataset characteristics on T5’s efficiency to summarize. The results demonstrate T5’s ability to extract summaries from the input text, making use of the optimized parameters for enhanced performance.This research contributes valuable insights to the application of transformer-based models in text summarization, providing a detailed guide for researchers.

# Text Summarizer with T5 Transformer Model

<img src="https://cdn-images-1.medium.com/max/932/1*iJcUH1F0TmCQE5p2wQt9og.png" width="2000" height="1000" />


## Overview

This project is a text summarizer implemented using the T5 Transformer model with a beam search algorithm for extractive text summarization. The T5 model, known for its versatility in natural language processing tasks, is fine-tuned on summarization data to generate concise and coherent summaries of input text.

![Summarizer Demo](path/to/demo/screenshot.png)

## Features

- **T5 Transformer Model**: The text summarizer is powered by the T5 Transformer model, which has been pretrained on a large corpus and fine-tuned specifically for extractive summarization.

- **Beam Search Algorithm**: We use a beam search algorithm to enhance the quality of the generated summaries by considering multiple possible sequences of words.

- **Customization**: Easily customize the summarizer for your specific use case by adjusting parameters and fine-tuning on your own dataset.

## Getting Started

### Prerequisites

- Python 3.x
- Pipenv (optional but recommended)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/text-summarizer.git
