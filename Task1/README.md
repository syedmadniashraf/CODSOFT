# Task 1 - Movie Genre Classification 🎬

## 🧠 Objective
To build a machine learning model that can predict the **genre of a movie** based on its **plot summary** or other textual information.

## 📘 Dataset
Used the [IMDB Genre Classification Dataset](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb).  
The dataset contains 54,000+ movie descriptions with their corresponding genres.

## ⚙️ Approach
1. **Loaded** the dataset (`train_data.txt`) using pandas  
2. **Cleaned** the text data (lowercase, removed stopwords, punctuations) using NLTK  
3. **Converted** text into numerical form using **TF-IDF Vectorizer**  
4. **Trained** a Logistic Regression model for genre prediction  
5. **Evaluated** model performance using accuracy and classification report  

## 📊 Results
- **Dataset Size:** 54,214 movies  
- **Model Used:** Logistic Regression  
- **Accuracy Achieved:** ~55%  
- **Sample Prediction:** `Fantasy` / `Animation` (depending on random plot)

## 🧰 Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLTK   

## 💡 Learnings
- Learned text preprocessing and TF-IDF concept  
- Understood model evaluation using precision, recall, and f1-score  
- Improved understanding of classification using Logistic Regression  

---

👨‍💻 **Intern:** Syed Madni Ashraf 
📅 CodSoft Machine Learning Internship 2025
