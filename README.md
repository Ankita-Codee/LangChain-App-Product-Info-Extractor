# LangChain App (Product Info Extractor)

## 🧠 Project Description
This project is a simple assistant built using **LangChain** and **Groq's LLM** model that extracts structured product information from natural language queries. Given a product-related query, the assistant returns:
- ✅ Product Name
- ✅ One-line Description
- ✅ Tentative Price in USD (integer)

The output is strictly formatted using a **Pydantic schema**, parsed with LangChain’s `JsonOutputParser`. The model used is Groq's high-speed `llama3-70b-8192`.

---

## 🛠️ Technology Used
- **Python 3.11**
- [LangChain](https://python.langchain.com/en/latest/)
- [Groq API via langchain_groq](https://groq.com/)
- [Pydantic](https://docs.pydantic.dev/)
- [python-dotenv](https://pypi.org/project/python-dotenv/) – to manage API keys securely

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
    ```bash
    git clone https://github.com/Ankita-Codee/LangChain-App-Product-Info-Extractor.git
    cd LangChain-App-Product-Info-Extractor

### 2. Create and Activate a Virtual Environment
    ```bash
    conda create -p venv python=3.11
    conda activate venv/


### 3. Install Required Dependencies
    ```bash
    pip install -r requirements.txt
If you don’t have requirements.txt, install directly:

### 4. Set Up Environment Variables
Create a .env file in the project root:

    ```bash
    GROQ_API_KEY=your_groq_api_key_here


