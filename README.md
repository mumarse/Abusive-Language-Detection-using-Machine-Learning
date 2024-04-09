# Abusive Language Detection using Machine Learning

This project demonstrates the process of detecting abusive language using various Machine Learning techniques, including Support Vector Machine, Naïve Bayes, Decision Tree, and Random Forest. It compares the performance of these techniques to determine which one is most effective for detecting abusive language and explains the reasons behind their effectiveness.

## Introduction

Abusive language detection is a crucial task in natural language processing, especially in online platforms where harmful content can have significant negative impacts. This project explores different ML techniques for detecting abusive language and provides insights into their effectiveness.

## Key Concepts

- Efficient loading of dataset from disk.
- Application of different Machine Learning techniques for abusive language detection, including data pre-processing and feature extraction.
- Basic machine learning workflow:
  1. Examine and understand data
  2. Build an input pipeline
  3. Build the model
  4. Train the model
  5. Test the model
  6. Improve the model and repeat the process

## Tools and Techniques

### Tools Used:
- Anaconda (Python distribution platform)
- Jupyter Notebook (Open-source web application)
- Python (programming language)

### Techniques Demonstrated:
- Support Vector Machine
- Naïve Bayes
- Decision Tree
- Random Forest

## Setup

### Libraries Used:
- Pandas
- scikit-learn
- joblib
- matplotlib
- seaborn
- googleapiclient

## Data Loading and Pre-processing

The project efficiently loads the dataset from disk and applies various pre-processing techniques to the data, including normalization, handling stop words, removing duplicate values, and handling outliers.

## Training and Testing

The data is split into 70% training and 30% testing datasets. Feature extraction is performed using TF-IDF (Term Frequency-Inverse Document Frequency), which is a widely used technique for text classification tasks.

## Machine Learning Techniques

The project applies the following ML techniques for abusive language detection:

1. **Support Vector Machine (SVM)**
2. **Naïve Bayes**
3. **Decision Tree**
4. **Random Forest**

## Performance Evaluation

The performance of each ML technique is evaluated based on metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and classification reports are also provided for detailed analysis.

## Results and Conclusion

The project concludes by comparing the performance of different ML techniques and provides insights into which technique is most effective for abusive language detection. Recommendations for further improvement and future work are also discussed.
