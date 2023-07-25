# csci-316

Big Data Mining Techniques and Implementation

# Assignment 1

#### Requirements

1. This is a classification problem.
2. Use 80% data for training and 20% for testing. Stratified sampling must be used.
3. Main steps of the project should be (a) “discover and visualise the data”, (b) “prepare the data for
   machine learning algorithms”, (c) “select and train models”, (d) “fine-tune the model” and (e)
   “evaluate the outcomes”. You can structure the project in your own way. Some steps can be performed
   more than once. </br>
   a. Load data, data.info(), data.shape(), data.head(), visualise data possibly with seaborn </br>
   b. Pre-processing, clean data, decide on which outliers to remove, prepare data for machine learning algo (this is where 80% and 20% happens.)

   - Feature selection, feature engineering, feature scaling, etc.

   c. <strong>Training models/ ML Algorithms:</strong> Decision Tree Model, <!--Linear Regression, Support Vector Regression, -->
   Random Forest,

4. In the steps (c) and (d) above, you must work with at least three machine learning algorithms.
5. In step (b), define at least one new feature by using the User-Defined Transformer. This transformer includes a parameter indicating whether use the new feature(s) or not. In step (d), fine-tuning step must use this parameter (as a hyper parameter). (We will ask lecturer.)
6. Explanation of each step together with the Python codes must be included.
7. A comparison of the models’ performance must be included.
