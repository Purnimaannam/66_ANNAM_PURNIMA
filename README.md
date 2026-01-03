DeviceGuru

AI-Based Plan & Device Recommendation Assistant
From Endless Scrolling to Confident Decisions
Problem Statement
Choosing the right telecom plan or electronic device online is overwhelming.
Most existing platforms depend on:
Keyword-based filters
Popularity rankings and advertisements
The assumption that users understand technical specifications
This creates a major gap between what users actually need and what systems understand, leading to confusion, decision fatigue, and poor purchase choices.

Solution

DeviceGuru is a hybrid Machine Learning + AI reasoning system designed to understand users before recommending anything.
How it works:
Users express their needs naturally (budget, usage, priorities).
A Large Language Model (LLM) interprets intent, constraints, and preferences.
A Machine Learning model evaluates and ranks plans or devices using multi-factor suitability scoring.
The system returns:
A structured recommendation
A clear, human-readable explanation
DeviceGuru converts human intent into analytical decisions.

Why It Stands Out

Hybrid architecture combining LLM-based reasoning with ML-based evaluation
Not influenced by ads, popularity, or keyword bias
Handles vague, real-world user intent
Produces transparent and explainable recommendations
Designed as a decision assistant, not a product listing engine

Technical Architecture:
DeviceGuru/
│
├── README.md                  # ⭐ Main pitch + architecture + run guide
├── requirements.txt           # Dependencies
├── .env.example               # API key template (never commit real key)
│
├── data/
│   ├── raw/
│   │   └── mobile_price_classification.csv
│   └── processed/
│       └── cleaned_data.csv
│
├── models/
│   ├── train_model.py         # ML training script
│   ├── evaluate_model.py      # (optional) metrics
│   └── price_model.pkl        # Saved ML model
│
├── agents/
│   ├── intent_agent.py        # LLM intent understanding
│   └── explanation_agent.py   # LLM explanation generator
│
├── core/
│   ├── recommender.py         # Rule + ML hybrid logic
│   ├── schema.py              # Input / Output schemas
│   └── utils.py               # Helper functions
│
├── api/
│   └── main.py                # FastAPI backend
│
├── ui/
│   └── app.py                 # Streamlit UI
│
├── notebooks/
│   └── exploration.ipynb      # Data understanding (optional but good)
│
└── docs/
    └── architecture.png       # Optional diagram for presentation

Below is how DeviceGuru converts user intent into explainable recommendations:
Intent Understanding: LangChain-powered Large Language Model
Decision Engine: Scikit-learn Machine Learning model
Backend API: FastAPI
User Interface: Streamlit
Data Layer: Structured datasets for plans and devices
The architecture is modular, scalable, and production-oriented.

Impact & Expandability

Reduces decision fatigue and incorrect purchases
Enables non-technical users to make confident decisions
Easily extendable to:
Laptops and home appliances
Insurance and subscription plans
Healthcare and financial decision systems

Tech Stack
Python
Scikit-learn
LangChain
FastAPI
Streamlit

 Run Instructions

Create a virtual environment and install dependencies
Train the machine learning model
Start the FastAPI backend
Launch the Streamlit interface
