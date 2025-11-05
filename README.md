# news-article-classification-nlp

## Overview
This project classifies online news articles into multiple categories such as **Politics**, **Entertainment**, **Sports**, **Wellness**, etc., using NLP and classical machine learning algorithms.

## Objectives
- Perform multi-class text classification  
- Explore and visualize category distributions  
- Extract features with TF-IDF  
- Train models (Logistic Regression, Naive Bayes, Linear SVM)  
- Evaluate and compare performance metrics

## Data Preprocessing
- Removed HTML tags, punctuation, and numbers  
- Converted text to lowercase and lemmatized  
- Removed stopwords  
- Token count filtering (to remove extremely short news items)

## Models Implemented
| Model | Accuracy | F1-Score |
|--------|-----------|----------|
| Logistic Regression | ~85% | 0.84 |
| Linear SVM | ~86% | 0.85 |
| Naive Bayes | ~78% | 0.77 |

## Visualizations
- Top 10 Most Frequent Categories  
- Category Distribution Pie Chart  
- Average Text Length per Category  
- WordCloud of News Text  
- Confusion Matrices for each model  
- Model Accuracy and F1-Score comparisons  

## Technologies Used
Python, Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, NLTK

## Folder Info
- **notebooks/** → Jupyter Notebook with code  
- **reports/** → PDF report + images  
- **data/** → Dataset file (`data_news.xlsx`)

## How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/News_Article_Classification.git
   cd News_Article_Classification

## Contact

📧 Email: [singhbulbul485@gmail.com]  
🌐 LinkedIn: [https://www.linkedin.com/in/bulbul-singh-77b3a6201/] 
