# Interactive chat PDF

Source: https://medium.com/@soumavadey/interactive-pdf-chat-app-with-deepseek-r1-ollama-full-code-walkthrough-61d0e64dc7f2


# Setup

Install requirements
 * Docker
 * Ollama
 * Desired llm model
 * Python3.10
 * Pip3
 * A powerful enough GPU


1. Ensure that you first download and run your desired model
```bash
ollama run deepseek-r1
```

2. Install the requirements
```bash
pip install -r requirements.txt
```

3. Run the UI
```bash
streamlit run main.py
```