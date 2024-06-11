**Social Network Analysis Assignment:**

**Identifying Communities of Interest:**

**Question:- Analyze a social network dataset (e.g., online forum discussions, social media groups) to identify communities with shared interests or opinions. Explore the characteristics and potential applications of these communities.**

**Link of the dataset:-** https://www.kaggle.com/datasets/kazanova/sentiment140

**Answer:-**

**Sentiment Analysis on Social Network Data:**

The analysis focused on sentiment analysis using a social network dataset. Initially, data preprocessing steps were performed, including cleaning, removing stopwords, punctuations, URLs, numeric numbers, and repeating characters. Tokenization, stemming, and lemmatization were applied to prepare the text data. The dataset was then split into training and testing sets.

**TensorFlow-based Model Training:**

A TensorFlow-based model was implemented for training, consisting of an embedding layer, LSTM layer, dense layers, and activation functions. The model was compiled with binary crossentropy loss and RMSprop optimizer. Training and validation were conducted with parameter tuning, specifying batch size and epochs.

**Evaluation and Performance Metrics:**

The trained model was evaluated on the test data, achieving an accuracy of 75%. Predictions were made on the test data, and a confusion matrix was generated to assess the model's performance. Additionally, an ROC curve was plotted to visualize the true positive rate and false positive rate.

**Conclusion:**

The analysis demonstrated the process of sentiment analysis on social network data using machine learning techniques, aiming to classify tweets into positive and negative sentiments.
