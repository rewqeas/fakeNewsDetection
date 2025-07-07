
# 📰 Fake News Detection App

A web-based application to detect whether a news article is **real** or **fake** using machine learning and natural language processing (NLP) techniques.

## 🚀 Project Overview

This project aims to classify news articles as either **real** or **fake** using a logistic regression model trained on a text dataset. The frontend is built with **Streamlit**, offering an intuitive interface for users to input news content and receive instant predictions.

## 🧠 Technologies Used

- **Python**
- **Streamlit** – for the web app
- **scikit-learn** – for model building and vectorization
- **Joblib** – for model and vectorizer serialization
- **Jupyter Notebook** – for data cleaning, preprocessing, training

## 📂 Files

- `fake_news_detection.ipynb`: Notebook containing the data preprocessing, model training, and evaluation.
- `app.py`: Streamlit application script.
- `vectorizer.jb`: Trained TF-IDF vectorizer used for transforming input text.
- `lr_model.jb`: Trained logistic regression model.

## 🛠️ How to Run

1. **Clone the repository** or download the project files.
2. Make sure Python is installed on your machine.
3. Install the required libraries:
   ```bash
   pip install streamlit scikit-learn joblib
   ```
4. Place the `vectorizer.jb` and `lr_model.jb` files in the same directory as `app.py`.
5. Run the app:
   ```bash
   streamlit run app.py
   ```

## 🧪 How It Works

1. User enters a news article into the text area.
2. Text is transformed using the pre-trained `TF-IDF Vectorizer`.
3. Transformed input is passed to the trained `Logistic Regression` model.
4. Prediction is displayed on the screen: ✅ Real or ❌ Fake.

## 📈 Model Info

- **Model**: Logistic Regression
- **Vectorizer**: TF-IDF
- **Evaluation**: Trained and tested on a labeled dataset of news articles.

## 📌 Future Improvements

- Add support for multiple models (e.g., Random Forest, Naive Bayes)
- Provide explanation for predictions (using tools like SHAP)
- Deploy on the cloud using services like Heroku or Streamlit Cloud

