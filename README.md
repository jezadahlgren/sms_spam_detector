# sms_spam_detector
Module 21 Challenge

**Name:** Module 21 Challenge: sms_spam_detector

**Description:**

According to the module notes, I will be refactoring code from an SMS text classification pipeline solution that constructed a linear Support Vector Classification model.  Once this is trained I created a Gradio app to host the application which will allow people to test thier text messages to find out if they are spam or not.  

**Support:**

The bulk of the supoort was provided through class lessons and ChatGPT.

**Libraries imported:**

- pandas
- gradio
- Importing 4 dependencies from sklearn
    - from sklearn.model_selection import train_test_split
    - from sklearn.pipeline import Pipeline
    - from sklearn.feature_extraction.text import TfidfVectorizer
    - from sklearn.svm import LinearSVC


**Data analysis process and results:**

The resulting app testing the following statements to see if they were spam or not: 
    | (Not Spam) | 1. You are a lucky winner of $5000! |
    | (Not Spam) | 2. You won 2 free tickets to the Super Bowl. |
    | (Spam)     | 3. You won 2 free tickets to the Super Bowl text us to claim your prize. |
    | (Spam)     | 4. Thanks for registering. Text 4343 to receive free updates on medicare. |