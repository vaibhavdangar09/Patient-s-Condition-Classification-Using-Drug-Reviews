# Patient-s-Condition-Classification-Using-Drug-Reviews

![image](https://github.com/vaibhavdangar09/Patient-s-Condition-Classification-Using-Drug-Reviews/assets/85430510/023d79ac-becb-403a-9704-c4a71d73fcc9)



# Objective
The primary objective of this project is to develop a robust system capable of accurately classifying patient conditions solely based on their reviews. By leveraging advanced NLP techniques, the project aims to streamline the categorization process and provide valuable insights into patient health status.

# Methodology

Data Acquisition: A comprehensive dataset of patient reviews encompassing various medical conditions is collected to serve as the foundation for model training.

Data Preprocessing: The raw text data undergoes preprocessing steps including tokenization, stop word removal, and punctuation elimination. Subsequently, Word2Vec embedding is applied to convert words into numerical vectors, preserving semantic relationships.

Model Development: A Bidirectional LSTM RNN architecture is implemented to capture the sequential dependencies in the text data and extract meaningful representations. The model is trained on the labeled dataset to classify patient conditions accurately.

Model Evaluation: The performance of the model is evaluated using standard evaluation metrics such as accuracy, precision, recall, and F1-score. This assessment provides insights into the model's effectiveness in accurately classifying patient conditions.

Hyperparameter Optimization: Fine-tuning of model hyperparameters is conducted to optimize performance and maximize classification accuracy.

Results:The developed model achieves an impressive accuracy of 89% in classifying patient conditions based solely on their reviews. This high accuracy underscores the efficacy of Word2Vec embedding and Bidirectional LSTM RNNs in capturing the nuances of patient feedback and accurately categorizing medical conditions.

# Conclusion
This project demonstrates the effectiveness of employing Word2Vec embedding and Bidirectional LSTM RNNs in accurately classifying patient conditions based solely on their reviews. The high accuracy achieved signifies the potential of advanced NLP techniques in augmenting healthcare analytics and improving patient care.
