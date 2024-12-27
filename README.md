Name: Prabhat Kumar

Company: Prodigy InfoTech

CIN: PIT/DEC24/02757

Domain: DATA SCIENCE

Duration: 1st December2024 to 31st December2024

Project Overview: Predicting Customer Purchases Using a Decision Tree Classifier

This project explores the use of machine learning, specifically a Decision Tree Classifier, to predict whether a customer will purchase a product or service based on historical, demographic, and behavioral data from the Bank Marketing Dataset. The ultimate goal is to derive actionable insights that can improve the efficiency and targeting of marketing campaigns, thereby increasing the likelihood of customer engagement.

Detailed Steps:

1. Dataset Overview and Problem Understanding
The dataset includes information on over 40,000 marketing efforts, each detailing customer attributes and the outcome of the marketing campaigns. The key objective is to classify whether a customer will subscribe to a term deposit (subscribed_deposit: yes/no).

Data Attributes:
Customer Demographics: Age, job, marital status, education, etc.
Behavioral Data: Previous campaign outcomes, call durations, and contact counts.
Economic Indicators: Employment variation rates, consumer price index, consumer confidence index, etc.
Target Variable: Whether the customer subscribed to the deposit (yes or no).
This diverse set of features makes it possible to capture complex patterns that influence customer decisions.

2. Data Cleaning and Preparation
A thorough cleaning process ensured the dataset was ready for analysis:

Duplicate Records: Identified and removed duplicates to prevent biased model training.
Handling Outliers: Applied the IQR method to remove extreme values from critical numerical columns like age, campaign, and duration.
Irrelevant Feature Removal: Dropped highly correlated features such as emp.var.rate and euribor3m, which could introduce noise or redundancy in the model.
Label Encoding: Transformed categorical variables (e.g., job, marital, poutcome) into numeric values using Label Encoding for machine learning compatibility.
3. Exploratory Data Analysis (EDA)
EDA was performed to uncover trends and relationships within the data:

Feature Distributions: Histograms for numerical variables revealed patterns such as age distribution and duration spread.
Category Analysis: Count plots of categorical variables like job, education, and poutcome highlighted class imbalances and customer characteristics.
Correlation Heatmap: Analyzed relationships among numerical variables to identify potential multicollinearity issues and significant predictors for the target variable.
Box Plots: Visualized the impact of features like balance and duration on the target variable to highlight critical trends.
4. Model Implementation
A Decision Tree Classifier was built using the cleaned and preprocessed dataset:

Model Configuration:

Criterion: Both Gini Index and Entropy were used to compare impurity measures.
Tree Depth: Limited to prevent overfitting while maintaining adequate model complexity.
Min Samples Split: Controlled how the tree split further to balance accuracy and generalizability.
Training: The model was trained using a split dataset (70% training, 30% testing) to ensure robust evaluation.
Key Features: Variables like duration (call duration), previous (number of prior contacts), and poutcome (outcome of the previous campaign) were observed to heavily influence the predictions.
5. Model Evaluation and Performance
The Decision Tree model was rigorously tested to evaluate its effectiveness:

Performance Metrics:
Accuracy Score: Measured the overall correctness of predictions, showing the model’s effectiveness in distinguishing between subscribed and non-subscribed customers.
Confusion Matrix: Evaluated how well the model balanced between false positives and false negatives.
Precision, Recall, and F1-Score: Provided a deeper understanding of model performance on each class (yes and no).
Results:
Training accuracy: ~90%
Testing accuracy: ~85-87% (showing minimal overfitting).
High recall for the yes class, ensuring fewer missed predictions of potential subscribers.
6. Decision Tree Visualization
The decision tree was visualized, offering interpretable insights into the decision-making process:

Structure: The tree structure provided clear, actionable rules, such as:
If duration > X and poutcome is success, predict yes.
If duration <= Y and campaign > Z, predict no.
Feature Importance: Highlighted how features contributed to predictions, enabling the bank to prioritize key influencing factors in their marketing strategy.
7. Advanced Insights
Targeting Strategies:
Focus on customers with a history of successful interactions (positive poutcome values).
Increase engagement with customers contacted for longer durations (duration > threshold).
Improve campaigns by avoiding over-contacting (campaign feature).
Feature Impact: Economic indicators like euribor3m and emp.var.rate were less relevant, justifying their exclusion in the final model.
Class Imbalance Handling: The dataset's natural imbalance was tackled during evaluation, ensuring fair performance metrics.
Conclusion and Business Implications
The Decision Tree Classifier proved to be an effective tool for predicting customer behavior:

Business Value:
Improved targeting of marketing efforts, saving resources by focusing on high-potential leads.
Enhanced understanding of customer preferences and behavior patterns.
Insights into campaign success factors, allowing for iterative improvements.
Next Steps:
Experiment with ensemble models (Random Forest, Gradient Boosting) to further boost performance.
Use advanced techniques like SMOTE to address class imbalance.
Deploy the model in real-world scenarios for live campaign targeting.
This project underscores the power of machine learning in data-driven decision-making and its ability to transform marketing strategies into efficient, customer-centric processes.

![image](https://github.com/user-attachments/assets/d62035d2-d692-426a-a6f9-b9f30ce3700b)
![image](https://github.com/user-attachments/assets/1961e3fb-0351-4ae8-b09f-11c745af556b)
![image](https://github.com/user-attachments/assets/739a2e3a-b72d-4a2f-977e-df9e6372c20f)
![image](https://github.com/user-attachments/assets/383463e6-e565-4410-aac1-78e2e2e69dba)
![image](https://github.com/user-attachments/assets/1b9bec78-f2f1-4aa4-b5b0-58ff5cc4664b)
![image](https://github.com/user-attachments/assets/4e00d486-7a89-4f1c-bc23-38179ac281a2)
![image](https://github.com/user-attachments/assets/b684ca7b-5948-4d87-bd24-5836ce4a3344)
![image](https://github.com/user-attachments/assets/6e100cb4-a9b9-4ce6-a6e6-976c31e569fd)
![image](https://github.com/user-attachments/assets/37172f3c-ebe2-464b-9ec0-0d5691258948)
![image](https://github.com/user-attachments/assets/30b4a0b6-5d08-431d-966d-3f82904c728a)
![image](https://github.com/user-attachments/assets/abc18975-272b-4592-8a03-0cf78d447cd4)
![image](https://github.com/user-attachments/assets/02902964-abc0-43a7-831c-63e8284f6868)
![image](https://github.com/user-attachments/assets/c9424fef-6e25-42ee-8daf-3092c6ff0c1d)
![image](https://github.com/user-attachments/assets/a836b9b9-88fd-40d9-a673-f95a7e844108)
![image](https://github.com/user-attachments/assets/541e2266-7fee-42b5-85e4-d14f889dea38)
![image](https://github.com/user-attachments/assets/2c4ae35b-85da-4cbc-82f6-08ada8f200a8)
![image](https://github.com/user-attachments/assets/4287ca1e-8a79-44d2-ab02-b2e9afe1735e)
![image](https://github.com/user-attachments/assets/d07c83d2-33ab-4922-8952-1e7b46f0b0a3)
![image](https://github.com/user-attachments/assets/b2c7c46c-7050-4147-bd9c-9018e318ca24)
![image](https://github.com/user-attachments/assets/9c2c8539-b63f-4de2-bfff-82efa2c9ee0b)
![image](https://github.com/user-attachments/assets/9987cdfe-c2aa-44c4-ab2f-ef0ae5a825a6)
![image](https://github.com/user-attachments/assets/699a4625-f995-4f3b-857f-7e4e4d46af13)
![image](https://github.com/user-attachments/assets/5de30c84-8b3b-4aa3-9a87-dd597b2c4696)
![image](https://github.com/user-attachments/assets/99fd9d1a-bb11-4d0c-ab83-eb920a133f8a)
![image](https://github.com/user-attachments/assets/8585c79d-22b5-4bce-9b29-06d6d184bafc)
![image](https://github.com/user-attachments/assets/045b4668-87fe-472d-abc5-f269c6b22356)



























