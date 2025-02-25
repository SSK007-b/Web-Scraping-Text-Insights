# 📝 Web Scraping & Text Analysis for Sentiment & Readability  

## 📌 Project Overview  
This project performs **web scraping, text extraction, and NLP-based sentiment analysis** on articles. It processes text data by removing stopwords, analyzing sentiment, computing readability scores, and generating structured outputs in CSV format.  

## 🚀 Features  
✔ **Web Scraping with BeautifulSoup** – Extracts titles & text from URLs.  
✔ **Text Preprocessing** – Removes stopwords and tokenizes words.  
✔ **Sentiment Analysis** – Calculates **positive, negative, polarity & subjectivity scores**.  
✔ **Readability Analysis** – Computes **Fog Index, Complex Words %, Avg. Sentence Length**, etc.  
✔ **Personal Pronoun Count** – Detects **first-person pronoun usage**.  
✔ **CSV Output Generation** – Saves structured data into `Output_Data.csv`.  

## 📂 Project Structure  
┣ 📜 script.py # Python script for scraping & analysis
┣ 📂 InputData # Folder containing URLs for scraping
┣ 📂 OutputData # Generated output with sentiment & readability scores


## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/WebScraping-TextAnalysis.git
cd WebScraping-TextAnalysis

pip install -r requirements.txt
```
# Example Output  
URL_ID, Positive Score, Negative Score, Polarity Score, Subjectivity Score, Avg. Sentence Length, % Complex Words, Fog Index, Complex Word Count, Word Count, Avg. Syllables per Word, Personal Pronouns, Avg. Word Length
101, 12, 5, 0.4118, 0.068, 19.5, 0.22, 8.3, 45, 210, 1.4, 3, 4.7
102, 8, 3, 0.4545, 0.065, 21.2, 0.18, 9.1, 36, 198, 1.5, 5, 4.2
...
