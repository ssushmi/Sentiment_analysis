** Sentiment Analysis of Yelp Reviews using BERT & NLP**

This project performs sentiment analysis on reviews scraped from social media reviews using BERT-based transformers. It also visualizes sentiment distribution and generates a word cloud of positive reviews.

🧠** What This Project Does**
✅ Scrapes reviews from a Yelp business page using requests and BeautifulSoup

✅ Performs sentiment classification using nlptown/bert-base-multilingual-uncased-sentiment via HuggingFace Transformers

✅ Visualizes:
  Sentiment distribution (bar chart)
  Word cloud for positive reviews

✅ Exports sentiment results to CSV

**Dependencies**
Install required packages using pip:
pip install transformers torch beautifulsoup4 requests wordcloud pandas matplotlib

**Example Output**
Average Sentiment Score: 4.20
Positive Reviews: 9
Negative Reviews: 1

**📊 Sentiment Distribution Bar Chart**
Displays the count of reviews by sentiment score (1 to 5).

**☁️ Word Cloud of Positive Reviews**
Highlights common words in highly rated reviews (score ≥ 4).

