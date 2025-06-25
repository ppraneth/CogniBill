# CogniBill

This project leverages OCR and Large Language Models (LLMs) to intelligently extract and summarize crucial details from uploaded invoice images.

## Features

* **Invoice Image Upload:** Seamlessly upload your invoice images for processing.
* **OCR Text Extraction:** Utilizes Tesseract OCR to accurately extract text content from the uploaded invoices.
* **AI-Powered Summarization:** Employs Google Gemini Pro/Flash to identify and summarize key fields and information from the extracted invoice data.

## Run

To get started with CogniBill, follow these simple steps:

1.  **Create a `.env` file:** In the root directory of the project, create a file named `.env`.
2.  **Add your Google API Key:** Open the `.env` file and add the following line, replacing `API_KEY` with your actual Google API Key:
    ```
    GOOGLE_API_KEY=YOUR_API_KEY_HERE
    ```
3.  **Install dependencies and run:**
    ```bash
    pip install -r requirements.txt
    python app.py
    ```
