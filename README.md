# LexMed

This repository contains the program and output files for the **LexMed** project, developed as part of the Ignite initiative. The project leverages Optical Character Recognition (OCR) technology to scan PDFs without machine-readable characters and convert them into machine-readable text, which is then saved into text files.

## Features
- **OCR Scanning**: The program scans PDFs that do not contain machine-readable text and converts the content into readable text.
- **Text File Output**: The extracted text is saved into separate text files for easy use and processing.
- **Libraries Used**:
  - **pytesseract**: A Python wrapper for Google Tesseract-OCR, used for optical character recognition.
  - **MuPDF**: A lightweight PDF and XPS viewer that is used to parse the content of PDF files.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/LexMed.git
   ```

2. Navigate to the project directory:
   ```bash
   cd LexMed
   ```

3. Install the required libraries:
   ```bash
   pip install pytesseract mupdf
   ```

   Make sure you have Tesseract-OCR installed on your system. You can download it from [here](https://github.com/tesseract-ocr/tesseract) and follow the installation instructions for your operating system.

## Usage

1. Place your PDF files (without machine-readable text) in the project folder or specify the path to the files.
2. Run the Python script to process the PDFs and extract the text:
   ```bash
   python main.py
   ```

3. The output will be saved in text files within the project folder.

## Project Structure

- `main.py`: The main program that scans the PDFs and extracts text.
- `output/`: A directory where the resulting text files are stored.
- `README.md`: This file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Ignite Program**: For providing the opportunity to work on this project.
- **Tesseract-OCR**: For providing the open-source OCR engine used for text extraction.
- **MuPDF**: For the library used to parse PDF files.

```

Feel free to adjust any details as necessary!
