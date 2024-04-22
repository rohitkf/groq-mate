# Introduction
A simple implementation of RAG using open source models
Checkout my other projects [here](https://rohitkf.dev)

# Steps to run the application :
- Step 0 : Create a new environment using [Anaconda](https://www.anaconda.com/download)
    ```Bash
    conda create -p venv -y
    ```

- Step 1 : Install Ollama [here](https://ollama.com/), then install the model
    ```
    ollama run llama2
    ```
- Step 2 : Install the dependencies
    ```Bash
    pip install -r requirements.txt
    ```
- Step 3 : Create `.env` file with API KEY from [groq](https://console.groq.com/keys)
    ```Bash
    GROQ_API_KEY=your_api_key
    ```
- Step 4 : Run the application
    ```Bash
    streamlit run app.py
    ```