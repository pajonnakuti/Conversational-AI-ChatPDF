# Conversational-AI-ChatPDF

## Overview

Conversational-AI-ChatPDF is an advanced conversational AI tool that leverages LangChain and Llama-2 models to provide intelligent and interactive conversations with PDF documents. This project enables users to interact with PDF content using natural language queries, extracting and summarizing information effectively.

## Features

- **Natural Language Processing**: Utilize LangChain and Llama-2 models for understanding and responding to natural language queries.
- **PDF Interaction**: Extract, summarize, and interact with PDF document content seamlessly.
- **Conversational Interface**: Engage in intelligent conversations with the PDF content, asking questions and receiving relevant answers.
- **Extensibility**: Easily extend the functionality to support additional document formats and NLP models.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Conversational-AI-ChatPDF.git
    cd Conversational-AI-ChatPDF
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare Your PDF**:
    - Place the PDF documents you want to interact with in the `pdfs` directory.

2. **Run the Application**:
    ```bash
    python main.py
    ```

3. **Interact with the PDF**:
    - Use the conversational interface to ask questions and get responses based on the PDF content.

## Configuration

Configure the application settings in `config.py`:

- **Model Configuration**:
    - Set up the LangChain and Llama-2 model parameters.
    
- **PDF Directory**:
    - Specify the directory path where PDF files are stored.

## Example

Here is a simple example of how to use Conversational-AI-ChatPDF:

1. **Ask a Question**:
    - "What is the main conclusion of the document?"

2. **Get a Response**:
    - The system will process the PDF content and provide an accurate response based on the context.

## Contributing

We welcome contributions to improve Conversational-AI-ChatPDF! Here are some ways you can contribute:

- **Bug Reports & Feature Requests**: If you encounter bugs or have feature requests, please open an issue.
- **Pull Requests**: If you'd like to contribute code, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **LangChain**: For providing the natural language processing framework.
- **Llama-2**: For the advanced language models.
- **Contributors**: Thanks to all the contributors who have helped improve this project.

## Contact

For any questions or inquiries, please contact [your-email@example.com].

