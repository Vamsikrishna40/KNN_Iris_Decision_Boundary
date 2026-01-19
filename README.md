# K-Nearest Neighbors (KNN) Classification on Iris Dataset

## 📌 Overview

This project demonstrates the implementation and analysis of the **K-Nearest Neighbors (KNN)** classification algorithm using the classic **Iris dataset**.  
The objective of this assignment is to understand how the KNN algorithm works, how the choice of the parameter *k* affects model performance, and how different distance metrics influence the classification results.

The notebook includes data loading, preprocessing, model training, evaluation, hyperparameter analysis, and visualization of decision boundaries.

---

## 📂 Project Structure


---

## 📊 Dataset Information

- **Dataset Name:** Iris Dataset  
- **Source:** Scikit-learn built-in dataset  
- **Number of Samples:** 150  
- **Number of Features:** 4  

### Features

1. Sepal Length  
2. Sepal Width  
3. Petal Length  
4. Petal Width  

### Classes

- Setosa  
- Versicolor  
- Virginica  

---

## ⚙️ Requirements

The following Python libraries are required to run this project:

```bash
pip install numpy pandas matplotlib scikit-learn

## ⚙️ Libraries Used

The following Python libraries were used in this project:

- **numpy** – for numerical computations and array operations  
- **pandas** – for data handling and analysis  
- **matplotlib** – for data visualization and plotting graphs  
- **scikit-learn** – for machine learning models, datasets, and evaluation metrics  

---

## 🧪 Tasks Performed

The notebook is organized into the following tasks:

### Task 1: Load and Explore the Dataset
- Load the Iris dataset from scikit-learn  
- Display feature names and target labels  
- Inspect the shape and sample records of the dataset  

### Task 2: Train-Test Split
- Split the dataset into training and testing sets  
- Prepare input features and target labels  

### Task 3: Train a Basic KNN Model
- Train a KNN classifier with **k = 3**  
- Predict class labels for the test set  
- Calculate and display the model accuracy  

### Task 4: Predictions for Different Values of k
- Train KNN models with multiple values of *k*  
- Compare predictions and accuracy for each *k*  

### Task 5: Model Evaluation
- Generate confusion matrix  
- Display classification report  
- Analyze precision, recall, and F1-score  

### Task 6: Performance Visualization
- Plot accuracy versus number of neighbors (*k*)  
- Visualize training data distribution  

### Task 7: Effect of Distance Metric
- Fix **k = 5**  
- Compare Euclidean and Manhattan distance metrics  
- Plot and analyze decision boundaries  

### Task 8: Observations
- Study how predictions change as *k* increases  
- Identify the most complex decision boundary  
- Analyze overfitting and underfitting  
- Compare the effect of different distance metrics  
- Recommend the best configuration  

---
## 📈 Visualizations

The following visualizations are included in this project:

- Accuracy vs Number of Neighbors (*k*) plot to analyze the effect of *k* on model performance  
- Scatter plots of the training data for understanding class distribution  
- Decision boundary plots for:
  - Euclidean distance  
  - Manhattan distance  

These visualizations help in understanding how the KNN model behaves with different hyperparameters and distance metrics.

---

## 🧠 Key Learnings

Through this assignment, the following key concepts were learned:

- Small values of *k* (such as **k = 1**) produce highly complex decision boundaries and can lead to overfitting.  
- Larger values of *k* result in smoother decision boundaries but may cause underfitting.  
- The choice of distance metric affects how neighbors are selected and slightly changes classification results.  
- There is a trade-off between model complexity and generalization in KNN.  
- Proper selection of *k* and distance metric improves model performance.

---

## ✅ Final Recommendation

For the Iris dataset, the recommended configuration is:

- **Number of Neighbors:** `k = 5`  
- **Distance Metric:** `euclidean`  

This configuration provides a good balance between bias and variance, avoids overfitting, and gives stable and reliable classification accuracy.

---

## 🧑‍🎓 Author Information

- **Name:** Vamsi Krishna  
- **Course/Subject:** Machine Learning / Data Mining  
- **Topic:** K-Nearest Neighbors Classification  
- **Institution:** _(Innomatics Reserach Labs)_  

---

## 📜 License

This project is created for **educational and academic purposes only**.  
It may be used, modified, and shared for learning and non-commercial use.

---

## 📎 References

- Scikit-learn Documentation: https://scikit-learn.org  
- Iris Dataset (UCI Machine Learning Repository): https://archive.ics.uci.edu/ml/datasets/iris  
- KNN Algorithm Overview: https://en.wikipedia.org/wiki/K-nearest_neighbors  

---

