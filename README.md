# CodeAlpha_Task
Exploratory Data Analysis (EDA) on the Iris dataset — CodeAlpha Internship Task 2
📘 Iris Dataset – Exploratory Data Analysis (EDA)
CodeAlpha Internship Task 2
📌 Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the classic Iris dataset, one of the most widely used datasets in machine learning.
The goal is to understand dataset structure, visualize feature relationships, explore correlations, and extract meaningful insights that support further modeling.

This project was completed as part of the CodeAlpha Data Analytics Internship.

📁 Project Structure
Iris_EDA_Project/
│
├── iris_eda.py               # Main Python script performing EDA
├── iris_dataset.csv          # Dataset used in the analysis
├── requirements.txt          # Dependencies required to run the script
├── README.md                 # Documentation
│
└── plots/                    # Auto-generated visualizations
    ├── hist_sepal_length_cm.png
    ├── hist_sepal_width_cm.png
    ├── scatter_sepal_len_width.png
    ├── correlation_matrix.png
    ├── boxplot_sepal_length_cm.png
    ├── boxplot_sepal_width_cm.png
    ├── boxplot_petal_length_cm.png
    ├── boxplot_petal_width_cm.png

🚀 How to Run This Project
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Iris_EDA_Project.git
cd Iris_EDA_Project

2️⃣ Create & Activate a Virtual Environment
✔ Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1


If blocked, run PowerShell as Administrator once:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

✔ macOS / Linux
python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the EDA Script
python iris_eda.py


All generated charts will appear inside the plots/ folder.

📊 Analysis Performed
✔ Dataset Exploration

Shape of dataset

Data types

First five rows preview

Missing values check

Summary statistics

✔ Visualizations

Histograms (Sepal Length, Sepal Width)

Scatter plot (Sepal Length vs Sepal Width)

Correlation heatmap

Boxplots for all four numerical features

🔍 Key Insights

The dataset contains no missing values.

Petal length and petal width show a strong positive correlation (~0.96).

Sepal width shows weak correlation with other features.

Iris Setosa is clearly distinguishable from other species.

Dataset is ideal for classification algorithms.

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

📚 About the Dataset

The Iris dataset includes 150 samples from 3 species:

Iris Setosa

Iris Versicolor

Iris Virginica

Each sample includes:

Sepal length

Sepal width

Petal length

Petal width

📝 License

This project is intended for educational & portfolio use.

🌐 Author

Gideon Kingsly Raj R
CodeAlpha Data Analytics Intern
GitHub: https://github.com/
<gideon-kingsly>
