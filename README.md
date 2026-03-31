Global Air Pollution — Exploratory Data Analysis    
A clean, beginner-friendly Exploratory Data Analysis on the Global Air Pollution Dataset from Kaggle — covering ~23,000 cities across the world.
________________________________________
 About the Dataset
Field	Details
Source	Kaggle — hasibalmuzdadid
Rows	~23,000
Coverage	Cities worldwide
Key columns	Country, City, AQI Value, AQI Category, CO, Ozone, NO₂, PM2.5
________________________________________
 What This EDA Covers
Step	Analysis
1	Imports & setup
2	Load data
3	Data types — pd.to_numeric, .str.strip()
4	Missing values — count, plot, clean
5	Descriptive statistics
6	AQI distribution — histogram + box plot
7	AQI category breakdown — bar + pie chart
8	Top 15 most polluted countries
9	Top 15 cleanest countries
10	AQI vs each pollutant (scatter + trend line)

How to Run
1. Clone the repo
git clone https://github.com/YOUR_USERNAME/global-air-pollution-eda.git
cd global-air-pollution-eda
2. Install dependencies
pip install pandas numpy matplotlib seaborn notebook
3. Download the dataset
Go to 👉 Kaggle Dataset
Download global air pollution dataset.csv and place it in the project folder.
4. Launch the notebook
jupyter notebook global_air_pollution_eda.ipynb
Then click Run All.
________________________________________
📁 Project Structure
global-air-pollution-eda
          ├── global_air_pollution_eda.ipynb   # Main EDA notebook
          ├── global air pollution dataset.csv # Dataset (download from Kaggle)
          └── README.md
________________________________________

 Libraries Used
•	pandas — data loading and manipulation
•	numpy — numerical operations
•	matplotlib — plotting
•	seaborn — heatmaps and styled plots
________________________________________
 Key Findings
•	PM2.5 has the strongest correlation with overall AQI
•	Most cities globally fall in the Good or Moderate AQI category
•	South and Southeast Asian cities dominate the most polluted rankings
•	Wind and geographic factors contribute to AQI variation across regions
________________________________________

