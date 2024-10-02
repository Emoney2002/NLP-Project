# NLP-Project
Text Summarization with BART
Overview
This Jupyter notebook implements a text summarization tool using the BART (Bidirectional and Auto-Regressive Transformers) model from Hugging Face's Transformers library. The goal is to condense long articles into succinct summaries while preserving essential information.

Features
Pre-trained Model: Utilizes the BART model fine-tuned for summarization tasks, ensuring high-quality outputs.
Customizable Input: Users can easily input any text they wish to summarize.
Simple Interface: The notebook provides a straightforward way to generate summaries, making it user-friendly for both technical and non-technical users.
Installation
To run this notebook, you need to have the following libraries installed:

torch
transformers

You can install them using pip:


pip install torch transformers

How It Works

Importing Libraries: The notebook begins by importing necessary libraries and loading the BART model and tokenizer.
Defining the Summarization Function: A function generate_summary(text) is created to handle the summarization logic.

Inputting Text: Users can define the text to be summarized in the notebook.
Generating and Displaying Summary: The function is called with the input text, and both the original text and the generated summary are printed for comparison.



Conclusion
This notebook serves as a practical demonstration of using state-of-the-art NLP models for text summarization, providing an efficient way to distill information from lengthy texts.

