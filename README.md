# WanderMind-project

WanderMind is a LangChain-powered agentic AI application that helps users create intelligent and optimized travel plans. It integrates multiple tools like weather, currency conversion, place search, and calculators, and provides a conversational interface through Streamlit.

🌟 Features

    🧠 Agentic AI Workflow powered by LangChain.

    🌦️ Real-time Weather Tool for your destination.

    🌍 Place Search Tool for attractions and local recommendations.

    💱 Currency Converter for budget planning.

    🧮 Cost Calculator integrated into trip logic.

    🌐 Web UI using Streamlit (lightweight and fast).

    AI_Trip_Planner/
│
├── agent/                    # Agent logic using LangChain
│   └── agentic_workflow.py
│
├── tools/                   # Modular AI tools (weather, search, etc.)
│
├── config/                  # Configuration files
│   └── config.yaml
│
├── logger/                  # Logging utilities
├── exception/               # Custom exception handlers
├── main.py                  # CLI interface
├── streamlit_app.py         # Web interface via Streamlit
├── requirements.txt         # Python dependencies
├── README.md                # This file
└── .env.name / .python-version etc.


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

