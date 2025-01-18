# AG-NEWS-PROJECT-OF-AI

INRODUCTION:

AG NEWS is likely a reference  to agricultural news, which is news about agriculture, including agirbusiness, best practices, & changing conditions.

OBJECTIVE:

To build a text classification model that accurately categorizes news articles into predefined categories: World, Sports, Business, and Science/Technology.

DATASET DESCRIPTION:

The AG News dataset is a collection of news articles labeled with four categories:

World

Sports

Business

Science/Technology

Workflow:

Data Preprocessing:

Removed stopwords, punctuation, and special characters.

Converted text to lowercase.

Tokenized the text (split sentences into words).

Applied lemmatization or stemming to normalize text.

Exploratory Data Analysis (EDA):

Visualized the distribution of categories.

Analyzed the most frequent words in each category.

Examined word count and text length patterns.




Modeling:

Tried multiple models for text classification:

Machine Learning models used:

Multinomial Naive Bayes.

DEEP Learning Models used:

(LSTM,GRU,Transformer-based models(E.g., BERT).

![Slide1-2](https://github.com/user-attachments/assets/66d54083-6a5a-4c07-8cd2-0c8ee700f588)


Metrics for Evaluation:

Accuarcy, precision, Recall, F1-score.


Vectorization:

CountVectorizer and TF-IDF for traditional models.

Tokenization and embeddings for Transformer-based models.

Evaluation:

Metrics used: Accuracy, Precision, Recall, F1-score.

Performed cross-validation for robust evaluation.

Analyzed the confusion matrix to assess misclassifications.

Hyperparameter Tuning:

Tuned parameters like learning rate, batch size, and optimizer settings for optimal performance.

Results:

Achieved 0.8984% accuracy on the test set with the best-performing model (e.g., bert-base-uncased).

The model was most accurate in the Business category and showed minor misclassification in Science/Technology articles.

![CamScanner 01-18-2025 16 26_1](https://github.com/user-attachments/assets/7cbbc5d4-900c-4563-9f5f-76538faf007f)


![Slide1-2](https://github.com/user-attachments/assets/ee5e5c77-2018-428b-a361-7d0d6c620ba7)









