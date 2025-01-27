# Word Embedding Project

This project involves preprocessing and cleaning a dataset of tweets for word embedding.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository_url>
    cd <repository_name>
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebook:
    ```sh
    jupyter notebook word_embd.ipynb
    ```

2. Follow the steps in the notebook to preprocess the data.

## Description

The notebook performs the following steps:
1. Imports necessary libraries.
2. Loads the dataset.
3. Preprocesses the text data by:
    - Normalizing tweets.
    - Fixing contractions.
    - Removing noisy tokens.
    - Removing stopwords.
4. Saves the cleaned data to `clean_data.csv`.

## Requirements

- Python 3.10.12
- pandas
- spacy
- nltk
- contractions
- tqdm
- scikit-learn

## License

This project is licensed under the MIT License.
