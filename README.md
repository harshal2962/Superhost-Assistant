🏠 Airbnb Host Coach: From Host to Superhost using AI
An AI-powered recommendation system to help Airbnb hosts achieve Superhost status and maximize revenue. Combines Gradient Boosted Decision Trees, KMeans Clustering, and a custom Growth Potential Index (GPI) to provide personalized, data-driven recommendations. Built using Python and designed for future integration with GenAI-based coaching.

📌 Executive Summary
Airbnb faces market imbalances due to underperforming hosts and a lack of growth visibility across neighborhoods. This project solves that by:

Predicting Superhost probability using 25+ listing-level variables.

Segmenting hosts into data-driven clusters.

Scoring each host/property using a Growth Potential Index (GPI).

Offering personalized strategies for revenue optimization and guest satisfaction.

🧪 Tech Stack
Python (Pandas, Scikit-learn, XGBoost)

Clustering (KMeans, Elbow Method)

SMOTE (oversampling)

Feature Engineering & Target Encoding

AUC-ROC, Precision-Recall, and VIF analysis

Jupyter Notebook

📊 Key Components
✅ Superhost Prediction (GBDT)
AUC-ROC: 0.986

Precision & Recall: 94%

Top Features: numCancel_pastYear, rating_overall, occupancy_rate

📈 Growth Potential Index (GPI)
A normalized score from 0 to 1 combining:

Superhost prediction

Cluster performance

Booking/revenue ratio

Guest ratings

📍 Clustering Analysis
Used KMeans (k=4) with features like:

Booking-to-revenue ratio

Superhost density

Occupancy rate

Resulted in:

High-Growth

Moderate-Growth

Low-Growth clusters

🔍 Sample Insights
“Your property has a GPI of 0.83 (High-Growth). Focus on increasing 5-star reviews and raise nightly rates during peak demand.”

“Cluster 2 hosts show high occupancy but low rates. Optimize pricing to increase revenue.”

📂 Project Structure
graphql
Copy
Edit
.
├── Airbnb_687_team_project.ipynb     # Full codebase: EDA + modeling
├── data/                             # Airbnb Chicago dataset
├── visuals/                          # Charts and plots
├── models/                           # Trained model objects
├── README.md                         # This file
└── requirements.txt                  # Python packages used
🚀 How to Use
bash
Copy
Edit
git clone https://github.com/yourusername/airbnb-host-coach.git
cd airbnb-host-coach
jupyter notebook Airbnb_687_team_project.ipynb
🧭 Future Roadmap
🔗 GenAI Integration: Real-time host coaching via chat interface

🌍 Scalability: Adapt to multiple cities beyond Chicago

📊 Deployment: Build Streamlit dashboard for host-level insights

👥 Contributors
Harshal Amin | LinkedIn | GitHub

Yash Kothari

