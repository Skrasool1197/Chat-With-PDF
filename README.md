
# Chat with PDF: Interactive PDF-based Conversations

This Streamlit application enables users to upload PDF documents and interactively query their content using a powerful AI-based retrieval and question-answering system.

##  Features

- **Multiple Session Management:** Create and manage multiple sessions to keep your work organized.
- **PDF Upload and Processing:** pload one or more PDFs, which are processed for efficient retrieval.
- **Interactive Q&A:** Query your PDFs in natural language and receive precise answers.
- **Conversation History:** View a history of your questions and the model's responses for each session.


## Setup

Clone the repository:
```bash
git clone https://github.com/Skrasool1197/Chat-With-PDF.git
cd Chat-With-PDF
```

Create a virtual environment with python version of 3.11.


Install the required dependencies:
```bash
  pip install -r requirements.txt
```

Run the application:
```bash
streamlit run app.py
```
## API Reference




| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `groq_api_key` | `string` | **Required**. Your API key |
`huggingface_api_key` | `string`| **Required**. Your API key|

 






## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`GROQ_API_KEY`

`HUGGINGFACE_API_KEY`



## Deployment


This project is deployed on Streamlit Cloud, you can access using following url:
 ```bash
      streamlit run app.py
```

