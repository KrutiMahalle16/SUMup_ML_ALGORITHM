# SUMup_ML_ALGORITHM
Problem Statement: We aim to predict the forest cover type based on various geographical and
environmental features. Using a dataset containing measurements such as elevation, slope, distances
to hydrology, and other factors, we apply several classification algorithms including Decision Trees,
Random Forest, Logistic Regression, Naive Bayes, k-Nearest Neighbours, and K-Means to
determine which model best fits this classification task.
Dataset: The dataset includes the following features:
● Geographic features (Elevation, Aspect, Slope)
● Distance measurements (Horizontal and Vertical Distance to Hydrology, Horizontal Distance
to Roadways and Fire Points)
● Hillshade values (Hillshade_9am, Hillshade_Noon, Hillshade_3pm)

● The target variable is categorical: representing different forest cover types.
Methodology:
1. Data Preprocessing: The dataset is split into features (X) and the target (y). Missing values
are replaced, zeros in specific columns are replaced with the median, and the data is
standardized. The dataset is then divided into training (80%) and testing (20%) sets.
2. Feature Selection: Features like elevation, aspect, slope, distances, and hillshade values are
selected as inputs to the models.
3. Model Training and Evaluation:
○ Logistic Regression, Naive Bayes, k-NN: Applied as basic classification techniques.
○ Decision Tree: Trained to model and visualize the decision-making process.
○ Random Forest: An ensemble of decision trees used to improve model accuracy. ○
K-Means: Employed for clustering and adjusted for classification evaluation.
4. Evaluation Metrics: Model performance is evaluated using accuracy, confusion matrices,
classification reports, and adjusted Rand index for K-Means.
Selected Techniques:
● Logistic Regression (LR), Naive Bayes (NB), k-Nearest Neighbours (k-NN): Applied with
standard parameters for comparison.
● Decision Trees (DT): Used to understand feature importance.
● Random Forest (RF): Utilized with an ensemble approach to improve predictive
performance.
● K-Means Clustering: Applied to cluster the data, with labels adjusted to fit the classification
task.
Results:
● Logistic Regression Accuracy: Shows reasonable performance, with accuracy around 72% .
● Naive Bayes Accuracy: Performs similarly to Logistic Regression but may struggle with
feature independence assumptions.
● k-NN Accuracy: Achieves competitive results, with accuracy depending on the choice of k.
● Decision Tree Accuracy: Prone to overfitting, but provides insights into feature splits.
● Random Forest Accuracy: Delivers the best overall performance with an accuracy above
90%, leveraging ensemble learning.
● K-Means: Underperforms compared to supervised methods, as clustering does not directly
optimize for the target variable.
Model Accuracy Score

Model Accuracy Score:

Logistic Regression ~72%
Naive Bayes ~8%
k-Nearest Neighbours (k-NN) ~92%
Decision Tree ~93%
Random Forest ~95%


Conclusion: Random Forest offers the best predictive accuracy for classifying forest cover type,
benefiting from its ensemble approach. Decision Trees provide interpretability, while other classifiers
such as Logistic Regression, Naive Bayes, and k-NN yield competitive results. Clustering methods
like K-Means are less effective for this supervised task.
