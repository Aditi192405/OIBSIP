# Email Spam Detection using Machine Learning

## Project Overview

This project uses Machine Learning techniques to classify SMS messages as either **Spam** or **Ham (Normal Message)**. The model is trained on the SMS Spam Collection Dataset and uses Natural Language Processing (NLP) techniques for text preprocessing and feature extraction.

## Dataset

* SMS Spam Collection Dataset
* Total Messages: 5572
* Classes:

  * Ham (Normal)
  * Spam

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* WordCloud

## Project Workflow

### 1. Data Collection

* Loaded SMS Spam Collection Dataset

### 2. Data Preprocessing

* Converted text to lowercase
* Removed punctuation
* Removed stopwords
* Cleaned text data

### 3. Feature Extraction

* TF-IDF Vectorization

### 4. Model Training

* Multinomial Naive Bayes
* Logistic Regression

### 5. Model Evaluation

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

### 6. Visualization

* Confusion Matrix Heatmap
* WordCloud for Spam Messages

## Results

The trained model achieved high accuracy in detecting spam messages and successfully classified custom messages as Spam or Ham.

## Project Structure

Email-Spam-Detection/

├── Email_Spam_Detection.ipynb

├── README.md

├── requirements.txt

├── screenshots/

└── dataset/

## Sample Prediction

Input:
Congratulations! You won a free iPhone. Click now!

Output:
Spam

## Future Improvements

* Deploy using Streamlit or Flask
* Add Email Spam Detection support
* Use advanced NLP models
* Improve real-time prediction capabilities

## Author

Aditi Kumari
Oasis Infobyte Data Science Intern
