# ExtractiveTextSummarizer

#### This project is involved in dealing with the mechanism and the effectiveness of the T5 (Text-To-Text Transfer Transformer) model for text summarization. We have showed how T5 is different form other transformers. We also figured out how is the working of T5 tansformer different from that of Convolutional Neural Networks. Our study examines the working of the component blocks and the sublayers of self-attention, add & normalize and feedforward used by T5. We have started with preprocessing the available data from our dataset followed by defining the model. Then we have trained and tested the model with 80% being the training part and 20% being the testing part. The tokenization also has been done in this specific part of our project. After that our project aims to validate the results from the model. It also examines the impact of hyperparameters and dataset characteristics on T5’s efficiency to summarize. The results demonstrate T5’s ability to extract summaries from the input text, making use of the optimized parameters for enhanced performance.This research contributes valuable insights to the application of transformer-based models in text summarization, providing a detailed guide for researchers.

# Text Summarizer with T5 Transformer Model

<img src="https://cdn-images-1.medium.com/max/932/1*iJcUH1F0TmCQE5p2wQt9og.png" width="1000" height="750" />


## Overview

This project is a text summarizer implemented using the T5 Transformer model with a beam search algorithm for extractive text summarization. The T5 model, known for its versatility in natural language processing tasks, is fine-tuned on summarization data to generate concise and coherent summaries of input text.



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

2. Install dependencies:

   ```bash
      cd text-summarizer
      pipenv install

3. Run the summarizer script:

   ```bash
   pipenv run python summarizer.py --input_file input.txt --output_file output_summary.txt

4. Upload the dataset file in your CoLab folder and change the pathway of the dataset file to the one that you just uploaded in your CoLab. Now, run the code

5. Explore the options and customize the summarizer for your needs


# Results 

To determine the performance of our model, we use a
measure called ROUGE-score, which measures how well a
generated text (like a summary) matches a reference or a
set of reference texts. Two of main types of ROUGE scores:
• Rouge N: Measures how many sequences of n consecutive words (n-grams) in the generated text match those
in the reference text. ROUGE N is further classified
into many types, two of which are ROUGE 1 and
ROUGE 2.
• Rouge L: Examines the longest common subsequences
of words between the generated and reference summaries.

<img width="425" alt="Rouge_score" src="https://github.com/DataScience-ArtificialIntelligence/ExtractiveTextSummarizer/assets/99867617/79d1ea99-95a7-40fa-b295-4fc3357e2f4e">

## Acknowledgements
We would like to express our sincere gratitude to Dr. Animesh Chaturvedi for providing us with the invaluable opportunity to work on this project exploring text summarization, a cutting-edge technology within the field of Artificial Intelligence. 
Providing expert guidance and feedback: He consistently offered insightful suggestions and constructive criticism, which helped us refine our approach and improve our understanding of the subject matter.
Creating a supportive and stimulating learning environment: He fostered a collaborative atmosphere that encouraged open discussion and creative thinking, enabling us to learn from each other and grow as individuals.
Sharing his vast knowledge and experience: He generously imparted his deep understanding of the field, providing us with valuable theoretical and practical knowledge that we will carry forward in our future endeavors.
We are immensely grateful to Dr. Chaturvedi for his dedication, mentorship, and unwavering support. This project would not have been possible without his invaluable contributions.
