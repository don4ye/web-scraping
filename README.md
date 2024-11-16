# Web Scraping Project

## Author
**Name:** Monsuru Adebisi 
**GitHub Repo:** [Web Scraping Repository](https://github.com/don4ye/web-scraping.git)

## Project Overview
This project demonstrates web scraping and natural language processing (NLP) using Python. It focuses on extracting information from an article, processing text data with spaCy, and analyzing tokens and lemmas through various tasks.

## Objectives
1. Learn to scrape web pages and save the content to local files.
2. Process and analyze text data using Python libraries like BeautifulSoup and spaCy.
3. Visualize results through histograms and draw meaningful insights.

## Tools and Libraries
The following tools and Python libraries were used in this project:
- **BeautifulSoup4**: For web scraping and parsing HTML documents.
- **spaCy**: For natural language processing, tokenization, and lemmatization.
- **Matplotlib**: For visualizing sentence scores.
- **Requests**: For fetching web pages.

## Tasks
1. **Web Scraping**: Fetched and extracted an article's HTML using BeautifulSoup and saved it as a `.pkl` file.
2. **Text Extraction**: Loaded the saved HTML and extracted text content using BeautifulSoup's `.get_text()` method.
3. **Token Analysis**: Identified the 5 most frequent tokens, excluding stopwords, punctuation, and whitespace.
4. **Lemma Analysis**: Identified the 5 most frequent lemmas, with similar filtering.
5. **Sentence Scoring**: Scored sentences by their token and lemma occurrences, visualized the results using histograms.
6. **Nouns-Only Analysis**: Discussed how to filter and analyze only nouns using spaCy's POS tagging.

## Visualizations
- Histograms of sentence scores were plotted using Matplotlib to visualize the distribution of scores.

## Challenges and Insights
- **Challenge**: Filtering text to include only specific parts of speech (e.g., nouns).
- **Solution**: Used spaCy's `token.pos_` attribute for POS tagging.
- **Interesting Insight**: The ability to extract meaningful insights by analyzing frequent tokens and lemmas in text.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/don4ye/web-scraping.git
