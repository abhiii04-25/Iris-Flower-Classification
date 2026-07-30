# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview
This project uses the famous Iris Flower Dataset to build a Machine Learning model that classifies iris flowers into three species:

- 🌸 Setosa
- 🌺 Versicolor
- 🌹 Virginica

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison of different classification algorithms.

## 🚀 Objectives
- Understand the Iris dataset
- Perform Exploratory Data Analysis (EDA)
- Preprocess the dataset
- Split data into training and testing sets
- Train multiple Machine Learning models
- Compare model performance
- Evaluate models using various metrics

## 📂 Dataset
The Iris dataset is available directly from Scikit-learn. It contains:

- 150 samples
- 4 features: Sepal Length, Sepal Width, Petal Length, Petal Width
- 3 classes: Setosa, Versicolor, Virginica

## 🛠 Technologies Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📚 Machine Learning Workflow
1. **Import Libraries** — Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
2. **Load Dataset** — import the Iris dataset and convert it into a Pandas DataFrame
3. **Data Exploration** — view the dataset, dataset info, statistical summary, missing value check
4. **Data Visualization** — pair plot, correlation heatmap, histograms, box plots
5. **Data Preprocessing** — feature selection, target selection
6. **Train-Test Split** — 80% training / 20% testing
7. **Model Training** — Logistic Regression, Decision Tree Classifier, Random Forest Classifier
8. **Model Evaluation** — accuracy score, confusion matrix, classification report
9. **Model Comparison** — compare all models and determine the best-performing classifier

## 📊 Project Structure
```
Iris-Flower-Classification/
│
├── data/
│   └── iris.csv
├── images/
│   ├── pairplot.png
│   ├── heatmap.png
│   ├── histogram.png
│   ├── boxplot.png
│   └── confusion_matrix.png
│
├── notebook.ipynb
├── train.py
├── requirements.txt
├── README.md
└── iris_model.pkl
```

## 📈 Sample Visualizations
Generated automatically in `images/` when you run `train.py` or the notebook:
- Pair Plot
- Correlation Heatmap
- Histogram
- Box Plot
- Confusion Matrix

## 📦 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

Go into the project directory:
```bash
cd Iris-Flower-Classification
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the project:
```bash
python train.py
```

## 📋 Requirements
```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

## 📊 Results
Running `train.py` trains three classifiers on an 80/20 stratified train-test split and reports accuracy, a classification report, and a confusion matrix for each. On this split:

| Model | Accuracy |
|---|---|
| Logistic Regression | ~0.97 |
| Decision Tree | ~0.93 |
| Random Forest | ~0.90 |

The best-performing model is automatically saved to `iris_model.pkl` using `joblib`. Since the Iris dataset is small (150 rows) and the split is randomized by a fixed seed, exact numbers may shift slightly with different `random_state` values — cross-validation is recommended for a more robust comparison (see Future Improvements).

## 🎯 Learning Outcomes
After completing this project, you will understand:
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Supervised Machine Learning
- Classification Algorithms
- Train-Test Split
- Model Evaluation
- Confusion Matrix
- Accuracy Score
- Machine Learning Workflow

## 🔮 Future Improvements
- Hyperparameter Tuning
- Cross Validation
- Feature Importance Analysis
- Model Deployment using Streamlit
- Flask/FastAPI Web Application

## 👨‍💻 Author
**Abhishek Sontakke**
MCA (Artificial Intelligence & Machine Learning)
Aspiring AI/ML Engineer | Data Science Enthusiast

⭐ If you found this project helpful, consider giving it a Star on GitHub!
