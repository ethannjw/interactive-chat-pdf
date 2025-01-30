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

1. Ensure that you have installed ollama in your machine. 
    * [Windows](https://github.com/ollama/ollama/blob/main/docs/windows.md)

2. Check that ollama is installed correctly
```bash
ollama -v
```
If ollama is installed correctly, you should see this:
`ollama version is 0.3.13`

If not, please check first ollama is installed correctly before proceeding

3. Ensure that you first download and run your desired model
```bash
ollama run deepseek-r1
```

4. Install the requirements
```bash
pip install -r requirements.txt
```

5. Run the UI
```bash
streamlit run main.py
```