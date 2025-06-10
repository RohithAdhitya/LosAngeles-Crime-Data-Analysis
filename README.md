# 🚔 Crime Data Analysis – Los Angeles (2020–2023)

## 📄 Overview
This project analyzes crime data from the City of Los Angeles spanning January 2020 to October 2023. By leveraging data cleaning techniques, exploratory data analysis, and time-series forecasting, the project uncovers patterns in criminal activity to support public safety initiatives and urban decision-making.

---

## 🎯 Objectives
- Preprocess and clean large-scale public crime data
- Discover seasonal, geographic, and demographic trends
- Analyze the impact of major events (e.g., policy changes, economic shifts)
- Predict future crime trends using ARIMA time-series forecasting

---

## 🧰 Tech Stack
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels
- **ML/Stats**: ARIMA (AutoRegressive Integrated Moving Average)
- **Tools**: Jupyter Notebook

---

## 📊 Key Insights
- 📈 Crime peaked in **2022**, with a gradual decline in 2023
- 🚗 The most common crime type: **Vehicle Theft**
- 🗓️ **Fridays** had the highest crime frequency; **Tuesdays** had the lowest
- 🏙️ The **Central region** reported the highest incidents; **Foothill** the fewest
- 🧑‍🤝‍🧑 Crime trends varied by **gender** and **age group**
- 📉 The **economic recession** period in 2020 correlated with a spike in crime

---

## 🔮 Forecasting
Using ARIMA (order = (1,1,1)), we forecasted crime counts for the next 365 days. The model revealed expected declines aligned with recent trends, though further model tuning is suggested for higher accuracy.

---

## 📂 Project Structure
## 🧼 Cleaning Highlights
- Handled missing values across categorical and numeric fields
- Converted dates/times to proper datetime formats
- Removed outliers using Z-score
- Performed encoding (initially attempted, later excluded for interpretability)

---

## 📈 EDA & Visuals
- Monthly and yearly crime trends
- Seasonal crime spikes and weekday analysis
- Crime distribution by area and demographic group
- Correlation with economic indicators and major events

---

## 📌 Future Enhancements
- Integrate external economic and policy datasets for stronger correlations
- Apply deep learning models (e.g., LSTM) for better crime forecasting
- Create interactive dashboards using Streamlit or Dash

---

## 👥 Contributors
- Divyia Venkat Eachampatti Thirunavukarasu  
- Pramoth Guhan  
- Rohith Adhitya Chinnannan Rajkumar

---

## 📅 Submission
**IE6400 Foundations of Data Analytics Engineering**  
Fall Semester 2023 | Group 22  
Submitted: November 3, 2023

---

## 📜 License
This project is for educational purposes only and uses public data under the [Open Government License].

