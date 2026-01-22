# AI-Based Phishing URL Classification

This project focuses on the detection and classification of malicious URLs using machine learning techniques.  
The primary goal is to identify and categorize URLs into four distinct classes based on their security risk.

## Problem Definition

Phishing and malicious URLs remain one of the most common attack vectors in cybersecurity.  
Traditional blacklist-based approaches are often insufficient against newly generated or obfuscated URLs.

This project addresses this problem by applying machine learning techniques to classify URLs based on extracted features rather than static signatures.

## Classification Categories

The model classifies URLs into the following four categories:

- **Phishing**: URLs designed to steal sensitive user information
- **Malware**: URLs distributing malicious software
- **Spam**: URLs related to unsolicited or deceptive content
- **Benign**: Legitimate and safe URLs

## Methodology

1. **Feature Engineering**
   - Manual feature extraction from URLs
   - Lexical and structural characteristics
   - URL length, special character frequency, token-based features, etc.

2. **Data Preprocessing**
   - Handling class imbalance
   - Cleaning and normalization of extracted features

3. **Model Training**
   - Supervised machine learning approach
   - Multi-class classification (4 classes)
   - Performance evaluated using standard classification metrics

## Project Structure

url_classification/
│
├── Kaggle1_feature_engineering(Manual Feature Extraction).ipynb
│ └── Feature extraction and exploratory analysis
│
├── url_classification.ipynb
│ └── Model training and evaluation
│
├── .gitignore
│ └── Git ignore rules (datasets, cache files, virtual environments)
│
└── README.md


## Dataset Information

The dataset used in this project contains URL samples labeled as phishing, malware, spam, or benign.

Due to the presence of credential-like patterns and sensitive strings commonly found in phishing datasets, the dataset is **intentionally excluded** from version control for security reasons.

This approach aligns with secure software development and data handling best practices.

## Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy

## Use Cases

- Phishing detection systems
- SOC and threat intelligence pipelines
- AI-assisted security analysis
- Academic research on malicious URL detection

## Notes

This project was developed as part of an academic research initiative focusing on cybersecurity and artificial intelligence.  
The implementation prioritizes security awareness, reproducibility, and professional software development practices.

## Author

Developed by **Ensar Özder**  
Cybersecurity & Artificial Intelligence Research
