# Document-Chatbot
It is a Document Chatbot project using Openai, Langchain and Streamlit.
# DocumentGPT - Document ChatBot

DocumentGPT is a simple chatbot developed using Streamlit, OpenAI's GPT-3.5-turbo, and other libraries for document processing. This chatbot allows users to upload documents in PDF format and Docx format, process them, and then engage in a conversation to obtain relevant information from the documents.

## Features

- **Document Processing:** Supports PDF document processing. You can upload one or multiple PDF files.
- **Text Extraction:** Extracts text from PDF files for further processing.
- **Conversational AI:** Engage in a conversation with the chatbot to ask questions about the processed documents.
- **OpenAI Integration:** Utilizes OpenAI's GPT-3.5-turbo for natural language understanding and generation.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pip (Python package installer)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Muhammadzainattiq/Document-Chatbot.git
   cd Document-Chatbot
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

Run the Streamlit app:

```bash
streamlit run document_chatbot.py
```

The app will open in your default web browser, allowing you to interact with the DocumentGPT chatbot.

## How It Works

1. **Upload Documents:** Use the file uploader in the sidebar to upload PDF documents.

2. **Process Documents:** Click the "Process" button to extract text from the uploaded documents and create a conversation chain for OpenAI.

3. **Ask Questions:** Use the chat input box to ask questions about the content of the processed documents.

4. **View Responses:** The chatbot will respond to your questions based on the information extracted from the documents.

## Additional Information

- **OpenAI API Key:** Make sure to add your OpenAI API key in the appropriate place within the code to enable integration with the GPT-3.5-turbo model.

```python
openai_api_key = st.secrets["OPEN_API_KEY"]
```

## Limitations

- The chatbot currently supports PDF document and Docx processing only.
- The quality of responses depends on the content and structure of the processed documents.

## Contributors

- [Muhammad Zain Attiq]
- [Muhammad Haris Tariq]

Feel free to contribute to the project by submitting issues or pull requests.


## Acknowledgments

- Special thanks to OpenAI for providing the GPT-3.5-turbo model.
- Inspired by the capabilities of language models for document processing and conversational AI.
