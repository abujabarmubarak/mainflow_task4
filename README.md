House Price Prediction - Regression Analysis

Project Description

This project involves building a Linear Regression Model to predict house prices based on key features such as:

Size (in square feet)

Number of Rooms

Location (Urban, Suburban, Rural)

The dataset is processed, analyzed, and used to train a model that predicts house prices with high accuracy.

Features & Methodology

1️⃣ Data Preprocessing

Handling missing values using median imputation.

Scaling numerical features using StandardScaler.

Encoding categorical variables using One-Hot Encoding.

2️⃣ Exploratory Data Analysis (EDA)

Checking the distribution of features.

Identifying outliers and correlations between variables.

Visualizing data with heatmaps, scatter plots, and histograms.

3️⃣ Model Development

Splitting data into Training (80%) and Testing (20%).

Training a Linear Regression Model using scikit-learn.

4️⃣ Model Evaluation

Root Mean Square Error (RMSE) to measure prediction accuracy.

R² Score to determine how well the model explains price variation.

📂 Dataset

The dataset (house_prices.csv) contains:

Size (sq ft)

Number of Rooms

Location

Price ($)

1200

3

Urban

120000

2500

4

Suburban

180000

1800

3

Rural

100000

...

...

...

...

📌 How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the Python script:

python regression_model.py

🛠 Technologies Used

Python (pandas, numpy, scikit-learn, matplotlib, seaborn)

Machine Learning (Linear Regression)

📢 Results & Insights

✅ Size & Number of Rooms strongly influence house prices.
✅ Urban locations tend to have higher prices than rural areas.
✅ The model achieves a high R² score, meaning it's a good predictor of house prices.

📜 License

This project is open-source under the MIT License.

