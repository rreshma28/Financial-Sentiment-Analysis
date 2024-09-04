# Financial-Sentiment-Analysis:
### Objective:
To develop a robust model capable of accurately classifying financial news articles into positive, negative, or neutral sentiment categories.
To address the challenge of class imbalance in financial datasets, ensuring fair representation across all classes.

### Methodology:

##### Data Preprocessing:

Clean and preprocess the dataset, handling missing values, normalization, and stop word removal.
Explore data augmentation techniques to address potential limitations in dataset size.

Feature Engineering:
Create relevant features such as n-grams, TF-IDF, and sentiment lexicons to capture contextual information and sentiment cues.

Class Imbalance Handling:
Implement Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset, addressing the issue of class imbalance.

Model Selection and Training:
Choose a suitable machine learning algorithm (e.g., Logistic Regression) for sentiment classification.
Train the model on the balanced dataset, optimizing hyperparameters for best performance.

Evaluation:
Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
Analyze the model's ability to handle different sentiment classes, especially the minority classes.

##### Results:

The final model achieved an overall accuracy of 82%, with macro and weighted F1-scores of 0.77 and 0.82, respectively.
The use of SMOTE significantly improved the model's performance in handling underrepresented classes.
The model demonstrated strong generalization ability and can be applied effectively in real-world financial analysis scenarios.

#### Conclusion:
The combination of Logistic Regression and SMOTE proved to be a robust solution for financial sentiment analysis in imbalanced datasets. The model's strong performance metrics highlight its suitability for practical applications. Future work could explore incorporating additional features, experimenting with different models, and addressing potential limitations to further enhance the model's predictive power and applicability.
