# NLP_2025_Assignment1

## Overview
This project builds a text generator using **n-gram models (bigrams, trigrams, quadgrams)** to mimic Shakespeare’s style.

## Objectives & Overall Approach
- Load and preprocess Shakespeare's works.
- Construct **n-gram dictionaries**.
- Compute probability distributions for next-word prediction.
- Generate text using **weighted random sampling**.
- Compare bigrams, trigrams, and quadgrams.
- Conduct a human evaluation survey to assess the coherency and consistency with the Shakespearean style.

## Dataset
The dataset used is a `.txt` file containing **Shakespeare's sonnets**. The dataset contains **17,589 words**. The dataset is preprocessed by:
- Converting text to lowercase.
- Removing punctuation.
- Tokenizing words.
- Extracting bigrams, trigrams, and quadgrams.

## Instructions to Run the Code

### Steps
1. **Download** `shakespeare.txt` and save it in your Google Drive.
2. **Open** `NLP_Assignment1.ipynb` with **Colab**.
3. **Run** the first two chunks of code and follow the prompt to mount your Google Drive.
4. **Update** the path variable to your `shakespeare.txt` path.
5. **Run** the rest of the code by executing individual cells or selecting `Runtime → Run All`. 

## Expected Output
- A Shakespearean-style text generator that can generate sentences or paragraphs based on n-gram probabilities.
- Comparative analysis of **bigrams, trigrams, and quadgrams**.
