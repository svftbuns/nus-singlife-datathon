# NUS-SDS-Datathon-Singlife

Singlife has observed a concerning trend in the customer journey: potential policyholders are expressing hesitation and eventual disengagement during the insurance acquisition process. To address this, Singlife seeks to leverage its dataset. The objective is to derive actionable insights from this data to enhance the customer experience. The challenge is to dissect the dataset to uncover the critical touchpoints that conss and personalise communication. The ultimate goal is to predict customer satisfaction contribute to customer drop-off and identify opportunities to streamline the application proceand conversion rates, thereby bolstering Singlife's market position.

## Methods used

### Data Processing
- Data Imputation
  - Interpolation
  - KNN Imputation
- Data Balancing
  - SMOTE
- Data Encoding
  - One-Hot Encoding

### Exploratory Data Analysis
- Feature Selection
  - Fisher Score
  - Decision Tree

### Machine Learning
  - Decision Tree Classifier
  - K-Nearest Neighbours
  - XGBoost

## Conclusion
Our analysis has shown that XGB model performed the best in terms of accuracy. This is mainly because XGBoost is an ensemble learning algorithm that combines the predictions of multiple weak learners, usually decision trees. Decision trees are capable of capturing complex relationships within the data, allowing the model to learn intricate patterns.

## Takeaways
1. Techniques to handle imbalance dataset with many missing values.
2. Feature Selection to select essential factors from dataset with vast number of columns.

## Future Improvements
1. Incorporate Deep Learning Models such as Pytorch and Keras to boost accuracy
2. Apply advanced Data Imputation techniques such as Iterative Imputer and matrix factorization
3. Utilize techniques like binning, discretization, or polynomial features to enhance the model's ability to capture patterns.
4. Employ dimensionality reduction techniques like Principal Component Analysis (PCA) or t-Distributed Stochastic Neighbor Embedding (t-SNE) to reduce the number of features and facilitate better model training.

## Contributors
| Name             | Github Account                                          |
|------------------|---------------------------------------------------------|
| Vivian Kho       | [@svftbuns](https://github.com/svftbuns)                |
| Chen Ziyi        | [@zi-yii](http://github.com/zi-yii)                     |
| Rachel           | [@racxxhel](http://github.com/racxxhel)                 |
