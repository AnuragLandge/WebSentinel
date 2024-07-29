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
### Hyperlink Analysis Model
The dataset includes URLs labeled as benign or malicious, sourced from repositories tracking known safe and harmful sites, with attributes like URL length, domain age, and special character presence. The pre-processing involves cleaning the dataset by removing duplicates and irrelevant data, normalizing URLs to a standard format, extracting features such as URL length, subdomains, and HTTPS presence, and encoding labels into numerical format for model training. The dataset is split into training and testing sets. Machine learning algorithms like Random Forest and SVM are used to train the model, with hyperparameter tuning performed to optimize performance.

### Content Analysis Model
This dataset comprises the textual content of websites labeled as benign or malicious, sourced from various web crawlers and online databases. Pre-processing involves cleaning the text by removing HTML tags and scripts, tokenizing the text into words or tokens, vectorizing text into numerical vectors using techniques like TF-IDF or word embeddings, and encoding labels into numerical format. Models are trained on the pre-processed text data using algorithms like Naive Bayes and LSTM, with hyperparameter tuning conducted to enhance performance.

### Web Scraping
File paths are encoded correctly to ensure consistency and accessibility during the scraping process. Utility functions are implemented to streamline various tasks involved in web scraping, making the process more efficient and manageable.

### Web Integration
The user interface is designed and developed to provide an intuitive and user-friendly experience. Machine learning models are integrated with backend services to process and classify data effectively. The integration flow ensures seamless coordination between the frontend and backend, providing a smooth user experience.

## Results and Discussion
Evaluation of the Hyperlink Analysis Model
The performance of the hyperlink analysis model is assessed using metrics such as accuracy, precision, recall, and F1-score, providing insights into its effectiveness in classifying URLs.

Evaluation of the Content Analysis Model
The content analysis model is evaluated using similar performance metrics, focusing on accuracy and precision in text classification to determine its reliability and accuracy.
