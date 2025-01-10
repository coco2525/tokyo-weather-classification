# Classification System Based on Tokyo Weather Data

## Introduction
This project, undertaken in **Summer 2024**, builds a machine learning classification system using Tokyo weather data. Five algorithms—Naive Bayes, Decision Tree, Random Forest, Support Vector Machine (SVM), and K-Nearest Neighbor (KNN)—are implemented and compared to identify the best-performing model. The goal is to provide highly accurate weather condition predictions based on hourly weather data from July 2023 to July 2024.

## Data
- **Source**: [OpenWeatherMap API](https://openweathermap.org/)
- **Features**: 
  - Date
  - Max/Min Temperature
  - Humidity
  - Rainfall
  - Pressure
  - Wind Speed
  - Wind Direction
  - Cloud Cover
  - Weather Type (e.g., clear, cloudy, rain)

## Key Steps
1. **Data Preparation and Preprocessing**
   - Verified no missing values.
   - Analyzed statistics (e.g., max temperature ranged from 34.84°F to 103.78°F).
   - Addressed multicollinearity by excluding highly correlated features.

2. **Data Visualization**
   - Seasonal patterns in temperature and rainfall.
   - Violin plots for temperature distributions by weather type.
   - Correlation matrix heatmaps.

3. **Model Building**
   - Algorithms: KNN, Naive Bayes, Decision Tree, Random Forest, and SVM (with Linear, RBF, Polynomial, and Sigmoid kernels).
   - Data split into 70% training and 30% testing.

4. **Evaluation**
   - Cross-validation with 5 folds.
   - Metrics: Accuracy, Precision, Recall, and F1 Score.
   - Best Model: Random Forest (Accuracy: 99%, F1 Score: 0.98).

## Deployment
The model is deployed with a user-friendly web interface allowing non-technical users to input meteorological data and receive forecasts.
- **Live Demo**: [Weather Forecast App](https://coco2525.pythonanywhere.com/classification)

## Real-world Applications
1. **Daily Planning**: Helps residents and tourists prepare for outdoor activities.
2. **Event Management**: Enables better planning for outdoor events.
3. **Agriculture and Logistics**: Optimizes harvesting schedules and delivery coordination.
4. **Disaster Prevention**: Supports early warnings and evacuation strategies for severe weather.

## Future Improvements
- Incorporate multi-year datasets for better accuracy.
- Extend the model to global weather forecasting.
- Explore integration with real-time cloud platforms for broader applications.

---

## Author
- **Momo Ogawa**  
