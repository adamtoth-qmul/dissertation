# **Credit Card Fraud Detection Using Supervised Machine Learning Algorithms - Experiments with Resampling, Feature Selection, and Ensemble Models**

The paper first analyses *five supervised machine learning algorithms* (**Logistic Regression, K-Nearest Neighbours, Decision Tree, Random Forest, Naïve Bayes**) commonly used in fraud detection on a well-known, 'raw' real-world dataset and evaluates their performance. It then applies several *resampling* (**Random Undersampling, Near Miss, Tomek Links, Random Oversampling, Synthetic Minority Oversampling, Adaptive Synthetic Oversampling**) and *feature selection* techniques (**ANOVA-F and Recursive Feature Elimination with Decision Tree**) to combat the class imbalance problem and to enhance performance of the algorithms. Finally, the best performing classifier is selected, and paired up with classifiers, creating *ensemble models* (**Simple and Weighted Majority Voting based**) to examine whether their combined workings improve their capabilities in detecting fraud cases. 

The *overall aim* of this experiment, therefore, is not only to find the most efficient combination of the above techniques and classifiers and see whether they can outperform existing results, but also *to highlight the incremental improvements in performance by each consecutive steps - resampling, feature selection, and ensemble models.* 

## **Why These Techniques?**
Resampling and feature selection techniques commonly found in my literature review were included in the experiment, whilst making sure simpler and more complex of these were also represented. 

## **Challenges and Future Research Directions**
* Hyperparameter tuning could have seriously improved scores further. It would have been also nice to see more resampling and feature selection techniques.
* Code blocks used were not necessarily the most computationally efficient ones. Even without hyperparameter optimisation, training times seriously limited the amount of work that I managed to accomplish. If I had more time, I could have experimented even more with the ensemble models – that part of the research lacked a rigorous approach and depended more on intuition gained from the previous stages.

## **Dataset**
The real-world dataset being used in this paper was obtained from Kaggle (2021). It contains 284,807 transactions made by credit cards over two days in September 2013 by European cardholders, out of which only 492 are frauds (0.172%), making it a highly unbalanced dataset. Available at: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


## **Results**
## **Stages: Raw Data --> Under & Oversampling Techniques --> Feature Selection --> Ensemble Models**
<img width="450" alt="Screenshot 2023-01-08 at 19 39 02" src="https://user-images.githubusercontent.com/118363955/211215571-742cf901-d3ef-4f5a-8a55-7dac83f0ad06.png">
<img width="707" alt="Screenshot 2023-01-08 at 19 38 50" src="https://user-images.githubusercontent.com/118363955/211215578-8de2ccbd-5c15-4275-8b6b-975d47289d4b.png">
<img width="695" alt="Screenshot 2023-01-08 at 19 39 20" src="https://user-images.githubusercontent.com/118363955/211215583-512945bf-be4e-4669-8e6e-488ade8cf345.png">
<img width="679" alt="Screenshot 2023-01-08 at 19 39 34" src="https://user-images.githubusercontent.com/118363955/211215593-2382485a-5b5b-476d-8e7e-3a5508a55689.png">

<img width="878" alt="Screenshot 2023-01-08 at 19 40 00" src="https://user-images.githubusercontent.com/118363955/211215597-f7bc4fa8-cdf4-4bb0-88f0-e4b89c93aaad.png">
<img width="860" alt="Screenshot 2023-01-08 at 19 40 13" src="https://user-images.githubusercontent.com/118363955/211215603-71c6e43c-aaa1-4426-8eaf-b8adbeaa8520.png">
<img width="873" alt="Screenshot 2023-01-08 at 19 40 25" src="https://user-images.githubusercontent.com/118363955/211215610-32e91a41-ba13-4625-bc2d-91d54bfb1209.png">

