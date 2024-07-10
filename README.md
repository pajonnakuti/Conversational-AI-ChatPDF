# Conversational-AI-ChatPDF

## Overview

Conversational-AI-ChatPDF is a sophisticated AI-based project that integrates multiple cutting-edge technologies to facilitate document processing and conversational capabilities. By leveraging ChromaDB, Gradio, LangChain, and Llama-2 models, this project allows users to interact with PDF documents in a conversational manner.

## Features

- **Natural Language Processing**: Utilize LangChain and Llama-2 models for understanding and responding to natural language queries.
- **PDF Interaction**: Extract, summarize, and interact with PDF document content seamlessly.
- **Conversational Interface**: Engage in intelligent conversations with the PDF content, asking questions and receiving relevant answers.
- **Extensibility**: Easily extend the functionality to support additional document formats and NLP models.
- **Document Processing**: Extract and process data from PDF documents.
- **Conversational AI**: Utilize advanced language models to engage in natural conversations based on the document's content.
- **Web Scraping**: Gather additional context and information from the web to enhance the conversation.
- **User Interface**: Interact with the system using a user-friendly interface powered by Gradio.

## Technologies Used

- **ChromaDB**: A high-performance, columnar database optimized for handling large-scale document data.
- **Gradio**: A Python library that allows you to quickly create user interfaces for machine learning models.
- **LangChain**: A framework designed for building applications with language models.
- **Llama-2 Models**: Advanced language models used for understanding and generating human-like text.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- pip (Python package installer)
- Git

### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/Conversational-AI-ChatPDF.git
    cd Conversational-AI-ChatPDF
    ```

2. **Create a Virtual Environment**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

### Setup

1. **ChromaDB Setup**
   - Follow the instructions for setting up ChromaDB from the [official documentation](https://github.com/chroma-db).

2. **Gradio Setup**
   - Gradio is installed via the requirements file, but you can check out their [documentation](https://gradio.app/docs/) for more customization.

3. **LangChain Setup**
   - Ensure you have access to LangChain models and APIs as per the [LangChain documentation](https://www.langchain.com/docs).

4. **Llama-2 Model Setup**
   - Set up Llama-2 models as per the [official Llama documentation](https://huggingface.co/llama).

### Usage

1. **Run the Application**
    ```bash
    python app.py
    ```

2. **Access the Gradio Interface**
   - Open your web browser and navigate to `http://localhost:7860` to interact with the application.

### Configuration

- **ChromaDB Configuration**: Modify the database connection settings in `config/chroma.yml`.
- **Gradio UI Configuration**: Customize the user interface components in `app.py`.
- **LangChain and Llama-2 Configuration**: Update model parameters and API keys in `config/langchain_llama.yml`.


## Example

Here is a simple example of how to use Conversational-AI-ChatPDF:

1. **Ask a Question**:
    - "What is the main conclusion of the document?"

2. **Get a Response**:
    - The system will process the documents content and provide an accurate response based on the context.

## Contributing

We welcome contributions to improve Conversational-AI-ChatPDF! Here are some ways you can contribute:

- **Bug Reports & Feature Requests**: If you encounter bugs or have feature requests, please open an issue.
- **Pull Requests**: If you'd like to contribute code, please fork the repository and submit a pull request.

Please fork the repository and submit a pull request.

1. **Fork the Project**
2. **Create your Feature Branch**
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. **Commit your Changes**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. **Push to the Branch**
    ```bash
    git push origin feature/AmazingFeature
    ```
5. **Open a Pull Request**

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [ChromaDB](https://github.com/chroma-db)
- [Gradio](https://gradio.app)
- [LangChain](https://www.langchain.com)
- [Llama](https://huggingface.co/llama)

## Contact

For further information, please contact [Pavan Kumar Jonnakuti](mailto:pavankumar.j@incois.gov.in).

