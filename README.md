🌍 Air Pollution Exposure and Respiratory Disease Correlation Analysis
📌 Project Overview

This project explores the relationship between air pollution exposure and respiratory disease risk using a large, realistic synthetic dataset. It simulates how environmental and socioeconomic factors influence respiratory health outcomes, making it ideal for demonstrating data science workflows in public health.

The analysis includes:

Data generation (synthetic but statistically meaningful)
Exploratory Data Analysis (EDA)
Correlation analysis
Predictive modeling (regression)
Visualization of insights
🎯 Objectives
Understand how air pollutants (PM2.5, PM10, NO₂, SO₂, O₃) impact respiratory health
Analyze the role of confounding variables like age, smoking, and income
Build a predictive model for respiratory disease risk
Demonstrate an end-to-end public health data science pipeline
📊 Dataset Description

The dataset contains 10,000 observations with the following features:

Feature	Description
age	Age of individual (5–85 years)
gender	Male / Female
smoker	Smoking status (0 = No, 1 = Yes)
pm25	Fine particulate matter concentration (µg/m³)
pm10	Coarse particulate matter concentration (µg/m³)
no2	Nitrogen dioxide levels
so2	Sulfur dioxide levels
o3	Ozone levels
income_level	Socioeconomic status (Low, Middle, High)
respiratory_risk	Continuous risk score (synthetic)
respiratory_disease	Binary outcome (0 = No, 1 = Yes)

⚠️ Note: This dataset is synthetic and created for educational and portfolio purposes only.

🛠️ Tools & Technologies
Python
Pandas & NumPy
Matplotlib & Seaborn
Scikit-learn
🔍 Methodology
1. Data Generation

A synthetic dataset was created using probabilistic distributions to simulate realistic environmental exposure and population characteristics.

2. Feature Engineering
Categorical variables encoded numerically
A respiratory risk score was constructed using weighted contributions from pollutants and lifestyle factors
3. Exploratory Data Analysis
Summary statistics
Correlation heatmaps
Distribution and relationship visualizations
4. Modeling
Linear Regression used to predict respiratory risk
Train-test split for evaluation
5. Evaluation Metrics
R² Score
Root Mean Squared Error (RMSE)
📈 Key Insights
Higher exposure to PM2.5 and NO₂ shows strong correlation with increased respiratory risk
Smoking status significantly amplifies health risk
Lower income levels are associated with higher vulnerability
Age contributes steadily to increased respiratory risk
🚀 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/air-pollution-analysis.git
cd air-pollution-analysis
Install dependencies:
pip install -r requirements.txt
Run the script:
python air_pollution_analysis.py
Output:
Visualizations
Model performance metrics
Generated dataset (.csv / .xlsx)
📂 Project Structure
├── data/
│   └── synthetic_air_pollution_health_data.xlsx
├── notebooks/
│   └── analysis.ipynb
├── src/
│   └── air_pollution_analysis.py
├── outputs/
│   └── figures/
├── README.md
└── requirements.txt
💡 Future Improvements
Add time-series analysis of pollution exposure
Incorporate geospatial mapping (city-level clustering)
Use advanced models (Random Forest, XGBoost)
Build an interactive dashboard (Streamlit / Power BI)
Integrate real-world datasets for validation
👤 Author

Joan Jushua

📜 License

This project is open-source and available under the MIT License.

🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork the repo and submit a pull request.
