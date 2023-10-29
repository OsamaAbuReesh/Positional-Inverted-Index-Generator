# Positional Inverted Index Generator

## Overview
This Python application generates a positional inverted index from a collection of documents and enables querying of the index for phrase search. The index and document mappings are stored in JSON and CSV formats, respectively.

## Features

- Generates a positional inverted index and stores it in `pos_inverted_index.json`.
- Creates a mapping between the document ids used in the index and the relative paths of the corresponding files in `docId_filePath_mapping.csv`.
- Prompts user to input a phrase query and retrieves the relative paths of all documents containing this query.
- Provides functionality to insert and delete documents, updating the index accordingly.

## Usage Instructions

1. Place all your documents in the designated folder.
2. Run the application.
3. The app will create and store the index as `pos_inverted_index.json` and document mappings in `docId_filePath_mapping.csv`.
4. Use the provided interface to query the index, insert new documents, or delete existing ones.

## Implementation Details

- **Parsing**: The application ignores English stop words and words with a length less than 3 characters during the parsing process.
- **Document Insertion/Deletion**: Users can seamlessly add or remove documents, and the index will be updated in real-time.
- **Code Organization**: Effort has been made to ensure the code is organized, modular, and well-documented to ensure clarity and ease of understanding.

## Feedback and Contribution

Feel free to raise issues, provide feedback, or make pull requests. All contributions are welcome!
