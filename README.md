# NLP Midterm Project: Grammar Autocorrector

## Overview

The **Grammar Autocorrector** is an NLP-based system designed to automatically correct grammatical errors in text. The project utilizes deep learning techniques to identify and rectify mistakes, improving the overall grammatical accuracy of written content.

This project is developed as part of the NLP midterm assignment.

## Features

- Automatic grammar error detection and correction
- Pre-trained models for efficient predictions
- Easy deployment and usage

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/NLP-Grammarly.git
   cd NLP-Grammarly
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. If using Google Colab, open the notebook: [Open in Colab](https://colab.research.google.com/github/justxoai/NLP-Grammaly/blob/main/GrammarCorrection.ipynb)

## Usage

To run the grammar correction model:

1. Load the trained model in the Jupyter Notebook:
   ```python
   from your_model import load_model
   model = load_model("path/to/model")
   ```
2. Process input text:
   ```python
   corrected_text = model.correct("Your input sentence with errors")
   print(corrected_text)
   ```
3. Evaluate the model on test data using:
   ```python
   model.evaluate("path/to/test_data")
   ```

## Data and Model Download

The dataset and pre-trained model can be downloaded from:

- **Dataset:** C4 200M Grammar Error Correction
- **Pre-trained Model:** T5

## Documentation

For more details on the implementation and methodology, refer to the project notebook: [GrammarCorrection.ipynb](https://github.com/justxoai/NLP-Grammaly/blob/main/GrammarCorrection.ipynb)

## References and Resources

- LeewanHung. “T5_Grammar.” Kaggle, 2023. [Link](https://www.kaggle.com/code/leewanhung/t5-grammar)
- Cquentin48. “Grammar correction.” Kaggle, 2024. [Link](https://www.kaggle.com/code/cquentin48/grammar-correction#Grammar-correction-using-custom-deep-learning-model)
- Dario Cioni. “C4 200M Grammar Error Correction dataset.” Kaggle, 2023. [Link](https://www.kaggle.com/datasets/dariocioni/c4200m)
- Papers with Code. “Grammatical Error Correction.” Papers with Code, 2023. [Link](https://paperswithcode.com/task/grammatical-error-correction)
- Microsoft. “UniML.” GitHub, 2023. [Link](https://github.com/microsoft/unilm)
- Yassin522. “English-Grammar-Error-Correction.” GitHub, 2024. [Link](https://github.com/Yassin522/English-Grammar-Error-Correction)
- Ben Newman. “S24 Hugging_Face_Transformers_Tutorial.” Google Colab, Spring 2024. [Link](https://colab.research.google.com/drive/13r94i6Fh4oYf-eJRSi7S_y_cen5NYkBm)
- Jacob Murel Ph.D, Joshua Noble. “What is an encoder-decoder model?.” IBM Think, 2024. [Link](https://www.ibm.com/think/topics/encoder-decoder-model)