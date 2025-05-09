## Comparative Analysis of Machine Learning Models for Delivery Time Prediction 🚀

### Project Overview
This project aims to **predict food delivery times accurately** using machine learning models. The primary goal is to optimize delivery operations by analyzing key factors such as **distance, traffic levels, weather conditions, and vehicle types**. Through data-driven decision-making, the objective is to enhance **customer satisfaction and operational efficiency** in real-world logistics scenarios.

### Dataset Description
The dataset, sourced from *Kaggle*, includes:
- **Traffic Conditions**: Low, Medium, High traffic levels during delivery.
- **Weather Descriptions**: Sunny, Cloudy, Rainy, Foggy conditions affecting delivery time.
- **Delivery Person Attributes**: Age, ratings, and vehicle type (Motorcycle, Scooter, Electric Scooter).
- **Distance and Geographical Data**: Latitude and longitude coordinates of both restaurant and delivery location.
- **Target Variable**: Delivery time in minutes.

### Methodology
1. **Data Preprocessing**: Cleaned NaN values, removed unnecessary columns, and encoded categorical variables.
2. **Data Visualization**: Generated insightful visualizations to understand attribute distributions and relationships.
3. **Clustering Analysis**:
   - Applied *KMeans* and *DBSCAN* to identify patterns in traffic and delivery time.
4. **Regression Modeling**:
   - Evaluated four models: **KNN, CART, SVR, GPR**.
   - *KNN* achieved the highest accuracy with an R² score of **0.86**.
5. **Model Evaluation**:
   - Compared models using *MAE*, *MSE*, *RMSE*, and *R²* metrics.

### Key Findings
- **KNN Regression** was the top performer with the lowest error rates and highest predictive accuracy.
- **Traffic and Distance** are the most influential factors in determining delivery time.
- *DBSCAN* effectively identified outliers in delivery time estimation.

### Future Enhancements
- Integration with **real-time delivery tracking** using *Flask* or *AWS Lambda*.
- Testing **Ensemble Models** like *Random Forest* and *XGBoost* to further improve accuracy.

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/hemanth379/Comparative_Analysis_of_ML_Models_for_Delivery_Time_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd delivery-time-prediction
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Group6_Final_code.ipynb
   ```

### Team Members
- **Sai Soumya Aloor**
- **Sri Charan Desetty**
- **Venkata Naga Anirudh Chaganti**
- **Anantha Prahlada Kurudi**
- **Hemanth Varma Pericherla**

### Connect
Feel free to reach out if you want to discuss the project, predictive modeling, or data science in general. Let's connect and grow together! 😊

#DataScience #MachineLearning #PredictiveAnalytics #Logistics #FoodDelivery #Teamwork
