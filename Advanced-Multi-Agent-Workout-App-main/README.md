# 🏋️ Multi-Agent AI Workout & Nutrition Planner

This project demonstrates an advanced, multi-agent LLM architecture designed to provide personalized fitness and nutrition planning grounded in the user's specific data. Built using LangFlow for orchestration and Streamlit for the user interface.

---

## 🌟 Key Features

* **Intelligent Routing:** Uses an LLM agent to dynamically route user queries to the most qualified specialized agent (e.g., calculation agent vs. RAG agent).
* **Personalized RAG:** Implements a Retrieval-Augmented Generation (RAG) pipeline to ground responses in user-provided health notes, ensuring highly contextual and accurate advice.
* **Tool Calling:** Integrates specialized tools (like a calculator) to enhance LLM reliability for complex, numerical tasks (e.g., macro counting).
* **User Interface:** Provides a simple, interactive chat interface built entirely with Streamlit.

---

## 🛠️ Technical Stack

* **LLM Orchestration:** LangChain, LangFlow (for visual flow management and API)
* **Vector Database:** Astra DB (used for vector storage and semantic search)
* **Frontend:** Streamlit (Full Python UI)
* **Agent Logic:** Python 3.x
* **Core Libraries:** [List core libraries like `pandas`, `requests`, etc.]

---

## 🚀 Getting Started

Follow these steps to set up and run the application locally.

### Prerequisites

You need an API key for your chosen LLM (e.g., OpenAI) and access credentials for Astra DB.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Madhav-Ahuja27/Multi-Agent-Workout-App.git](https://github.com/Madhav-Ahuja27/Multi-Agent-Workout-App.git)
    cd Multi-Agent-Workout-App
    ```

2.  **Set up Virtual Environment** (Recommended)
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure Environment Variables**
    Create a file named `.env` in the root directory and add your keys:
    ```
    OPENAI_API_KEY=your_key_here
    ASTRA_DB_APPLICATION_TOKEN=your_token_here
    # ... any other keys needed for Astra DB connection ...
    ```

5.  **Run the Streamlit App**
    ```bash
    streamlit run app.py
    ```
    The application will open in your browser.

---

## 🔗 Live Demo & Links

* **Live App:** [**Insert your Streamlit Cloud Deployment Link Here**]
* **Personal Website/Portfolio:** [**Your LinkedIn Profile URL**]

---

## 👤 Author

**Madhav Ahuja**

* GitHub: [github.com/Madhav-Ahuja27]
