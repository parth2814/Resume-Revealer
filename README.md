# hackathon-project

# Resume Data Extraction

## Overview

This repository contains Python code for extracting relevant information from resumes, such as skills and occupations, using external datasets stored in Excel files. The code utilizes regular expressions to search for specific patterns within the resume text and matches them against entries in the datasets. Additionally, it employs other libraries for extracting text from various file formats and performing optical character recognition (OCR) on images.

## Features

- **Parser Functionality:** Parses the extracted text to identify and extract relevant sections such as personal information, education, technical skills, experience details, and achievements.
- **Skill Extraction:** Extracts skills from the resume text using both regular expressions and a dataset.
- **Occupation Extraction:** Extracts occupations from the resume text using a dataset.
- **Support for Various File Formats:** Supports extraction from PDF, DOCX, DOC, and image files.
- **Customization:** Allows customization of datasets for skills and occupations.

## Dependencies

- Python 3.x
- Pandas
- PyMuPDF (fitz)
- pytesseract
- docx
- BeautifulSoup (bs4)

## Usage

1. **Clone the Repository:**
    git clone https://github.com/parth2814/resume-data-extraction.git
    cd resume-data-extraction
   
2. **Install Dependencies:**
   
   To install the required dependencies, run the following command:
  ```bash
  pip install -r requirements.txt
  ```


## Execute the Code

1. **Open the Jupyter Notebook:** Navigate to the directory where the Jupyter Notebook file (`hackathon_project.ipynb`) is located.

2. **Launch Jupyter Notebook:**
   - If you have Jupyter Notebook installed, run the following command in your terminal or command prompt:
     ```
     jupyter notebook
     ```
   - If you have JupyterLab installed, you can also use it by running:
     ```
     jupyter lab
     ```

3. **Open the Notebook:** Once Jupyter Notebook or JupyterLab is launched, navigate to the notebook file (`hackathon_project.ipynb`) and open it.

4. **Execute the Cells:** Execute the cells in the notebook to run the code. You can do this by clicking on the "Run" button in the toolbar or by using keyboard shortcuts (e.g., Shift + Enter).

5. **Follow Instructions:** Follow any instructions provided in the notebook to input data, adjust parameters, or customize the code as needed.

6. **View Output:** After executing the code cells, view the output within the notebook or save/export the output as required.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.



