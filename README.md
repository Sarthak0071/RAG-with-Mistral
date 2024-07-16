# Advanced Question Answering System

This project implements an advanced question answering system using LangChain, Hugging Face models, and Google's Generative AI. It processes web content, generates embeddings, and uses a retrieval-based approach to answer questions based on the given context.

## Features

- Web content loading and processing
- Text splitting for efficient processing
- Embedding generation using Google's Generative AI
- Similarity search for relevant context retrieval
- Integration with Hugging Face models for text generation
- Quantization configuration for optimized model performance
- Retrieval-based question answering

## Prerequisites

- Python 3.7+
- Pip package manager

## Installation

1. Clone this repository:
2. Install the required packages:
## Usage

1. Set up your Google API key and Hugging Face token as environment variables or through the provided input prompts.

2. Run the main script:

3. Enter your question when prompted.

## Configuration

- Adjust the `chunk_size` and `chunk_overlap` in the `RecursiveCharacterTextSplitter` for different text splitting behavior.
- Modify the `repo_id` in the `HuggingFaceEndpoint` configuration to use a different model.
- Customize the prompt template in `ChatPromptTemplate` to change the system's response style.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

