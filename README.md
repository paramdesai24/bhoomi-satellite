BHOOMI: Satellite Environmental Intelligence & Analytics
BHOOMI (Satellite-Based Environmental Forecasting and Prescriptive Analytics Platform) is a state-of-the-art full-stack platform designed for urban environmental monitoring, predictive analytics, and prescriptive interventions.

Leveraging multi-source satellite data (ISRO Bhuvan, NASA MODIS, ESA Sentinel), BHOOMI provides city-wide 3km × 3km grid-based intelligence for municipal stakeholders, focusing on air quality, urban heat islands, vegetation health, and carbon footprint estimation.
<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/1602f978-a7b1-4a06-8c42-369cacb9c471" />

🚀 Key Features
Predictive Environment Modeling: Multi-horizon forecasting (1d to 180d) using ARIMA, LSTM, and Prophet for 17+ environmental metrics.
Prescriptive Urban Analytics: Rule-based engine providing spatial recommendations for green buffers, cooling corridors, and plantation patches.
Geospatial Intelligence: High-performance interactive mapping using Mapbox GL JS, Leaflet, and Deck.gl.
ML-Based Anomaly Detection: Isolation Forest-driven identification of critical environmental outliers.
Carbon Footprint Tracking: Estimation of carbon source/sink balances across urban grids.
AI-Driven Reporting: Narrative report generation using Google Gemini for executive-level summaries.
🛠 Technology Stack
Frontend
Framework: React 18, TypeScript, Vite
Mapping: Mapbox GL JS, Leaflet, Deck.gl
State Management: Zustand
Visualization: Chart.js, Recharts, Tailwind CSS
Reporting: html2canvas, jsPDF
Backend & API
API Engine: Node.js/Express.js (Primary API), Python/Flask (ML Inference)
Database: PostgreSQL (Prisma/pg-client)
AI Integration: Google Gemini 1.5 Flash
Machine Learning
Core Stacks: NumPy, Pandas, Scikit-learn, XGBoost, PyTorch
Forecasting: Statsmodels, Prophet
Explainability: SHAP (Causal Attribution)
📦 Installation & Setup
Prerequisites
Node.js v18.0.0+
Python 3.8+
PostgreSQL Instance (e.g., Neon.tech)
1. Repository Setup
git clone https://github.com/your-username/bhoomi.git
cd bhoomi
2. Environment Configuration
Copy .env.example to .env and fill in your API keys and database credentials.

cp .env.example .env
Note: You will need a Mapbox Access Token and a Google Gemini API Key.

3. Frontend & API Server Setup
npm install
# Start Backend
npm run start:server
# Start Frontend
npm run dev
4. ML Module Setup (Optional)
If you wish to run the ML inference pipeline separately:

cd bhoomi_ml_satellite_forecasting_and_predictions
pip install -r requirements.txt
python app.py

📄 Documentation
Detailed documentation and technical reports are available in the docs/ directory:

Technical Architecture
ML Pipeline & Proposal
Prescription Rules
⚖ License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributors
Created by Cosmosapiens Team for environmental sustainability through satellite intelligence.
