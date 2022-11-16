# Dissertation


The paper first analyses five supervised machine learning algorithms commonly used in fraud detection on a well-known, 'raw' real-world dataset and evaluates their performance. It then applies several resampling and feature selection techniques to combat the class imbalance problem and to enhance performance of the algorithms. Finally, the best performing classifier is selected, and paired up with classifiers, creating ensemble models to examine whether their combined workings improve their capabilities in detecting fraud cases. 

The overall aim of this experiment, therefore, is not only to find the most efficient combination of the above techniques and classifiers and see whether they can outperform existing results, but also to highlight the incremental improvements in performance by each consecutive steps - resampling, feature selection, and ensemble models. 

**Dataset**
The real-world dataset being used in this paper was obtained from Kaggle (2021). It contains 284,807 transactions made by credit cards over two days in September 2013 by European cardholders, out of which only 492 are frauds (0.172%), making it a highly unbalanced dataset. Available at: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
