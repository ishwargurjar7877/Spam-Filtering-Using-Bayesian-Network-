# SMS Spam Detection with Bayesian Networks  

This project develops a *spam detection system* that classifies SMS messages into *ham (non-spam)* or *spam* categories utilizing *Bayesian Networks*. By employing probabilistic reasoning, the model effectively discerns unwanted messages based on textual patterns.  

## Main Features  
•⁠  ⁠*Bayesian Network Model:* Defines conditional dependencies between message labels and word occurrences.  
•⁠  ⁠*TF-IDF Vectorization:* Transforms text data into numerical features, highlighting the importance of words in messages.  
•⁠  ⁠*Binary Feature Transformation:* Converts TF-IDF features into binary format, indicating the presence or absence of words for Bayesian analysis.  
•⁠  ⁠*Training & Evaluation:* Implements *Maximum Likelihood Estimation* for training, with performance metrics including precision, recall, F1-score, and accuracy.  

## Dataset  
The dataset comprises 5,572 SMS messages categorized as either *spam* or *ham*. The focus is on two key columns:
•⁠  ⁠*Label:* Indicates the target class (spam or ham)  
•⁠  ⁠*Message:* Contains the text of the SMS  

## Results  
After training, the model produces a *classification report* that includes critical metrics such as precision, recall, F1-score, and accuracy. These metrics are vital for evaluating the effectiveness of the Bayesian network in differentiating between spam and non-spam messages.  

This project serves as a practical implementation of Bayesian networks for text classification, laying the groundwork for further investigation in the field of *probabilistic machine learning*.
