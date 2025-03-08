# PDF Summariser with Ollama and DeepSeek-R1

This repository hosts a Jupyter Notebook that leverages Ollama’s OpenAI-compatible API and the deepseek-r1 model to extract and summarise text from PDF files, Providing a concise summary from a PDF document.

## Requirements

- **Python Packages:**
  - PyMuPDF (for `fitz`)
  - pdfplumber
  - pandas
  - openai

- **Ollama Installation:**  
  Ollama is required to run this project. Download and install Ollama from the official website with the link given below:  
   [Ollama Installation Guide](https://ollama.ai/)

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Rakesh-v27/PDF_Summariser.git
   ```

2. **Create and Activate a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   
   ```

3. **Install Python Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install and Configure Ollama:**
   - Download Ollama from [ollama.ai](https://ollama.ai/) and install it on your PC.
   - Once installed, pull the deepseek-r1 model by running:
     ```bash
     ollama pull deepseek-r1:1.5b
     ```

## Usage

Open the `PDF_summariser.ipynb` notebook in Jupyter Notebook or JupyterLab, update the notebook as needed to specify your PDF files, and execute the cells to extract text and generate summaries.


