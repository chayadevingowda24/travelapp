**AI Traveller App**


A simple Streamlit web app that takes a few trip details and returns a budget analysis, a hotel suggestion, a travel-style recommendation, and a trip score.
Note: The recommendations are currently rule-based (if/else logic). No AI model is called yet.
Features
* Collects trip details: destination, travel date, budget (₹), travel type, and interests
* Budget analysis: classifies the budget and suggests a hotel category
* Travel recommendation: tailored tip based on travel type
* Trip score: calculated from selected interests, budget, and travel type
* Travel summary: shows all entered details with the final score
Tech Stack
* Python 3.8+
* Streamlit

***** Getting Started**

**1. Clone the repository**

  bash
  
  git clone <your-repo-url>
  
  cd  your-repo-folder


**2. Install dependencies**

bash

pip install streamlit

**3. Run the app**

bash
streamlit run trave_app.py


The app opens at http://localhost:8501.
