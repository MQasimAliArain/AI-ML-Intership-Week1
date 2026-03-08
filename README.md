# AI & ML Internship
## Task 2: Stock Price Prediction
## Task Objective
To predict the closing price of Apple Inc. (AAPL) using machine learning regression models (Linear Regression and Random Forest).
## Dataset
- **Source**: Yahoo Finance via `yfinance` API.
- **Features**: Open, High, Low, Volume.
- **Target**: Close Price.
## Models Used
1. **Linear Regression**: A simple statistical model for finding linear relationships.
2. **Random Forest Regressor**: An ensemble learning method using 100 decision trees for higher accuracy.
## Results
The models were visualized using a 'Separated Comparison View' with a $5 offset to clearly show how both models track the Actual Price trend. Random Forest provided a robust fit for the stock's volatility.

## Task 4: AI Health Assistant Chatbot
## Task Objective
To develop an intelligent, safe, and interactive health query chatbot using Large Language Models (LLMs) that provides structured medical information while implementing strict safety guardrails.
## Dataset & Model
- **Model Used**: Qwen/Qwen2.5-7B-Instruct
- **Infrastructure**: Hugging Face Inference API
- **Tech Stack**: Python, ipywidgets, python-dotenv
## Key Features
1. **Safety Guardrails**: A robust keyword filter that intercepts and blocks high-risk queries before model processing.
2. **AI Persona**: Configured as a "Senior Medical Assistant" to ensure professional and structured formatting.
3. **Structured Output**: Every response follows a strict 4-part framework: 
    - Direct Answer
    - Safety Guidelines
    - Conclusion
    - Medical Disclaimer
    ## Results
The chatbot delivers low-latency responses with high factual consistency using a low-temperature setting ($T=0.1$). Testing confirmed that the safety layer reliably triggers for harmful prompts, and the structured persona effectively organizes complex health information into a readable, professional format.
  
## Task 6: House Price Prediction
## Task Objective
To predict the market value of residential properties using machine learning regression models (Linear Regression and XGBoost) based on physical features and location.
## Dataset
- **Source**: Synthetic dataset generated with 2,000 rows to simulate real estate market trends.
- **Features**: Square Feet, Bedrooms, Bathrooms, Location (City, Suburbs, Rural).
- **Target**: House Price.
## Models Used
1. **Linear Regression**: A baseline statistical model used to identify linear relationships between property size and price.
2. **XGBoost Regressor**: An advanced gradient boosting ensemble model designed to capture complex patterns and improve prediction accuracy.
## Results
The models achieved high precision with an **R2 Score of 0.99**. Linear Regression provided a slightly lower Mean Absolute Error (MAE) of **$11,604**, while XGBoost demonstrated strong stability across the 2,000-row dataset. An interactive **IPyWidgets dashboard** was implemented to allow real-time price estimation based on user input.
4. **Interactive Interface**: A custom-built Jupyter Notebook UI featuring real-time animations and automated smooth scrolling.
