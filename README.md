# SENTIMENT-ANALYSIS

"COMPANY": CODTECH IT SOLUTION

"NAME": TANISHA SRIVASTAVA

"INTERN ID": CT12DK426

"DOMAIN": DATA ANALYSTICS

"DURATION": 12 WEEKS

"MENTOR": NEELA SANTOSH

"Description of my task"

Sentiment Analysis on Netflix Reviews Using NLP (Kaggle)
This part of the project focuses on performing sentiment analysis using Natural Language Processing (NLP) techniques on Netflix-related textual data, executed entirely on the Kaggle platform. The objective was to determine the emotional tone behind user-generated content such as reviews, titles, or descriptions to understand audience sentiment toward Netflix’s offerings.

Objective
The primary goal of this analysis was to classify user opinions or text data associated with Netflix shows and movies into positive, negative, or neutral sentiments. This kind of analysis can help content creators, marketers, and streaming platforms like Netflix evaluate viewer reactions and make content-related decisions based on emotional feedback.

Dataset
The dataset used for this task was sourced from Kaggle and included various types of textual content:

Viewer reviews (from third-party Netflix review datasets)

Movie and TV show descriptions

Title summaries

User comments or tweets related to Netflix (in some versions)

Each text entry was labeled (in supervised learning tasks) or unlabeled (in unsupervised or semi-supervised scenarios). Labeled datasets were used for training classification models.

Tools and Technologies
Kaggle Notebooks: Used as the development environment.

Python: Main programming language.

NLP Libraries: NLTK, spaCy, TextBlob, and transformers (for BERT-based models).

Scikit-learn: Used for traditional machine learning models.

Matplotlib & Seaborn: For data visualization.

Methodology
Data Cleaning and Preprocessing

Removed HTML tags, punctuation, and stopwords.

Tokenized the text and converted it to lowercase.

Used lemmatization to reduce words to their base form.

Exploratory Text Analysis

Word frequency analysis and word clouds were used to identify common themes.

Sentiment distribution graphs showed the proportion of positive, negative, and neutral entries.

Sentiment Scoring

For quick insight, tools like TextBlob were used to assign polarity scores to the text.

Text entries were categorized based on these scores:

Positive: polarity > 0

Neutral: polarity = 0

Negative: polarity < 0

Model Training

Models such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) were trained on labeled datasets.

A fine-tuned BERT model (Bidirectional Encoder Representations from Transformers) was used for advanced sentiment classification, which significantly improved accuracy.

Evaluation

Models were evaluated using metrics like accuracy, precision, recall, and F1-score.

BERT outperformed traditional models with an accuracy of over 90% on test data.

Key Findings
Most Netflix show descriptions had neutral to slightly positive tones.

Viewer reviews showed polarized sentiments, especially around controversial content or original series.

Sentiment analysis helped identify hidden user emotions and trends not captured by numeric ratings alone.

Conclusion
The sentiment analysis project highlights how textual data can be leveraged to gauge audience perceptions. Conducted entirely on Kaggle, the project demonstrates the application of both basic and advanced NLP techniques in a practical, real-world context. Such insights are invaluable for improving user engagement, curating personalized content, and refining marketing strategies.
