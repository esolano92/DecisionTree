# 🌸 Iris Classification with Decision Tree

This project demonstrates the use of a Decision Tree Classifier to predict the species of the Iris flower based on its physical characteristics. The model is trained and evaluated on the classic Iris dataset using hyperparameter tuning, validation, and visualization.

---

## 📊 Dataset

The [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) is a well-known multi-class classification dataset consisting of 150 samples with 4 features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each sample is labeled as one of three species:
- *Setosa*
- *Versicolor*
- *Virginica*

---

## 🧠 Model

The model used is a `DecisionTreeClassifier` from `scikit-learn`. Two hyperparameters were tuned:
- `max_depth`
- `min_samples_split`

Hyperparameter tuning was done using validation accuracy, and performance was visualized with plots.

---

## 🧪 Workflow

1. Load and split data into **train**, **validation**, and **test** sets
2. Tune `max_depth` and `min_samples_split` on the validation set
3. Train final model on **train + validation**
4. Evaluate final model on **test** set
5. Visualize the tree structure and interpret model behavior
6. Add predictions to the dataset for inspection

---

## 📈 Results

- **Best Parameters**: `max_depth=3`, `min_samples_split=2` *(example values)*
- **Test Accuracy**: ~96% *(varies depending on data split)*
- **Perfect classification** of *Setosa*
- Minor confusion between *Virginica* and *Versicolor*

A classification report, tree visual, and tesing-dataframe are included in the notebook for evaluation.

---




