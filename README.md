## Customer Churn Prediction with Machine Learning Models
### Overview 
This project focuses on predicting customer churn in a telecommunications company using various machine learning algorithms, including Logistic Regression, Decision Tree, Random Forest, and Hyperparameter Tuned Random Forest. Customer churn, or attrition, is a vital metric for businesses, representing the percentage of customers who discontinue their service within a given period. Accurately predicting churn allows companies to implement targeted retention strategies, reducing revenue loss and improving customer satisfaction.

### Key Components
#### 1. Data Analysis and Insights
Bivariate Analysis: 

Conducted a thorough analysis to understand the relationship between different customer attributes and churn rates. Insights from this analysis provided valuable guidance for subsequent modeling approaches.

Upselling Opportunity in West Virginia: 

Identified a specific opportunity in West Virginia where the customer retention rate is high despite low adoption of international and voicemail plans. This finding suggests a potential for upselling these services to the existing customer base, which could lead to increased revenue without a significant risk of churn.

Targeted Offers in Illinois: 

Discovered a regional preference for international calling services in Illinois. This insight guides the development of specialized international offers tailored to customers in this region, aiming to enhance customer satisfaction and loyalty.

Addressing Churn in New Jersey and Texas: 

Recognized high churn rates in states like New Jersey and Texas, signaling potential issues or competition in these markets. The identification of these challenges calls for targeted retention strategies such as personalized offers, loyalty programs, and improved customer service to reduce churn and increase customer retention.

Personalized Marketing through Phone Number Analysis: 

Leveraged the sparse distribution of phone numbers across states to enable highly personalized marketing efforts. By linking phone numbers to specific customer preferences, such as international or voicemail plans adoption, marketing teams can tailor their interactions to individual customer needs, thereby improving overall customer experience and satisfaction.


#### 2. Data Preprocessing
Handling Missing Values: Addressed missing or infinite values by replacing them with NaN and employing forward fill for NaN values.

Scaling Features: Standardized features using the StandardScaler to ensure compatibility with machine learning algorithms and improve model performance.

Splitting Data: Split the dataset into training and testing sets with an 80:20 ratio to train and evaluate the models effectively.

#### 3. Logistic Regression Model
Model Training and Evaluation: Initialized and trained a logistic regression model to predict churn, evaluating its performance on both training and testing sets.

Interpretation: Interpreted model coefficients and provided insights into the impact of each feature on churn prediction. Recommendations based on classification reports helped in understanding model strengths and weaknesses.

Visualization: Visualized model performance through ROC curves and confusion matrices to assess classification performance comprehensively.

#### 4. Decision Tree Model

Model Training and Evaluation: Trained a Decision Tree model to predict churn and evaluated its performance on both training and testing sets.

Interpretation: Analyzed the decision tree structure to understand the decision-making process and identified key predictors of churn.

#### 5. Random Forest Model
Model Training and Evaluation: Trained a Random Forest model and evaluated its performance on both training and testing sets.

Hyperparameter Tuning: Utilized RandomizedSearchCV for hyperparameter tuning to optimize the Random Forest model for better predictive accuracy.

Feature Importance Analysis: Investigated feature importance to identify significant predictors of churn, aiding in the development of targeted retention strategies.

#### 6. Hyperparameter Tuned Random Forest Model
Hyperparameter Tuning: Conducted hyperparameter tuning using RandomizedSearchCV to optimize the Random Forest model for improved performance.

Model Training and Evaluation: Trained the optimized Random Forest model and evaluated its performance on the testing set.

Feature Importance Analysis: Analyzed feature importance to gain insights into key drivers of churn predictions and provided recommendations based on the findings.

### Results
Strong Predictive Performance: Achieved robust predictive performance with all models, with ROC-AUC scores ranging from 0.85 to 0.93.

Key Feature Insights: Identified significant predictors of churn, providing actionable insights for targeted retention strategies.

Recommendations for Improvement: Provided recommendations for improving customer retention based on model insights and performance evaluation.

### Recommendations
Focus on Retention Strategies: Prioritize personalized retention efforts for customers at risk of churn based on model predictions.

Continuous Model Evaluation and Improvement: Regularly update and refine the models to adapt to changing business needs and customer behaviors.

Feature Importance Analysis: Utilize insights from feature importance analysis to tailor retention strategies and address underlying reasons for churn.

Enhance Customer Experience: Invest in initiatives to improve overall customer experience and reduce churn by addressing customer pain points.

Iterative Model Refinement: Experiment with different algorithms and techniques to continuously enhance model performance and adapt to evolving market dynamics.
