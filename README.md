# Spam-Classifier
This project is a comprehensive SMS/Email Spam Classifier built using Python, Streamlit, Scilit-learn and NLTK.

## Description
The classifier uses a trained model to predict whether a given message is spam or not. The model is based on the Naive Bayes algorithm and uses TF-IDF for vectorization.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/princ0301/Spam-Classifier.git
   cd spam-Classifier

2. Install the required packages:
   ```sh
   pip install -r requirements.txt

3. Download NLTK stopwords:
   ```sh
   python -c "import nltk; nltk.download('stopwords')"

# Useage

1. Open the Streamlt app in your web browser.
  ```sh
  streamlit run app.py
  ```
2. Enter or copy the text message that you want to classify in the provided text area.
3. Click the "Predict" button.
4. The app will display whether the input message is classified as "Spam" or "Not Spam" based on the trained Multinomial Naive Bayes(MNB) model's prediction.

# Project Structure
- app.py: The main Streamlit application file that allows users to input text messages and get predictions.
- model.pkl: A pickled file containing the trained Multinomial Naive Bayes (MNB) machine learning model for spam classification.
- vectorizer.pkl: A pickled file containing the TF-IDF vectorizer used for text feature extraction.
- README.md: This comprehensive documentation file that covers the Streamlit app.

