# Chat with PDFs
Welcome to the PDF Q&A Chatbot! This application allows you to engage in dialogue with multiple PDF documents using the power of FAISS vector embeddings, Google Gemini Pro, and LangChain.

This project is a Large Language Model (LLM) application utilizing Google Gemini Pro and LangChain, where users can chat with multiple PDF documents. The core functionality is achieved with the help of FAISS vector embeddings.

 Check out - [Live demo](https://huggingface.co/spaces/Anamithra/PDF_QA)

### Application Architecture:
![image](https://github.com/user-attachments/assets/4d48dfbd-d329-4536-b4a3-2f10dddbe795)


## Features

- Upload multiple PDF files.
- Process and store PDF text chunks using FAISS vector embeddings.
- Ask questions and get detailed answers from the content of the uploaded PDFs.
- Seamless integration with Google Gemini Pro for advanced conversational capabilities.


![image](https://github.com/user-attachments/assets/ac558583-7bd6-4832-a955-71ec30489f27)

### An example of Output-

![image](https://github.com/user-attachments/assets/87d310e5-d986-4219-bc96-4085e88960d5)


## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/anamithrak15/PDF-QA-Genie.git
    cd PDF-QA-Genie
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up your environment variables. Create a `.env` file in the root directory of the project and add your Google API key:
   Get your Google Gemini API key from - [AI Studio Google](https://aistudio.google.com/app/u/0/apikey)

    ```env
    GOOGLE_API_KEY=your-google-api-key
    ```

## Usage

1. Run the Streamlit app:

    ```bash
    streamlit run chatbot.py
    ```

2. Open your web browser and navigate to `http://localhost:8501`.

3. Use the sidebar to upload your PDF files and click the "Submit & Process" button.

4. Ask questions about the uploaded PDFs using the input box and receive detailed answers based on the document content.
