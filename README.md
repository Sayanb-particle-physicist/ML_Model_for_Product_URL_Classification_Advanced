# ML Model for Product URL Classification (Advanced)

This project develops and evaluates a machine learning model that classifies product URLs into relevant categories (e.g., electronics, clothing, groceries) based on textual and structural features.

## 🚀 Objective
To automatically identify the product category from a given URL using machine learning and NLP techniques.

## 🧠 Key Features
- Data preprocessing and feature extraction from URLs
- TF-IDF and Bag-of-Words vectorization
- Model training using Logistic Regression, Random Forest, and XGBoost
- Model evaluation and visualization
- Hyperparameter tuning for performance optimization

## 🧰 Tools and Libraries
- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- nltk / re (for text processing)

## 📊 Output
- Confusion matrix and accuracy metrics
- Predicted category samples
- Model performance comparison

## 📖 Example
```python
url = "https://www.amazon.in/Samsung-Galaxy-Smartphone"
predicted_category = model.predict([url])
print(predicted_category)
