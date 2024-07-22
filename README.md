# Predictive Analytics for Financial Services

## ABSTRACT
The recent expansion of the credit industry has made credit scoring a crucial problem, prompting banks to handle vast amounts of credit data. Various data mining techniques have been suggested to address credit scoring, each with its own strengths and weaknesses. However, there is no comprehensive reference outlining the most popular data mining techniques for credit scoring issues. This project aims to develop a model for classifying bank customers as "good" or "bad" based on their credit scores and other relevant details. The dataset contains information on customers' credit scores, income, debt-to-income ratio, employment status, and other factors affecting their creditworthiness. The project involves data preprocessing, feature selection and engineering, and training several machine learning models, including Dummy Classifier, KNN, Decision Trees, SVC, and Random Forests. The models' performance is evaluated using accuracy, precision, recall, and F1-score metrics. The results can help banks improve their risk assessment processes, identify potential defaulters, and make more informed lending decisions.

Index Terms: Classification, data mining techniques, predictive analytics, credit scoring

## INTRODUCTION
Credit risk assessment is essential for banks to make informed lending decisions and minimize losses. With the credit industry's expansion, banks deal with large volumes of data that cannot be analyzed manually. Data mining methods offer an effective solution for credit scoring issues, but a comprehensive reference of popular techniques is still needed. Accurate credit risk assessment helps banks identify potential defaulters and utilize resources better. This project aims to classify bank customers as "good" or "bad" based on credit scores and other relevant details using various machine learning models. The dataset includes customer credit scores, income, debt-to-income ratio, employment status, and more. Data preprocessing includes handling missing values, encoding categorical variables, and scaling numerical features. Feature selection and engineering identify relevant features and transform them for better model performance. Models are trained and evaluated using accuracy, precision, recall, and F1-score metrics to find the best model for credit risk assessment.

## RELATED WORK
1. **Broby (2022)** discussed predictive analytics in finance, particularly in credit risk assessment, highlighting the importance of accurate credit risk assessment for informed lending decisions and loss minimization. Various data mining techniques and the importance of feature selection and engineering were also discussed.
2. **A Proposed Classification of Data Mining Techniques in Credit Scoring** categorized data mining techniques into statistical and machine learning methods, discussing their advantages and limitations and emphasizing feature selection and engineering's importance.
3. **Indriasari et al. (2019)** provided insights into machine learning techniques for credit risk assessment in banking, emphasizing feature selection and engineering and the importance of evaluating model performance using appropriate metrics.
## DATA
The dataset is the “German credit risk data” available in the Kaggle repository, consisting of 9 attributes and 1000 instances, with each entry representing a person taking credit from a bank. Each person is classified as a good or bad credit risk based on the attributes.

## METHODS
Data preprocessing includes one-hot encoding and SMOTE for handling imbalanced data. Various classification models such as Random Forest, KNN, SVM, and Decision Trees were tried and tested.

## EXPERIMENTS AND RESULTS
The dataset was preprocessed and split into training and testing sets (70% training, 30% testing). Standard scaling was applied to both original and SMOTE data. A dummy classifier was used to create a baseline, and GridSearchCV was used to tune hyperparameters for each model. Models were evaluated using accuracy, precision, recall, and F1-score. Random Forest performed the best with an accuracy score of 0.72. The SMOTE data showed lower performance due to noisy samples.

## CONCLUSION
Random Forest is the best model for predicting customer creditworthiness based on accuracy scores. SMOTE did not perform well due to potential noise. Future work includes testing other classification models like AdaBoost, Gradient Boost, and XGBoost to improve prediction accuracy.

## REFERENCES
1. Broby, D. (2022). The use of predictive analytics in Finance. The Journal of Finance and Data Science, 8, 145-161. Link
2. A proposed classification of data mining techniques in credit scoring. Retrieved April 1, 2023, from ResearchGate
3. Indriasari, E., Soeparno, H., Gaol, F. L., & Matsuo, T. (2019). Application of Predictive Analytics at Financial Institutions: A Systematic Literature Review. 2019 8th International Congress on Advanced Applied Informatics (IIAI-AAI), Toyama, Japan, pp. 877-883. doi: 10.1109/IIAI-AAI.2019.00178
