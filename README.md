# AI Assistant for Personal Data Files

This repository contains an AI-powered assistant for analyzing and answering questions about personal data files, implemented in two different ways.

## Table of Contents

- [Implementations](#implementations)
  - [Jupyter Notebook](#1-jupyter-notebook-implementation)
  - [Python Scripts](#2-python-script-implementation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Implementations

### 1. Jupyter Notebook Implementation

This implementation is contained in `Chatbot_personal_data.ipynb` and uses:

- **Hugging Face** models for natural language processing
- **LangChain** for document processing and question answering
- **Gradio** for the user interface

#### Key Features:
- Uses the `facebook/bart-large-cnn` model for text generation
- Implements document chunking and embedding using `sentence-transformers/all-MiniLM-L6-v2`
- Creates a simple UI with Gradio for file upload and question answering


### 2. Python Script Implementation

This implementation is split across multiple Python files and uses:

- **IBM Watson Machine Learning** and **WatsonxLLM** for language modeling
- **LangChain** for document processing and question answering
- **Flask** for the backend server
- **HTML**, **CSS**, and **JavaScript** for the frontend

#### Key Files:
- `worker.py`: Core logic for document processing and question answering
- `server.py`: Flask server to handle API requests
- Frontend files (HTML, CSS, JS) for the user interface

#### Key Features:
- Uses the `meta-llama/llama-2-70b-chat` model through IBM Watson Machine Learning
- Implements advanced document chunking and retrieval methods
- Provides a web-based interface for file upload and chatting

## Getting Started

1. Clone this repository:
git clone https://github.com/yourusername/ai-assistant-personal-data.git
cd ai-assistant-personal-data

2. Install the required dependencies: pip install -r requirements.txt

3. For the Jupyter notebook implementation:
- Open and run `Chatbot_personal_data.ipynb` in a Jupyter environment

4. For the Python script implementation:
- Set up your IBM Watson Machine Learning credentials
- Run the Flask server:
  ```
  python server.py
  ```
- Open the provided HTML file in a web browser to access the interface

## Usage

1. Upload a PDF document containing personal data
2. Ask questions about the content of the document
3. Receive AI-generated answers based on the document's content

#### Demo
![Demo Screenshot](https://github.com/axiom19/AI-Assistant-for-Personal-Documents/blob/main/demos/demo.png))
[Watch the Demo Video](https://github.com/axiom19/AI-Assistant-for-Personal-Documents/blob/main/demos/Demo%20vid.mov)

## Contributing

Contributions to improve either implementation are welcome. Please feel free to submit issues or pull requests.

This project demonstrates two different approaches to building an AI assistant for personal data analysis, showcasing various technologies and implementation methods.
