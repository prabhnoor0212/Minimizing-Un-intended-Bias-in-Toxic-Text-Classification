# Minimizing-Un-intended-Bias-in-Toxic-Text-Classification

The domain of classifying toxic comments in online conversations is a very sensitive one. Online bullying can severely impact someone’s mental health and can have very harsh consequences. The need for systems that can accurately filter online toxicity increases with the increase in the ease of access to the internet. This is a delicate domain to work in where un-intended bias has been observed to be a hindrance in building successful systems that can differentiate between toxic and non-toxic conversations. Thus, using global metrics such as accuracy, f1-score or AUC might not be ideal. Further, the use of basic Machine Learning models is just not enough. It is important to have the right set of data, modeling techniques, and scoring metrics to build accurate models. This work explores the use of a modified AUC metric that accounts for the performance of the model not just globally, but also incorporates the performance on individual identity subgroups. This work also compares performance using TfIdf and contextual representation of text on Logistic Regression, Random Forest, LSTM inspired architecture, and transformer-based architecture: BERT.


Dataset & Problem Definition: <a href="https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data">link</a>

1. <a href="https://github.com/prabhnoor0212/Minimizing-Un-intended-Bias-in-Toxic-Text-Classification/blob/main/baselines.ipynb">Baseline Notebook</a>
    - Text Featurization:
            - TfIdf
            - Glove Embeddigns
    - Models:
            - Logistic Regresion
            - Random Forest   
2. <a href="https://github.com/prabhnoor0212/Minimizing-Un-intended-Bias-in-Toxic-Text-Classification/blob/main/LSTM_architecture.ipynb">LSTM Notebook</a>
    - Text Featurization:
            - Glove Embeddigns + FastText Crawl (Concatenation)
    - Models:
            - LSTM based custom architecture 
3. <a href="https://github.com/prabhnoor0212/Minimizing-Un-intended-Bias-in-Toxic-Text-Classification/blob/main/bert-pre-train.ipynb">BERT Notebook</a>
    - Text Featurization:
            - BERT pre-trained
    - Models:
            - BET fine-tuned

#Final Report: <a href="https://github.com/prabhnoor0212/Minimizing-Un-intended-Bias-in-Toxic-Text-Classification/blob/main/EECS_5327_project_prabhnoor.pdf">link</a>
