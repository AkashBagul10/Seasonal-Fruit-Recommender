Seasonal Fruit Recommender for India 🍎🥭

A full-stack AI application designed to provide hyper-local, seasonal, and personalized fruit recommendations across all 28 states and 8 union territories of India.

🚀 Overview

This project solves the problem of seasonal eating in a geographically diverse country like India. By analyzing regional harvest cycles, local varieties, and user health goals, the system recommends the best fruits available in a specific district for any given month.

✨ Key Features

Hyper-Local Intelligence: Data granular enough to provide recommendations at the district level.

Explainable AI (XAI): Instead of a "black box" score, the system provides human-readable reasons for every recommendation (e.g., "The famous 'Alphonso' is at its absolute peak of flavor in Maharashtra right now").

Predictive Scoring: Uses an XGBoost regression model trained on a custom dataset to rank fruits based on seasonality, locality, and price.

Dynamic UI: A responsive dashboard built with Tailwind CSS featuring fruit imagery and a health-goal personalization layer.

🛠️ Tech Stack

Backend: Python, Flask, Flask-CORS

Machine Learning: XGBoost, Scikit-Learn, Pandas, NumPy, Joblib

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS

Data Engineering: Custom ETL pipeline to merge 36+ regional JSON datasets into a unified schema.

📊 The Data Pipeline

The project utilizes a rich dataset (fruits_database_finalv2.json) containing:

Specific fruit varieties (e.g., Kesar vs. Alphonso vs. Dasheri).

Monthly harvest cycles for every Indian state.

Average market pricing and nutritional health tags.

High-quality imagery for user engagement.

⚙️ Installation & Setup

Clone the repository:

Install dependencies:

pip install -r requirements.txt


Run the Backend API:

python main.py


Launch the Frontend:
Open index.html in your preferred browser.

📈 Future Roadmap

Integration of a real-time price API.

User accounts to save "Favorite" fruits and health profiles.

Interactive SVG "Fruit Map of India" for exploratory browsing.
