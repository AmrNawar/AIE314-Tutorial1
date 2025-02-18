# AIE314-Tutorial1
# Document Processing and Question Answering Project

## Project Description

This project focuses on processing various document types (PDF, Word, PowerPoint) and extracting their textual content. It utilizes libraries like `spire` for document parsing and `transformers` for question answering. The extracted text is normalized into a JSON format for easy handling and analysis. Additionally, web scraping functionalities are included to retrieve data from external sources.

## Team Members

*   **Amr Nawar** (ID: 20100243)
*   **Mahmoud Enany** (ID: 20100)

## Project Structure

The project code is organized in a Google Colab notebook. It includes the following key components:

*   **Document Extraction:** Functions to extract text from PDF, Word, and PowerPoint files using `spire` library.
*   **Web Scraping:** Code to scrape data from websites using `requests` and `beautifulsoup4`.
*   **Data Preprocessing:** Function `preprocess_document` to handle different file types and extract their content along with metadata.
*   **JSON Normalization:** Function `normalize_to_json` to structure the extracted data into a JSON format.
*   **Question Answering:** Implementation of a question-answering pipeline using the `transformers` library.

## Usage

To use this project, simply run the code cells in the Google Colab notebook. The notebook will install the necessary libraries, process the input documents, and extract the relevant information. You can then use the extracted data for further analysis or use the question-answering pipeline to ask questions about the content.
