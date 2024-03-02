## Description

1. **Data Loading and Preprocessing:**
   - It loads email data from both legitimate and spam sources.
   - Cleans the emails by extracting relevant information like sender, recipient, subject, date, and content.

2. **Text Preprocessing:**
   - Tokenizes the content of emails, removes non-English words, and converts text to lowercase.

3. **Data Exploration:**
   - Explores the distribution of legitimate and spam emails using a bar plot.

4. **Feature Engineering:**
   - Converts the text data into numerical features using the Bag of Words (BoW) approach.
   - Splits the dataset into training, validation, and testing sets.

5. **Model Training and Evaluation:**
   - Trains three different Naive Bayes models (BernoulliNB, ComplementNB, and MultinomialNB) using the training data.
   - Evaluates the models' performance using accuracy scores.
   - Visualizes the accuracy of each model using a bar plot.

6. **Confusion Matrix Visualization:**
   - Calculates and visualizes confusion matrices for each model.
   - Confusion matrices show the performance of each model in terms of true positive, false positive, true negative, and false negative predictions.

Overall, the code performs a comprehensive analysis of email data, including preprocessing, feature engineering, model training, evaluation, and visualization of results, with a focus on Naive Bayes classification models.
