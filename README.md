# Local Search Engine with C++

Welcome to the Local Search Engine repository! This project is a simple search engine implemented in C++ that allows you to perform keyword-based searches on a local collection of text documents. This README file will guide you through the repository and help you understand the project's structure and usage.

## Introduction

The Local Search Engine is designed to provide a fast and efficient way to search for specific keywords within a collection of text documents. It utilizes the concept of an inverted index to index the documents and enable quick retrieval of relevant documents based on the search query.

## Features

The Local Search Engine comes with the following features:

- **Inverted Index**: The search engine builds an inverted index from the text documents, allowing for efficient keyword-based searches.
- **TF-IDF Ranking**: The engine uses the TF-IDF (Term Frequency-Inverse Document Frequency) ranking algorithm to determine the relevance of documents to a given query.
- **Command-Line Interface**: The search engine provides a simple command-line interface for interacting with the application.

## Installation

To install and run the Local Search Engine, follow these steps:

1. Clone the repository
2. Change the directory
3. Compile the source files:
g++ -std=c++11 -o search_engine main.cpp Document.cpp Index.cpp QueryProcessor.cpp

4. Run the executable:
./search_engine

## Usage

Once you have the search engine running, you can use the command-line interface to perform searches. The following commands are available:

- **index**: This command indexes a collection of text documents. You need to provide the path to the directory containing the documents. Example:
index /path/to/documents

- **search**: This command performs a search based on the provided query. Example:
search keyword1 keyword2 ...


- **quit**: This command exits the search engine application.

## Contributing

Contributions to the Local Search Engine are always welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the repo.

When contributing, please ensure that you follow the existing code style and conventions, and provide clear commit messages and documentation.

## License

The Local Search Engine is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for both commercial and non-commercial purposes. However, make sure to include the original license file in any copies or modifications of the project.


