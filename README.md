# 📚Python-Document-Preparation-and-Extraction

Scripts for reliable and scalable data preparation and extraction from unstructured documents (e.g., PDFs). Learn to build pipelines for text and table parsing, transforming complex documents into high-quality, structured datasets for product use cases.

This repository hosts a set of practical Python scripts and Jupyter notebooks focused on Document Data Engineering. The core goal is to provide reliable, scalable workflows for data preparation and extraction from unstructured document formats, primarily PDFs.

These labs are essential for software engineers and data scientists looking to feed high-quality, structured data into AI/ML models, RAG systems, or business intelligence pipelines.

##

### 🚀 Key Features

The key features of document data preparation and extraction pipeline, particularly for use in Python AI labs, are centered on converting complex, unstructured data (like PDFs) into clean, structured data suitable for machine learning models.


✨ <b>Data preparation</b> 
These features ensure the extracted data is clean, accurate, and optimized for AI tasks.

- <b>Optical Character Recognition (OCR):</b>  The capability to convert scanned images or image-only PDFs into machine-readable text layers. This is non-negotiable for handling older or non-digital documents.

- <b>Noise Reduction & Cleaning:</b>  Automated scripts to remove irrelevant elements like headers, footers, watermarks, page numbers, and repetitive boilerplate text, thus isolating the core content.

- <b>Text Normalization:</b>  Standardizing whitespace, resolving character encoding issues, and correcting common OCR errors (e.g., confusing 'l' and '1') to maintain high data consistency.

- <b>Data Validation:</b>  Implementing rules to check the extracted values (e.g., ensuring a "Date" field is in the correct format or a "Total" field is a numerical value) to guarantee accuracy.

- <b>Chunking and Segmentation:</b>  Dividing the clean text into smaller, meaningful pieces (chunks) based on semantic boundaries (sections, paragraphs). This is crucial for RAG (Retrieval-Augmented Generation) systems and effective LLM processing.

<br></br>

✨ <b>Extraction</b>

- <b>Robust PDF Parsing:</b> Efficiently handles complex layouts, multi-page documents, and various encoding issues using industry-standard libraries.

- <b>Text Extraction:</b> Focuses on clean, ordered text extraction, minimizing garbage characters and header/footer noise.

- <b>Tabular Data Extraction:</b> Specialized workflows to accurately detect and extract structured tables from within documents.

- <b>Data Preparation:</b> Includes scripts for cleaning, chunking, and formatting extracted data for vector databases and language models.

- <b>Tooling:</b> Demonstrates effective use of powerful libraries like `pymupdf` <b>(FitZ)/</b> and `pdplumber`.

##

### 🔬 Core Extraction Tools Used

| Library | Primary Use Case |
| :--- | :--- |
| **`pymupdf`** |	High-speed, robust text and image extraction from PDFs. |
| **`pdplumber`** |	Accurate detection and extraction of tabular data from PDF files. |
| **`pydf2`** |	General PDF manipulation (merging, splitting pages). |
| **`pandas`** |	Data structuring, cleaning, and preparation of extracted tables. |


##

### Task (src files) Python - Colab Notebooks
 - <b>Python & Goolgle Colab</b>
   - <i>Review the `Cleaning Mortgage Loan Data` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/cleaning_mortgage_loan_data.ipynb)
     - <i>Data `bank_loan.csv`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/bank_loan.csv)
     
   - <i>Review the `Work with JSON Data` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Work_with_JSON_Data.ipynb)
     - <i>Data `sample.json`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/sample.json)
   
   - <i>Review the `Perform text Cleaning and Standardization` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Perform_Text_Cleaning_and_Standardization.ipynb)
     - <i>Data `text_sample.txt`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/text_sample.txt)
   
   - <i>Review the `Enhanced A Scanned Document Using Pre-processing` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Enhance_a_Scanned_Document_Using_PreProcessing.ipynb)
     - <i>Data `noisy_image_sample.jpg`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/noisy_image_sample.jpg)
 
##

 - <b>Python Data Extraction</b>
   - <i>Review the `Python Libraries for Data Extraction` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Task_Python_Libraries_for_Data_Extraction.ipynb)
     - <i>Data `sample_title_report.pdf`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/sample_title_report.pdf)

   - <i>Review the `Resume Parser with PyMuPDF` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Task_Resume_Parser_with_PyMuPDF.ipynb)
     - <i>Data `sample_resume.pdf`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/sample_resume.pdf)

   - <i>Review the `Extract and Structure Data from Mortgage PDFs` code:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/src/Task_Extract_and_Structure_Data_from_Mortgage_PDFs.ipynb)
        - <i>Data `LenderFeesWorksheetNew`:</i> [HERE](https://github.com/LashawnFofung/Python-Document-Preparation-and-Extraction/blob/main/data/LenderFeesWorksheetNew.pdf)
 
       


 ##
 
 - <b>Optimizing OCR</b>
   - <i>Review the `add file name`:</i> [HERE](link url)
     - <i>Data `add data filename`:</i> [HERE](URL)

 ##
 
 - <b>Implementing RAG</b> 

##


 - <b>Optimizing RAG Pipelines</b>

##

 - <b>Blob Processing & Classification</b>

 ##
 
 - <b>Interactive Chatbot</b>

 ##
 
 - <b>AI-Powered Document Automation Platform</b>
