# AI-Powered Text Summarizer

## Overview

AI-Powered Text Summarizer is a web application that generates concise summaries from long-form text using the T5 Transformer model. The application provides a simple and interactive interface where users can enter lengthy content and receive a summarized version instantly.

## Features

* Transformer-based text summarization using T5
* FastAPI backend for efficient API handling
* Interactive web interface built with HTML, CSS, and JavaScript
* Text preprocessing and tokenization
* Real-time summary generation

## Tech Stack

* Python
* FastAPI
* PyTorch
* Hugging Face Transformers
* HTML
* CSS
* JavaScript
* Git & GitHub

## Project Structure

TextSummarizer/
├── app.py
├── templates/
│   └── index.html
├── saved_summary_model/
└── README.md

## How to Run

1. Clone the repository

git clone https://github.com/gyan-2812/TextSummarizer.git

2. Navigate to the project directory

cd TextSummarizer

3. Install dependencies

pip install fastapi uvicorn transformers torch sentencepiece jinja2

4. Start the application

uvicorn app:app --reload

5. Open in browser

http://127.0.0.1:8000

##screenshots

### Home Page

<img width="1473" height="735" alt="image" src="https://github.com/user-attachments/assets/127f248b-8249-47c6-a884-c1a8ca02964b" />


### Summary Generation
<img width="1443" height="731" alt="image" src="https://github.com/user-attachments/assets/af8fc0eb-5fce-4463-9866-4b536d8ec6b6" />



## Future Improvements

* Deploy the application on a cloud platform
* Support multiple summarization models
* Add file and document upload functionality
* Improve summary quality with fine-tuned models

## Author

Gyanprakash Dwivedi

GitHub: https://github.com/gyan-2812
