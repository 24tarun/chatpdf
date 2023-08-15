# A PDF CHAT BOT

## Overview

In this project i have implemented a similar version of [ChatPDF](https://www.chatpdf.com/)
The project utilises the LangChain framework to tokenise the PDF files into chunks of embeddable data.
The user can upload a pdf file and ask questions about the contents of the file

## Features

- 1: Uses OpenAI's LLM models.
- 2: Streamlit user interface.
- 3: Costs about $0.003 for each question 

## Installation

- 1. Clone the repository
      ```git clone https://github.com/24tarun/chatpdf.git```
- 2. Once inside the project directory, install the requirements
      ```pip install -r requirements.txt```
## Working

- 1. to start the local streamlit server
      ``` streamlit run app.py```
- 2. Browse or Drop your pdf file, or use sample.pdf
  3. Ask the questions and get answers.
