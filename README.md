# Hotel Reviews Sentiment Analysis with PineconeProject Purpose and Use Cases

The primary purpose of this project is to demonstrate how sentiment analysis and vector databases like Pinecone can be used to gain insights from customer feedback. It showcases the power of NLP techniques in understanding textual data and extracting valuable information for decision-making.
 

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

The sentiment analysis and opinion mining performed in this project reveal valuable insights into customer perceptions of various hotels and specific aspects of their experience. Here are some key observations:

Hotel Performance: By comparing the overall sentiment distribution for different hotels, we can identify those with higher customer satisfaction ratings. For example, the Intercontinental London The O2 received predominantly positive reviews across most areas, indicating a positive customer experience.

Areas for Improvement: The analysis highlights areas where hotels may need to focus on improvement. For instance, the Strand Palace Hotel and Britannia International Hotel Canary Wharf received negative or neutral feedback on room sizes and AC, suggesting potential areas for enhancement.

Customer Preferences: The project helps understand customer preferences by analyzing sentiment towards specific features like food, staff, cleanliness, and room size. This information can be used to tailor services and offerings to better meet customer expectations.

Time-Based Analysis: The ability to filter reviews by date enables the analysis of customer sentiment over time, allowing for the identification of trends and changes in perception. This is valuable for tracking the impact of improvements or changes made by the hotel.


## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License.
