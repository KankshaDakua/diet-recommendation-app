AI Diet Recommendation System

A simple web application that generates personalized diet recommendations based on user health data and activity level.

The system calculates BMI, BMR, TDEE, calories, macronutrients, and water intake to provide accurate nutrition suggestions.

✨ Features

Personalized diet recommendations

BMI calculation

BMR calculation (Mifflin-St Jeor equation)

TDEE estimation based on activity level

Macronutrient distribution (Protein, Carbs, Fats)

Daily water intake recommendation

🛠 Tech Stack

Frontend: Next.js

Backend: Flask (Python)

Language: Python

API: REST API

⚙️ Installation
Backend
git clone https://github.com/yourusername/ai-diet-recommendation.git
cd ai-diet-recommendation
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py

Backend runs on:

http://127.0.0.1:5000
Frontend
cd frontend
npm install
npm run dev

Frontend runs on:

http://localhost:3000
📊 Calculations Used

BMI = weight (kg) / height² (m²)

BMR = Mifflin-St Jeor Equation

TDEE = BMR × activity multiplier

Water Intake ≈ weight × 0.033

📄 License

This project is licensed under the MIT License.
