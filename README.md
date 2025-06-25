# .News-Article-Classification-Fake-Real
1-Introduction
This project focuses on identifying whether a news article is real or fake using Natural Language Processing (NLP). The
exponential growth of digital media has made the spread of misinformation more rampant. Therefore, it's important to
develop systems to classify and detect fake news.

2. Abstract
We built a binary text classification model that processes a news article's content and predicts if it is fake or real. The
model uses cleaned textual data transformed via TF-IDF vectorization and is trained on labeled data using Logistic
Regression. A user-friendly interface was also developed using Streamlit to allow live predictions.

3. Tools Used
- Python
- Pandas
- Scikit-learn
- NLTK
- TF-IDF Vectorizer
- Logistic Regression / Naive Bayes
- Streamlit
- 
4. Steps Involved in Building the Project
1. Collected a labeled dataset from Kaggle containing real and fake news.
2. Preprocessed the text by lowercasing, removing punctuation, and stopword removal using NLTK.
3. Converted text into numeric format using TF-IDF vectorization.
4. Split the data and trained the model using Logistic Regression.
5. Evaluated model performance using accuracy and F1-score.
6. Saved the model and vectorizer using pickle.
7. Built a Streamlit app to input news content and display predictions.
   
5. Conclusion
The project successfully demonstrates the use of NLP and machine learning to combat misinformation. With decent
accuracy and a user-friendly interface, this model can serve as a baseline for more advanced fake news detection
systems.

