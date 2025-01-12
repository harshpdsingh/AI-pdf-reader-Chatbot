# Local Retrieval-Augmented Generation (RAG) with PDFs

This repository provides a framework for ingesting, processing, and retrieving relevant information from PDF documents using advanced NLP techniques.


## Installation

### Step 1: Install Ollama

To install `ollama` and its dependencies, follow these steps:

1. **Install Python**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. **Open a Web Browser**: Go to your favorite web browser and navigate to [Ollama's GitHub repository](https://github.com/Ollama).

3. **Clone the Repository**: Open your terminal or command prompt and clone the repository using the following command:
    ```bash
    git clone https://github.com/Ollama/ollama.git
    ```

4. **Navigate to the Directory**: Change to the cloned directory:
    ```bash
    cd ollama
    ```

5. **Install Dependencies**: Run the following command to install all necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Step 2: Install Additional Dependencies

For this project, you will also need the following packages:
```bash
pip install unstructured langchain "unstructured[all-docs]" langchain-community chromadb langchain-text-splitters
