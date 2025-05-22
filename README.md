🏠 Airbnb Host Coach: From Host to Superhost using AI
An AI-powered recommendation system that helps Airbnb hosts achieve Superhost status and maximize revenue.
This project combines predictive modeling, clustering, and a custom Growth Potential Index (GPI) to provide personalized, data-driven insights for Airbnb hosts. Built in Python, it’s designed for future integration with GenAI-based coaching tools.

🧩 Overview
Problem:
Many Airbnb hosts struggle to achieve Superhost status or optimize revenue due to a lack of actionable insights.

Solution:
The Airbnb Host Coach addresses this by:

>Predicting Superhost probability using Gradient Boosted Decision Trees (GBDT).

>Segmenting listings using KMeans Clustering.

>Scoring each host using a unified Growth Potential Index (GPI).

>Delivering personalized recommendations to boost performance and earnings.

🧪 Tech Stack
Languages & Tools: Python, Jupyter Notebook

Libraries: Scikit-learn, XGBoost, Pandas, SMOTE, Matplotlib

Techniques: GBDT, KMeans, VIF analysis, Target Encoding, Hyperparameter Tuning

🔍 Core Features
🎯 Superhost Prediction (GBDT)
>AUC-ROC Score: 0.986
>Precision/Recall: 94%

Top Predictors: numCancel_pastYear, rating_overall, occupancy_rate

🌱 Growth Potential Index (GPI)
>Scores each listing from 0 (low growth) to 1 (high growth)

>Combines Superhost probability, cluster insights, booking/revenue performance, and guest ratings

🧩 Clustering Insights
>KMeans (k=4) segmentation using:

>Booking-to-revenue ratio

>Superhost density

>Occupancy rate

Result: Clear High, Moderate, and Low Growth clusters

💡 Sample Insight Cards
>Example 1: “Your property has a GPI of 0.83 — focus on increasing 5-star reviews and consider adjusting pricing during peak demand.”
>Example 2: “Cluster 2 hosts have high occupancy but underperform on revenue. Optimize your booking-to-revenue ratio.”

📁 Project Structure
.
├── Airbnb_687_team_project.ipynb     # Full codebase: EDA + modeling
├── data/                             # Airbnb Chicago dataset
├── visuals/                          # Plots and graphics
├── models/                           # Saved model objects
├── requirements.txt                  # Package dependencies
└── README.md                         # Project documentation



📈 Future Enhancements
>🤖 GenAI Integration: Build a chatbot to coach hosts in real-time

>🌍 City Expansion: Extend support beyond Chicago

>📊 Interactive Dashboard: Deploy using Streamlit for host-friendly insights

👥 Contributors
>Harshal Amin
>Yash Kothari

