# BizCardX: Business Card Data Extraction with OCR
BizCardX is a Streamlit application designed to simplify the process of extracting relevant information from business cards. The application utilizes easyOCR for Optical Character Recognition, allowing users to upload business card images and extract details such as company name, cardholder name, designation, contact information, and address.

### Features
User-Friendly GUI: Streamlit provides an intuitive graphical user interface for easy interaction.

OCR Integration: Leverages the power of easyOCR for accurate text extraction from business card images.

Database Integration: Allows users to save extracted information along with the uploaded business card image into a database.

CRUD Operations: Enables users to perform CRUD operations (Create, Read, Update, Delete) on the stored business card entries.

### Requirements
Make sure you have the following dependencies installed before running the application:

pip install -r requirements.txt
streamlit: 1.8.0
easyocr: 1.4.1
Pillow: 8.3.2
numpy: 1.21.2
pandas: 1.3.3
opencv-python-headless: 4.5.3.56

### Usage
#### Clone the repository:
git clone https://github.com/your-pallavghoshal/BizCardX.git

#### Navigate to the project directory:
cd BizCardX

#### Install dependencies:
pip install -r requirements.txt

#### Run the application:
streamlit run app.py
The application will be accessible in your web browser at http://localhost:8501.
