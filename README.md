# Invoice Extractor LLM App Using Gemini Pro
This project is an Invoice Extractor application that leverages the Gemini Pro language model to extract relevant information from invoices. The application is built using Streamlit.
## Overview
The Invoice Extractor LLM App is designed to simplify the process of extracting key information from invoice documents. By utilizing the power of Gemini Pro, a state-of-the-art language model, this app provides accurate and efficient data extraction capabilities.
## Features
- **Automated Invoice Data Extraction**: Extracts key fields such as invoice number, date, total amount, and more.
- **User-Friendly Interface**: Easy-to-use interface built with Streamlit.
## Installation
To run the app locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Tejas320/Invoice-Extractor-GeminiPro.git
    cd Invoice-Extractor-GeminiPro
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```
## Usage
Once the app is running, you can upload an invoice document, and the app will extract and display the relevant information.
## Dependencies
The project relies on the following Python packages:
- streamlit
- google-generativeai
- python-dotenv
- langchain
- PyPDF2
- chromadb
