# Fake News Prediction

This is a Python-based project that utilizes AI/ML algorithms to predict whether a news article is real or fake. The project is designed to help identify and combat the spread of misinformation by analyzing the content of news articles.

## Features

- **Machine Learning Models**: Implementation of algorithms for text classification.
- **Natural Language Processing**: Preprocessing and feature extraction from news articles.
- **Prediction**: Outputs whether the given news is real or fake.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: scikit-learn, pandas, numpy, nltk, matplotlib

## Dataset

- The dataset used for training and testing the models is sourced from [GeeksforGeeks](https://github.com/ChitranjanUpadhayay). Special thanks to GeeksforGeeks for providing this dataset.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/aayushmehta01/Fake-News-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fake-news-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the script:
   ```bash
   python main.py
   ```

## How It Works

1. **Data Preprocessing**: The dataset is cleaned and prepared by removing stop words, punctuation, and performing tokenization.
2. **Feature Extraction**: TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert text data into numerical features.
3. **Model Training**: Machine learning models (e.g., Logistic Regression, Random Forest, etc.) are trained on the preprocessed data.
4. **Prediction**: The trained model predicts the authenticity of the input news article.

## How to Use

1. Provide the news article text via the user interface or input prompt.
2. The system processes the text and outputs whether the article is "Real" or "Fake."

## Credits

- Dataset: [GeeksforGeeks](https://www.geeksforgeeks.org/)
- Tutorials and References:  Python documentation.

