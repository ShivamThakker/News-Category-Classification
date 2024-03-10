# News-Category-Classification

In order to run this program you need following libraries
- pandas, numpy, re, nltk, datetime, swifter
- train_test_split, LabelEncoder, matplotlib.pyplot, TfidfVectorizer, TruncatedSVD
- accuracy_score, confusion_matrix, SGD , xgb

This project classifies 42 news category from the HuffPost dataset.

The link to download the dataset is [here](https://www.kaggle.com/datasets/rmisra/news-category-dataset).

I along with my team have performed following steps:

1) Preprocessed the dataset
2) Built the TF-IDF vectorizer
3) Performed dimesionality reduction such as SVD and PCA. Used explained variance ratio to determine the perfect n_components for SVD
4) Trained model such as Logistic Regression, Random Forest, xGBoost, ANN and CNN
5) Compared the accuracy, confusion matrix and model accuracy and model loss vs epochs curve
