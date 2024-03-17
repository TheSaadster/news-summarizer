# News Summarizer

This is a simple Python application built using Tkinter, NLTK, TextBlob, and Newspaper libraries to summarize news articles from URLs provided by the user.

### Installation
1. Make sure you have Python installed on your system.
2. Install the required libraries using pip:
    ```
    pip install tkinter nltk textblob newspaper3k
    ```

### How to Use
1. Run the script.
2. Enter the URL of the news article you want to summarize into the "Article URL" text box.
3. Click the "Summarize" button.
4. The title, author, publication date, summary, and sentiment analysis of the article will be displayed in the respective text boxes.

### Functionality
- **summarize():** This function is triggered when the "Summarize" button is clicked. It extracts information from the provided URL, summarizes the article, and performs sentiment analysis using TextBlob.


### Notes
- The application disables editing in the output text boxes to prevent unintended modifications.
- NLTK is used for natural language processing tasks.
- TextBlob is used for sentiment analysis.
- Newspaper library is utilized to extract and parse the article content from the provided URL.

### Disclaimer
This application relies on external libraries and APIs to extract and analyze news articles. The accuracy of the summarization and sentiment analysis may vary depending on the quality and content of the articles as well as the performance of the libraries used.