# WanderMind-project

WanderMind is a LangChain-powered agentic AI application that helps users create intelligent and optimized travel plans. It integrates multiple tools like weather, currency conversion, place search, and calculators, and provides a conversational interface through Streamlit.

🌟 Features

    🧠 Agentic AI Workflow powered by LangChain.

    🌦️ Real-time Weather Tool for your destination.

    🌍 Place Search Tool for attractions and local recommendations.

    💱 Currency Converter for budget planning.

    🧮 Cost Calculator integrated into trip logic.

    🌐 Web UI using Streamlit (lightweight and fast).

   
🧩 Powered Tools (Modular Agents)

    WeatherTool – Uses location to provide live weather.

    PlaceSearchTool – Suggests places to visit.

    CalculatorTool – Performs budget calculations.

    CurrencyConverterTool – Converts between INR, USD, etc.


    🚀 How to Run
Option 1: 🔁 Run via Streamlit UI (Recommended)

pip install -r requirements.txt
streamlit run streamlit_app.py

    Then open your browser at: http://localhost:8501

Option 2: 🖥️ Run via Command Line (CLI)

python main.py

⚙️ Configuration

Edit config/config.yaml to add your OpenAI API key:

openai_api_key: "sk-xxxxxxxxxxxx"

    You can also use environment variables securely in production.

