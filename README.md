# -Dynamic-Pricing-Model
# 🚴‍♂️ Smart Fare Optimization: A Machine Learning Approach to Dynamic Pricing in Ride-Sharing

![Dynamic Pricing Model](https://www.inflowinventory.com/wp-content/uploads/2024/04/Dynamic-Pricing_02-1024x576.png)

---

## 📌 Project Overview

Ride-sharing companies typically use static, time-based pricing rules that often fail to reflect real-time demand or customer-specific behavior. This project introduces a **dynamic, machine learning–powered pricing model** to set ride fares based on real-world variables — boosting both **profitability** and **customer satisfaction**.

---

## 🎯 Objective

Create a **predictive pricing model** that dynamically adjusts fares by analyzing:

- 📅 Time of Booking  
- 🧑‍💼 Customer Loyalty Tier  
- 🕒 Expected Ride Duration  
- 🌍 Real-time Demand Signals  

✅ **Outcome**: Deliver fair, competitive, and profit-optimized pricing at scale.

---

## 🧠 Key Features

### 💡 Formula Logic (Simplified)

> **Predicted Fare = Base Fare + f(Time, Loyalty, Duration, Demand Conditions)**

The model uses **regression-based ensemble methods** to approximate a function `f(·)` learned from historical data.

### ⚙️ Feature Set

| Feature Name         | Description |
|----------------------|-------------|
| `booking_time`       | Time of day the ride was booked |
| `ride_duration`      | Estimated ride duration in minutes |
| `loyalty_status`     | Encoded value of user tier (e.g., Bronze, Silver, Gold) |
| `day_of_week`        | Categorical indicator for weekday vs. weekend |
| `traffic_index`      | Traffic congestion score (simulated/external) |
| `weather_condition`  | Weather state at booking time |
| `area_demand_level`  | Relative ride demand in pickup area |

> All features are preprocessed using encoding, normalization, and importance ranking.

---

## 🔢 Algorithms Used

✅ Ensemble Models:
- CatBoost  
- XGBoost  
- LightGBM  

✅ Traditional Regressors:
- Linear Regression  
- Lasso / Ridge  
- KNN Regressor  

✅ Others:
- Random Forest  
- Gradient Boosting Regressor  
- SVR (Support Vector Regression)

---

## 📈 Performance Metrics

| Metric | Value |
|--------|-------|
| R² Score | `0.84` |
| RMSE | `$68` |
| MAE  | `$53` |

---

## 💰 Business Impact Simulation

In a simulated batch of **100 customer rides**:

> 📊 **Projected Net Profit: `$2,400`**  
> 🧠 Dynamic pricing reduced underpricing during high-demand windows and offered discounts during off-peak, optimizing overall margins.

---






