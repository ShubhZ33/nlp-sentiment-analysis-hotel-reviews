# Hotel Reviews Sentiment Analysis with Pinecone

This project demonstrates how to perform sentiment analysis on hotel reviews using Pinecone, a vector database. 

## Project Overview

The project uses a dataset of hotel reviews and applies NLP techniques to understand customer sentiment. The key steps include:

1.  **Data Loading and Preparation:** Loading a hotel reviews dataset from Hugging Face Datasets and preprocessing the text data.
2.  **Sentiment Analysis:** Utilizing a pre-trained RoBERTa model for sentiment analysis to classify reviews as positive, negative, or neutral.
3.  **Embedding Generation:** Generating embeddings for reviews using a SentenceTransformer model to capture semantic meaning.
4.  **Pinecone Integration:** Storing the embeddings and metadata (sentiment labels, scores) in a Pinecone index for efficient retrieval.
5.  **Opinion Mining:** Querying the Pinecone index to analyze customer opinions on specific aspects of hotels, such as room size, cleanliness, staff, food, and AC.
6.  **Visualization:** Creating visualizations to represent the sentiment distribution and overall customer perception.

## Requirements

*   Python 3.7 or higher
*   Pinecone API key
*   Required libraries: `sentence_transformers`, `pinecone-client`, `datasets`, `seaborn`, `matplotlib`, `transformers`


## Usage

1.  **Install Dependencies:**

2.  **Set up Pinecone:**
    *   Create a free Pinecone account.
    *   Obtain your API key and environment variables.
    *   Configure the Pinecone connection in the code.
3.  **Run the Notebook:**
    *   Execute the Jupyter Notebook or Google Colab notebook provided in this repository.
    *   Follow the steps outlined in the notebook to load data, perform sentiment analysis, store data in Pinecone, and analyze customer opinions.

## Results

The project provides insights into customer sentiment towards various aspects of hotels. The analysis and visualizations help identify areas for improvement and understand customer preferences.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
