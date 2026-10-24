# Real-Time Sentiment Analysis System with Web Scraping

## Project Overview
This project analyzes text sentiment using machine learning and live news headlines collected from the BBC News RSS feed.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- BeautifulSoup and Requests
- NLTK
- TF-IDF Vectorization
- Naive Bayes
- Logistic Regression
- Matplotlib
- Gradio

## Main Features
- Web scraping of live news headlines
- Text cleaning, stopword removal, and stemming
- TF-IDF feature extraction
- Sentiment classification into negative, neutral, and positive
- Model evaluation using accuracy, classification reports, and confusion matrices
- Sentiment visualization and Gradio dashboard
- Batch processing of collected headlines

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells in order.
3. Install the required Python libraries.
4. Train the models and evaluate their performance.
5. Fetch news headlines and run sentiment predictions.
6. Launch the Gradio dashboard.

## Dataset
The project uses the TweetEval sentiment dataset for model training and BBC News RSS headlines for live prediction.

## Note
Model performance on news headlines may differ from test performance because the training dataset contains social-media text.
