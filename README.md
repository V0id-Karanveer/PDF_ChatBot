# PDF ChatBot

Engage with your PDF documents in a whole new way! This interactive PDF ChatBot is built using Streamlit and leverages advanced language processing techniques to allow you to have dynamic conversations based on the content of your PDF files.

## Features

- Upload multiple PDFs and have interactive conversations with the chatbot.
- Extract text from PDFs, webpages, and Google Drive links.
- Utilize advanced language embeddings and retrieval methods for meaningful interactions.
- Ask questions and receive contextually relevant responses.
- Perfect for research, learning, and exploration.

## How to Use

1. Install the required dependencies by running: `pip install -r requirements.txt`
2. Set up your environment variables in a `.env` file.
3. Run the application: `streamlit run main.py`

## Dependencies

- `streamlit`: Interactive web application framework.
- `PyPDF2`: Library for working with PDF files.
- `langchain`: Custom language processing module (provided in the repository).
- `dotenv`: Loading environment variables.
- `gdown`: Downloading files from Google Drive.
- `requests`: Making HTTP requests to fetch webpage content.
- `BeautifulSoup`: Parsing HTML content.

## Configuration

Make sure to set your API keys and other configuration parameters in the `.env` file before running the application.



