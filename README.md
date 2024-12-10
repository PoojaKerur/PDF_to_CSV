# PDF_to_CSV
This script extracts tabular data from a PDF file, processes it, and exports it as a well-structured CSV file. It handles issues such as merged columns, misaligned data, and missing values.
# Prerequisites
pandas: For handling tabular data.
PyPDF2: For reading PDF files.
re: For advanced string manipulation (used for splitting merged columns).
# Script Features
### Extract Text from PDF:
The script reads all pages of the PDF using PyPDF2 and extracts the text content.
### Data Structuring:
Splits lines into rows and further divides merged columns using predefined delimiters.
### Error Handling:
Gracefully skips unprocessable lines and provides error messages for unexpected issues.
### CSV Output:
Saves the processed data as a CSV file for easy review.
