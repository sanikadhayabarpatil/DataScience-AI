# NLP Hindi Text Processing

## Project Overview
This project explores **Natural Language Processing (NLP) for Hindi text**, utilizing **AI4Bharat’s indic-nlp library** for tokenization and leveraging **fastText** embeddings fine-tuned for Hindi. The dataset consists of Hindi literary stories from prominent authors.

## Data Source
- The dataset is obtained from the [Hindi Aesthetics Corpus](https://github.com/gayatrivenugopal/Hindi-Aesthetics-Corpus/tree/master), which includes stories from renowned Hindi authors.
- The dataset is preprocessed, requiring minimal cleaning.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install indic-nlp-library fasttext numpy pandas matplotlib
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook NLP_HindiText.ipynb
    ```

## Key Features
- **Text Preprocessing**: Tokenization, normalization, and basic cleaning.
- **Tokenization**: Uses `indic-nlp-library` for Hindi text tokenization.
- **Word Embeddings**: Incorporates AI4Bharat’s fastText Hindi embeddings for further modeling.

## Results
The project demonstrates the ability to preprocess, tokenize, and prepare Hindi text data for downstream NLP tasks using state-of-the-art tools tailored for Indian languages.

## Author
- **Sanika Dhayabar Patil**
