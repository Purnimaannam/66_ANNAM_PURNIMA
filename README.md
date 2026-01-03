#  DeviceGuru

### AI-Based Plan & Device Recommendation Assistant

**From Endless Scrolling to Confident Decisions**

---

##  Problem Statement

Choosing the right **telecom plan** or **electronic device** online is overwhelming.

Most existing platforms rely on:

*  Keyword-based filters
*  Popularity rankings and advertisements
*  The assumption that users understand technical specifications

This creates a major gap between **what users actually need** and **what systems understand**, leading to:

* Decision fatigue
* Confusing comparisons
* Poor or regrettable purchase choices

---

##  Solution

**DeviceGuru** is a **hybrid AI system** that understands users *before* recommending anything.

Instead of filtering products, DeviceGuru **reasons about user intent**.

### How it Works

1. **User Input**

   * Users describe their needs naturally
   * Example: budget, daily usage, priorities, flexibility

2. **Intent Understanding (LLM)**

   * A Large Language Model interprets:

     * User intent
     * Constraints
     * Hidden preferences

3. **Decision Engine (ML)**

   * A machine learning model evaluates plans/devices using:

     * Multi-factor suitability scoring
     * Objective comparison logic

4. **Output**

   *  Structured recommendation
   *  Clear, human-readable explanation

 **DeviceGuru converts human intent into analytical decisions.**

---

##  Why DeviceGuru Stands Out

*  Hybrid architecture (LLM reasoning + ML evaluation)
*  No ads, sponsored bias, or popularity-based ranking
*  Handles vague, real-world user intent
*  Transparent and explainable recommendations
*  A true **decision assistant**, not a listing engine

---

##  Project Structure

```
DeviceGuru/
│
├── README.md                  # Main pitch + architecture + run guide
├── requirements.txt           # Dependencies
├── .env.example               # API key template
│
├── data/
│   ├── raw/
│   │   └── mobile_price_classification.csv
│   └── processed/
│       └── cleaned_data.csv
│
├── models/
│   ├── train_model.py         # ML model training
│   ├── evaluate_model.py      # Model evaluation
│   └── price_model.pkl        # Saved ML model
│
├── agents/
│   ├── intent_agent.py        # LLM intent understanding
│   └── explanation_agent.py   # LLM explanation generator
│
├── core/
│   ├── recommender.py         # Hybrid rule + ML logic
│   ├── schema.py              # Input / Output schemas
│   └── utils.py               # Helper functions
│
├── api/
│   └── main.py                # FastAPI backend
│
├── ui/
│   └── app.py                 # Streamlit interface
│
├── notebooks/
│   └── exploration.ipynb      # Data exploration
│
└── docs/
    └── architecture.png       # System architecture diagram
```

---
##  Tech Stack

* **Python**
* **Scikit-learn**
* **LangChain**
* **FastAPI**
* **Streamlit**

---
##  Impact

* Reduces decision fatigue
* Prevents incorrect or impulsive purchases
* Empowers non-technical users
* Improves confidence in decision-making

---

##  Future Scope & Expandability

DeviceGuru can be extended to:

* Laptops & home appliances
* Insurance & subscription plans
* Healthcare decision systems
* Financial and investment tools

---
## Conclusion

DeviceGuru redefines digital recommendations by shifting the focus from selling products to supporting informed decision-making. By combining AI reasoning with machine learning, it delivers trustworthy, explainable, and user-centric recommendations.
