# Restaurant-Rating-Prediction

A beginner-friendly Machine Learning project that predicts restaurant ratings using the Zomato restaurant dataset. This project demonstrates the end-to-end regression workflow, from data exploration and preprocessing to model training and evaluation.

## 🎯 Project Objectives

- Explore and understand restaurant data.
- Clean and preprocess data for Machine Learning.
- Build a regression model to predict restaurant ratings.
- Compare Random Forest Regression with a baseline model.
- Evaluate model performance using MAE, RMSE, and R².

## 📊 Dataset

**Dataset:** Zomato Restaurant Dataset

The dataset contains restaurant information, including:

- Restaurant city and cuisines
- Price range
- Number of votes
- Latitude and longitude
- Online delivery availability
- Table booking availability
- Aggregate restaurant rating

**Target variable:** `Aggregate rating`

## 🛠️ Tech Stack

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## ⚙️ Project Workflow

1. Import Python libraries.
2. Load and inspect the dataset.
3. Explore missing values and duplicate records.
4. Visualize the distribution of restaurant ratings.
5. Prepare features and target variables.
6. Split the dataset into training and testing sets.
7. Preprocess numerical and categorical features.
8. Train a Random Forest Regression model.
9. Evaluate predictions using regression metrics.
10. Test the model with example restaurant data.

## 🤖 Machine Learning Model

This project uses **Random Forest Regression** to estimate restaurant ratings based on restaurant characteristics.

A baseline model that predicts the mean training rating is also used for comparison.

### Evaluation Metrics

| Metric | Description |
|---|---|
| MAE | Measures average absolute prediction error |
| RMSE | Penalizes larger prediction errors |
| R² Score | Measures model performance relative to a mean-based baseline |

Actual evaluation scores will be reported after running the notebook.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

### 2. Install dependencies

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Prepare the files

Place these files in the same folder:

```text
project/
├── Zomato_Restaurant_Rating_Prediction.ipynb
├── Zomato Restaurant Dataset.csv
└── README.md
```

### 4. Run the notebook

Open `Zomato_Restaurant_Rating_Prediction.ipynb` in VS Code, select your Python kernel, and execute the cells from top to bottom.

## 🔍 Future Improvements

- Compare Random Forest with Linear Regression and XGBoost.
- Apply cross-validation and hyperparameter tuning.
- Analyze prediction errors across cities and price ranges.
- Build an interactive prediction application using Streamlit.
- Deploy the model through a FastAPI endpoint.

## 📚 Learning Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)

## 👨‍💻 Author

**Your Name**

Replace this section with your name and GitHub profile.

---

*This project is intended for educational purposes and Machine Learning practice.*

