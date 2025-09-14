# 📘 CodeSoft Internship Tasks – Machine Learning Projects

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Visualization](https://img.shields.io/badge/Visualization-Seaborn%20%7C%20Matplotlib-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

This repository contains the **tasks completed during my CodeSoft Internship**.
Each task demonstrates the application of **Machine Learning algorithms** for real-world problem solving, including **classification** and **regression**.

---

## 📂 Projects Included

### 1️⃣ Iris Flower Classification

* **Goal**: Classify iris flowers into species (`Setosa`, `Versicolor`, `Virginica`) based on sepal and petal measurements.
* **Dataset**: `IRIS.csv`
* **Algorithm**: Random Forest Classifier
* **Highlights**:

  * Data exploration & visualization (scatterplots, histograms, pair plots).
  * Built a Random Forest Classifier with high accuracy.
  * **Result**: \~97% test accuracy.

---

### 2️⃣ Movie Rating Prediction

* **Goal**: Predict IMDB movie ratings using movie attributes like genre, director, and actors.
* **Dataset**: `IMdb_movie.csv`
* **Algorithm**: Linear Regression
* **Highlights**:

  * Handled missing values in `Rating` and `Duration`.
  * Encoded categorical variables using one-hot encoding.
  * Visualized top directors, actors, and genres.
  * **Result**: Successfully predicted ratings with regression model.

---

### 3️⃣ Titanic Survival Prediction

* **Goal**: Predict whether a passenger survived the Titanic disaster.
* **Dataset**: `tested.csv`
* **Algorithm**: K-Nearest Neighbors (KNN) Classifier
* **Highlights**:

  * Filled missing values (`Age`, `Fare`) and dropped irrelevant features (`Name`, `Cabin`, etc.).
  * Analyzed survival by class, gender, and age using visualizations.
  * **Result**: \~78–80% accuracy with KNN model.

---

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries Used**:

  * `pandas`, `numpy` → Data manipulation
  * `matplotlib`, `seaborn` → Data visualization
  * `scikit-learn` → Machine learning models & evaluation

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/codesoft-internship-tasks.git
   cd codesoft-internship-tasks
   ```

2. **Install dependencies:**

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run any project file:**

   ```bash
   python "Iris flower Classification.py"
   python "Movie rating Prediction.py"
   python "Titanic Survival Prediction.py"
   ```

---

## 📖 Learning Outcomes

* Data preprocessing & feature engineering
* Exploratory data analysis (EDA)
* Supervised ML algorithms (classification & regression)
* Model evaluation & accuracy measurement
* Hands-on experience with real datasets

---

## 🙌 Acknowledgements

This repository was developed as part of the **CodeSoft Internship Program** to practice and implement core machine learning concepts on real-world datasets.

---

## 📌 Note

All scripts are **independent** – you can directly run any file after installing dependencies.
Modify datasets or parameters to experiment further and improve results.
