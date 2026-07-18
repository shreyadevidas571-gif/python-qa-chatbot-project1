# Python Chatbot using Streamlit and Hugging Face 🤖

A simple Question Answering (QA) chatbot built with **Streamlit** and the **Hugging Face Transformers** library. The chatbot answers questions based on a predefined text about Python.

## Features

- Interactive web interface using Streamlit
- Uses the pretrained **DistilBERT** Question Answering model
- Answers questions from a given context
- Fast model loading using Streamlit caching

## Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- DistilBERT (distilbert-base-cased-distilled-squad)

## Project Structure

```
project/
│── app.py
│── requirements.txt
│── README.md
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/python-chatbot.git
cd python-chatbot
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
streamlit run app.py
```

## Code Overview

The application:

- Loads a pretrained DistilBERT Question Answering model.
- Accepts user questions through a Streamlit interface.
- Searches the provided Python notes for the most relevant answer.
- Displays the extracted answer.

## Example

**Context**

```
Python is a high level language.
Python can be understood by everyone.
Python contains variables and functions.
Python is used for web development, data science, and automation.
```

**Question**

```
What is Python used for?
```

**Answer**

```
web development, data science, and automation
```

## Requirements

```
streamlit
transformers
torch
```

or install them using:

```bash
pip install streamlit transformers torch
```

## Future Improvements

- Add support for custom documents.
- Allow users to upload PDF or text files.
- Integrate larger language models.
- Add chat history.
- Deploy on Streamlit Community Cloud.

## License

This project is licensed under the MIT License.
