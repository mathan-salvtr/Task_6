K-Nearest Neighbors (KNN) Classification on Iris Dataset
📌 Objective
Implement the K-Nearest Neighbors (KNN) algorithm for a classification problem using the Iris dataset, exploring the effect of different K values, and visualizing results including decision boundaries.

📂 Dataset
Source: Iris Dataset - UCI Machine Learning Repository

Description:
The dataset contains 150 observations of iris flowers, each described by:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Species (Setosa, Versicolor, Virginica)

🛠 Tools & Libraries
Python 3.x

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📊 Steps Implemented
Load & Explore Data

Read dataset from CSV.

Dropped unnecessary ID column.

Preprocessing

Feature scaling using StandardScaler.

Train-test split (80% train, 20% test).

Model Training

Used KNeighborsClassifier from scikit-learn.

Tried K values from 1 to 10.

Evaluation

Selected best K based on accuracy.

Generated confusion matrix.

Visualization

Accuracy vs K plot.

Confusion matrix heatmap.

Decision boundary plot (first two features).

📈 Results
Best K: Varies by run due to random split (commonly 3, 5, or 7).

Accuracy: ~0.96 - 1.0 (depending on split).

Visualizations:

Accuracy vs K

Confusion Matrix

Decision Boundary for first two features
