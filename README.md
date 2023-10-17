# BizCardX-Extracting-Business-Card-Data-with-OCR

# Purpose:
    Automates the process of extracting key details from business card images.

# Technologies Used:
    Streamlit: 
        Provides the user interface for the application.
    EasyOCR: 
        Utilizes Optical Character Recognition (OCR) to extract text from business card images.
    OpenCV:
        Likely used for image processing tasks, such as preprocessing business card images.
    Regex Function:
        Employed for pattern matching and extracting specific information from the OCR results.
    PostgrSQL Database: 
        Stores the extracted information for further analysis.
        
# Functionality:
    Image Input: 
        Users can upload business card images through the application interface.
    Text Extraction:
        EasyOCR is employed to recognize and extract text from the uploaded images.
    Data Processing: 
        Regular expressions are used to identify and extract specific pieces of information, such as name, designation, company, and contact details from the extracted text.
    Database Storage:
        Extracted information is stored in a MySQL database.
    User Interface: 
    Streamlit provides a user-friendly interface for users to interact with the application, upload images, and view extracted data.
    Further Analysis: 
        The stored data can be used for various purposes such as lead generation, customer relationship management, or other business analytics.
