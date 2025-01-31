# 🔍 Crime Data Analysis Project

## 📌 Project Overview
This project analyzes crime data from various cities in India to uncover patterns, trends, and insights into crime distribution. The dataset is stored in a MySQL database and is processed using Python with Pandas, Matplotlib, and Seaborn for data visualization.

## 🎯 Objectives
1. 📊 Identify the cities with the highest crime rates.
2. 👶👨‍🦳 Analyze the distribution of crime victims by age group.
3. 🔫 Examine commonly used weapons in crimes.
4. 🚨 Investigate gender distribution in domestic violence cases.
5. 🏙️ Determine the most commonly committed crimes in each city.
6. ✅ Identify crime types that are most commonly closed.
7. 👮 Evaluate police deployment for different crime types.
8. 🏛️ Study crime distribution across various crime domains.
9. 🔨 Examine the role of blunt objects as weapons in crimes.
10. 🏢 Identify cities with the highest number of open crime cases.

## 📂 Data Source
The dataset is stored in a MySQL database under the schema `crimedb`, with a primary table named `crime_dataset_india`. It includes information on crime types, victims, crime locations, weapons used, police deployment, and case status.

## 🛠️ Technologies Used
- **Programming Language:** Python 🐍
- **Database:** MySQL 🗄️
- **Libraries Used:**
  - `mysql.connector` for MySQL connectivity 🔗
  - `pandas` for data manipulation 📊
  - `matplotlib` and `seaborn` for data visualization 📈

## 🧹 Data Cleaning Process
To ensure data accuracy and consistency, the following steps were performed:
1. 🧐 Checked for missing values and removed incomplete records.
2. 🔄 Removed duplicate entries to avoid redundancy.
3. 🔠 Standardized text formats for consistency.
4. 📏 Categorized numerical values into meaningful groups.
5. 🚫 Filtered out irrelevant data to improve analysis quality.

## 🚀 Steps to Run the Project
### 1. 🏗️ Set Up MySQL Database
Ensure that MySQL is installed and running. Import the dataset into the database:
```sql
USE crimedb;
SELECT * FROM crime_dataset_india;
```

### 2. ⚙️ Install Required Libraries
If you haven't already, install the necessary Python libraries:
```bash
pip install mysql-connector-python pandas matplotlib seaborn
```

### 3. 🖥️ Run the Python Script
Execute the script in a Jupyter Notebook or a Python environment:
```bash
python crime_analysis.py
```

## 📊 Key Findings
1. 🔴 **Highest Crime Rate**: Delhi reports the highest number of crimes.
2. 🏃 **Age Distribution**: Most victims fall in the age group of 19-30.
3. 🔪 **Weapons Used**: Blunt objects are commonly used in burglaries.
4. 👩 **Domestic Violence**: Female victims dominate domestic violence cases.
5. 💻 **Cybercrime**: Cybercrime is prevalent in Delhi.
6. ✅ **Crime Closure Rate**: Public intoxication cases have the highest closure rate.
7. 🏙️ **Open Cases**: Delhi has the most open crime cases, indicating delays in resolution.

## 📈 Visualizations
The project includes the following visualizations:
- 📊 Bar charts for city-wise crime distribution.
- 📉 Line plots for age distribution across crime types.
- 🥧 Pie charts for weapon usage and gender distribution.
- 🎯 Dot plots for crime types by city.
- 🔥 Heatmaps for closed cases by crime type.
- 📏 Stacked bar charts for police deployment analysis.

## 🏁 Conclusion
The analysis provides valuable insights into crime trends in India. The findings can assist law enforcement agencies in better resource allocation, crime prevention strategies, and policy-making to improve public safety.

## 🔮 Future Enhancements
- 🤖 Implement machine learning models to predict crime hotspots.
- 🗺️ Add geospatial analysis for crime mapping.
- 🔄 Automate data updates from live crime reports.

## ✍️ Author
[Rhea Fernandes]

## 📜 License
This project is open-source and available for use under the MIT License.

