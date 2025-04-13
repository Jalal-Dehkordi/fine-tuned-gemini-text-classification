# fine-tuned-gemini-text-classification
## NewsGroup Classifier with Gemini

![Python](https://img.shields.io/badge/Python-3.8%20%7C%203.9%20%7C%203.10-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This project is a text classifier for the **20 Newsgroups** dataset, fine-tuned using the **Gemini** model from Google GenAI. The goal of this project is to demonstrate the process of data preparation, fine-tuning the model, and evaluating its performance on test data.

---

## Project Overview

This project includes the following steps:

1. **Data Download and Preprocessing**:
   - Utilizes the [20 Newsgroups](https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html) dataset.
   - Cleans the data by removing email addresses, headers, and limiting text length.

2. **Model Fine-Tuning**:
   - Fine-tunes the **Gemini** model using the Google GenAI API.
   - Creates a custom model that classifies texts without requiring system instructions or additional prompts.

3. **Model Evaluation**:
   - Compares the model's performance before and after fine-tuning.
   - Calculates classification accuracy and token usage.

4. **Using the Fine-Tuned Model**:
   - Demonstrates how to use the custom model to classify new texts.

## Prerequisites

To run this code you need:
- Google API Key
- Kaggle account to run the notebook
- Python libraries:
  - `google-genai`
  - `pandas`
  - `scikit-learn`
  - `tqdm`
