1. Introduction
   1. Document Searcher is a Python application that allows to query a LLM model about the content of multiple PDF files. The app will only respond to questions regarding the content of the PDF files.
   2. This project is based on the following repo: https://github.com/alejandro-ao/ask-multiple-pdfs/tree/main
2. Dependencies and Installation
   1. Clone the repo to your local machine
      1. `git clone git@github.com:dreski3/Document_Searcher.git`
   2. Install the dependencies
      1. `pip install -r requirements.txt`
   3. Create a `.env` with your OpenAI api key and HuggingFace token as shown in `.env.example`
3. Usage
    1. Run main.py with the following command:
      1. `streamlit run app.py`
    2. The application will open in your browser
    3. Load the PDF files you want to query
    4. Ask questions about the content of the PDF files