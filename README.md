# NLP and Text Cleaning in Python

This repository contains a Jupyter notebook that demonstrates the process of cleaning and preparing text data for Natural Language Processing (NLP) tasks using Python. The notebook makes use of several popular Python libraries including NLTK, pandas, and seaborn to perform a series of text preprocessing steps. The data used in this notebook is the Myers-Briggs Type Indicator (MBTI) dataset, which contains text posts associated with different personality types.

## Overview

The notebook covers the following key topics:

### 1. Importing Libraries and Downloading NLTK Corpora
- Import essential libraries such as NLTK, pandas, numpy, matplotlib, and seaborn.
- Download required NLTK corpora for tokenization and stop words.

### 2. Loading and Exploring the Dataset
- Load the MBTI dataset directly from a URL.
- Inspect the dataset structure and visualize the distribution of different MBTI personality types.

### 3. Data Cleaning and Preprocessing
- **Separating Posts**: Each post in the dataset is separated into individual rows to increase the number of samples.
- **Removing Noise**: Replace URLs in the text with a placeholder string.
- **Lowercasing**: Convert all text to lowercase to standardize the data.
- **Removing Punctuation**: Strip out punctuation marks from the text.
- **Tokenization**: Split text into tokens (words) using NLTK's TreebankWordTokenizer.
- **Stemming**: Reduce words to their base or root form using the Snowball Stemmer.
- **Lemmatization**: Convert words to their base form using the WordNet Lemmatizer.
- **Stop Words Removal**: Remove common stop words that do not contribute to the text's meaning.

### 4. Visualizations
- Plot the distribution of MBTI personality types before and after separating the posts.

## Getting Started

To get started with this notebook, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/nlp-text-cleaning.git
   cd nlp-text-cleaning
   ```

2. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook
   ```

## Dependencies

- Python 3.x
- NLTK
- pandas
- numpy
- matplotlib
- seaborn

These dependencies can be installed using the provided `requirements.txt` file.

## Dataset

The MBTI dataset used in this notebook can be found [here](https://raw.githubusercontent.com/Explore-AI/Public-Data/master/Data/classification_sprint/mbti_train.csv).

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License.

---

This repository provides a comprehensive guide to text cleaning and preprocessing, which are crucial steps in preparing textual data for NLP tasks. By following the steps outlined in the notebook, you will gain a solid understanding of how to clean and preprocess text data effectively using Python.
