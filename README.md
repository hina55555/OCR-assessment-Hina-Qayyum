# OCR Data Processing Pipeline

This repository contains a data processing pipeline for handling OCR (Optical Character Recognition) data. The pipeline consists of several steps outlined below:

## Step 1: Data Collection and Understanding

File: `1. Data Collection and Understanding.ipynb`

In this step, the provided specimen files are read using the notebook mentioned above. The purpose is to understand the structure and format of the OCR data.

## Step 2: Data Preprocessing

File: `2. Data Preprocessing.ipynb`

Each file from the OCR data folder is read and the unstructured data is structured using the notebook mentioned above. The latest test results are saved in the "files" folder.

## Step 3: Results Generation

Intermediate files generated in the "files" folder from Step 2 are read one by one, and the final results are stored per file in the "results" folder.

### Notebooks Description:

- **Data Collection and Understanding.ipynb**: This notebook focuses on reading the specimen files provided by in the OCR data folder.
- **Data Preprocessing.ipynb**: Here, each file is read and the unstructured data is structured. The latest test results are saved in the "files" folder.
- **Challenges and Function Definitions**: All the function definitions and challenges encountered during the process are documented within their respective Jupyter notebooks.

Feel free to explore each notebook for detailed implementations and explanations.
