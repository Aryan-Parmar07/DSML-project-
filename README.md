# Data Science & Machine Learning (DSML) Projects

Repository containing hands-on practical notebooks, datasets, and projects following the Data Science and Machine Learning curriculum.

---

## 🗂️ Repository Structure

```
dsml-project/
├── Module1/                                    # Python & Exploratory Data Analysis
│   ├── datasets/
│   │   ├── customer_seg.csv                    # Customer segmentation dataset
│   │   ├── salary_dataset.csv                  # Years of experience vs salary
│   │   └── zomato_eda_mini_project.csv         # Restaurant dining & rating data
│   ├── project-notebooks/
│   │   ├── Pandas.ipynb                        # Pandas data wrangling & operations
│   │   ├── EDAMatSea.ipynb                     # Data visualization with Matplotlib & Seaborn
│   │   └── ZomatoBasedMiniProject.ipynb        # Comprehensive Zomato EDA mini-project
│   └── README.md
│
├── Module2Statistics/                          # Probability & Applied Statistics
│   ├── project-notebooks/
│   │   ├── Descriptive_Statistics_Hands_On_Colab.ipynb  # Central tendency, variance, skewness
│   │   ├── Sampling_and_Central_Limit_Theorem.ipynb     # Sampling methods & CLT simulation
│   │   └── Statistics_Mini_project_salesData.ipynb      # Sales data statistical analysis
│   └── README.md
│
├── Module3/                                    # Machine Learning Algorithms
│   ├── project-notebooks/
│   │   ├── Linear_Regression_Student_Marks.ipynb        # Linear regression model
│   │   └── Logistic_Regression_Student_Pass_Fail.ipynb  # Logistic regression classifier
│   └── README.md
│
└── .gitignore                                  # Git ignore rules for Python & Jupyter
```

---

## 📚 Curriculum Breakdown

### 🔹 [Module 1: Data Science & Exploratory Data Analysis](Module1/)
Covers data cleaning, manipulation, and visual storytelling using modern Python data science libraries.
- **Topics**: DataFrames, filtering, aggregation, distributions, correlations, outliers.
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`

### 🔹 [Module 2: Statistics for Data Science](Module2Statistics/)
Focuses on both descriptive and inferential statistics to build statistical intuition for machine learning.
- **Topics**: Mean, median, mode, IQR, standard deviation, probability distributions, sampling techniques, Central Limit Theorem (CLT).
- **Libraries**: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`

### 🔹 [Module 3: Machine Learning Fundamentals](Module3/)
Introduces supervised machine learning algorithms, model training, evaluation, and inference.
- **Topics**: Simple Linear Regression (continuous target prediction), Logistic Regression (binary classification).
- **Libraries**: `scikit-learn`, `pandas`, `matplotlib`

---

## 🚀 Getting Started

### Option 1: Running in Google Colab (Recommended)
1. Navigate to the module and notebook you want to run.
2. Download the `.ipynb` file (and any accompanying `.csv` from `Module1/datasets/` if required).
3. Open [Google Colab](https://colab.research.google.com/) and click **Upload Notebook**.
4. If the notebook requires a dataset, upload the CSV into the Colab session storage panel on the left.

### Option 2: Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Aryan-Parmar07/dsml-project.git
   cd dsml-project
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   # Windows:
   .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy scipy matplotlib seaborn scikit-learn jupyter
   ```
4. Start Jupyter Notebook or JupyterLab:
   ```bash
   jupyter lab
   ```

---

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Statistical Computing**: SciPy, NumPy
- **Machine Learning**: Scikit-Learn
- **Environment**: Jupyter Notebooks / Google Colab

---

## 📄 Attribution

Course materials and curriculum structure adapted from the [ML-DataScience-Training](https://github.com/Mohmadasif/ML-DataScience-Training) program.
