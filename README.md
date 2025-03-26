# NYC Yellow Cab Trip Data Analysis (2023)

## 📊 About this Project
This repository contains an exploratory data analysis (EDA) of NYC Yellow Cab trip data for the year 2023. The project includes a Jupyter Notebook and a PDF report summarizing key findings, visualizations, and insights derived from the data.

---

## 📁 Repository Structure
```
├── EDA_Assg_NYC_Taxi_Starter_Prasoon_Kumar_Jha.ipynb      # Jupyter Notebook with full analysis  
├── Report_EDA_on_NYC_Taxi_Records_Prasoon_Kumar_Jha.pdf   # PDF Report generated from the notebook  
└── README.md                                              # Project overview and instructions  
```

---

## ✅ Key Insights
- **Top Pickup & Dropoff Zones:** Most popular areas for taxi activity  
- **Trip Distance vs. Tip Percentage:** How tipping behavior varies with trip distance  
- **Passenger Count Across Zones:** Demand hotspots identified across NYC zones  
- **Fare per Mile Analysis:** Comparison of fare efficiency across days of the week and hours of the day  

---

## 📊 Visualizations Included
- Bar plots for top pickup and dropoff zones  
- Tip percentage distribution by trip distance bins  
- Passenger count hotspots visualized on an NYC map  
- Average fare per mile by day of the week and hour of the day  

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/kumarprasoonjha/eda-on-nyc-taxi-prasoon-kumar-jha.git  
cd eda-on-nyc-taxi-prasoon-kumar-jha  
```

### 2. Install required dependencies (recommended versions)
```bash
numpy==1.26.4  
pandas==2.2.2  
matplotlib==3.10.0  
seaborn==0.13.2  
```

### 3. Prepare data
- Download and place the NYC Yellow Cab 2023 dataset in your local directory  
- Update `trip_records_dir` and `taxi_zones_dir` variables in the notebook accordingly  

### 4. Run the notebook
```bash
jupyter notebook eda-on-nyc-taxi-prasoon-kumar-jha.ipynb
```
