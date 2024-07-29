# WebSentinel
## Project Overview
This project aims to classify websites as either benign or malicious by analyzing both the URL and the content of the website. The system utilizes two main approaches: the Benign Sentinel and the Malicious Oversight.

Benign Sentinel: Builds a baseline using known safe websites.
Malicious Oversight: Reviews site content for patterns indicative of malicious intent.
This combined approach enhances the ability to spot suspicious URLs and improves cybersecurity protocols by providing a proactive measure against threats.

Table of Contents
Project Overview
Methodology
  1. Hyperlink Analysis Model
  2. Content Analysis Model
  3. Web Scraping
  4. Web Integration
Results and Discussion
Conclusion and Future Scope

## Methodology
    Hyperlink Analysis Model
    Dataset Overview
    URLs labeled as benign or malicious, including attributes like URL length, domain age, and special character presence.
    
    Pre-processing
    Cleaning: Remove duplicates.
    Normalization: Standardize URLs.
    Feature Extraction: URL length, subdomains, HTTPS presence.
    Label Encoding: Numerical label conversion.
    Model Training
    Split data into training and testing sets, then train with algorithms like Random Forest and SVM. Perform hyperparameter tuning.

### Content Analysis Model
Dataset Overview
Textual content of websites labeled as benign or malicious.

Pre-processing
Cleaning: Remove HTML tags and scripts.
Tokenization: Split text into words.
Vectorization: Convert text to numerical vectors using TF-IDF or embeddings.
Label Encoding: Numerical label conversion.
Model Training
Train on pre-processed text data using algorithms like Naive Bayes and LSTM. Optimize with hyperparameter tuning.

Web Scraping
Encoding File Paths
Ensure file paths are correctly encoded for consistency.

Utility Functions
Implement utility functions to streamline the scraping process.

Web Integration
Frontend Development
Design and develop the user interface.

Backend Integration
Integrate machine learning models with backend services.

Integration Flow
Coordinate frontend and backend for seamless user experience.

Results and Discussion
Evaluation of the Hyperlink Analysis Model
Assess model performance using metrics like accuracy, precision, recall, and F1-score.

Evaluation of the Content Analysis Model
Evaluate content model with similar performance metrics, focusing on accuracy and text classification precision.
