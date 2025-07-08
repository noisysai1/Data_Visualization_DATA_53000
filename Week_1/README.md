# Week 01: Traffic Prediction Dataset

**Course:** DATA-53000: Data Visualization  
**Author:** Sai Kumar Murarishetti  

## 📄 Abstract  
Urban traffic congestion poses significant challenges for planners and commuters alike. This project leverages a machine‐vision–collected dataset to analyze vehicle counts, traffic levels and hourly patterns. 
Future extensions will include vehicle speed data and additional contextual features to deepen insights.

## 🌐 Dataset Description  
The CSV dataset contains time-stamped counts and classifications for four vehicle types, along with an overall traffic‐level indicator:
- **Time** (hh:mm:ss AM/PM)  
- **Date** (MM/DD/YYYY)  
- **Day** (e.g., Tuesday)  
- **Types of Vehicles** (Bike, Bus, Truck, Car)  
- **Total No. of Vehicles** (integer count)  
- **Traffic Situation** (1=Heavy, 2=High, 3=Normal, 4=Low) :contentReference[oaicite:1]{index=1}

Source:_ [Kaggle: Traffic Prediction Dataset](https://www.kaggle.com/datasets/hasibullahaman/traffic-prediction-dataset)

## 🧪 Methodology  
1. **Data Collection**  
   - A stationary machine‐vision system captured vehicle counts every 15 minutes.  
2. **Preprocessing**  
   - Parsed timestamps, encoded traffic levels, and aggregated counts by hour.  
3. **Visualization**  
   - Generated six key charts (bar plots, pie charts, and line trends) to reveal hourly and vehicle‐type patterns.

## 📊 Visualizations  

| Figure | Description                                                                      

| ![Fig1](bike_bar.png)  | **Fig 1.** Hourly Bike Count (Bar Plot)|
| ![Fig2](bus_bar.png)   | **Fig 2.** Hourly Bus Count (Bar Plot) |
| ![Fig3](truck_car_bar.png) | **Fig 3.** Hourly Truck & Car Count (Bar Plot)<br/>_Peak at 4 PM; early‐morning truck activity noted._ |
| ![Fig4](vehicle_pie.png) | **Fig 4.** Proportion of Bikes vs. Buses by Hour (Pie Charts)|
| ![Fig5](hourly_trend.png) | **Fig 5.** Overall Traffic Trend Across Hours (Line Plot)|
| ![Fig6](bike_trend.png)   | **Fig 6.** Bike‐Specific Trend Across Hours (Line Plot)|


## 📝 Key Insights  
- **Rush‐hour spike:** 4 PM exhibits the highest combined volume—likely evening commute.  
- **Early‐morning freight:** Elevated truck counts around 2 AM suggest overnight logistics operations.  
- **Mode patterns:** Bikes show a smoother, daylight‐linked trend, whereas buses and cars peak sharply at commute times.

## 🔮 Conclusion  
This dataset empowers urban planners and transportation agencies to pinpoint congestion periods and optimize traffic flow. 
Upcoming enhancements—such as adding speed metrics—will bolster predictive modeling and decision support for sustainable city planning.


## 📚 References  
1. Hasibullah Aman, “Traffic Prediction Dataset,” Kaggle, 2020. :contentReference[oaicite:3]{index=3}  
2. … _(add any additional sources you consulted)_

