This project automates the extraction of information from PDF files, transfers the extracted data to a Google Sheet, and sends an email to the address extracted from the PDF files. Below are the details of how the process works and the tools utilized.

## Features

1. **PDF Information Extraction**:
   - Extract data from PDF files using `pdfplumber`.
   - Identify and extract specific information such as names, email addresses, and skills.

2. **Skill Extraction with NER**:
   - Leverage a pre-trained BERT-large model from HuggingFace for Named Entity Recognition (NER).
   - Extract skills or other relevant entities from the text in the PDF.

3. **Google Sheet Integration**:
   - Connect to Google Sheets using `gspread` for seamless integration.
   - Data extracted from the PDFs is converted to a DataFrame using `set_with_dataframe` and then transferred to the linked Google Sheet.

4. **Automated Email Notifications**:
   - Once the data is transferred to the Google Sheet, an email is automatically sent to the email address extracted from the PDF.

5. **Google Drive Authorization**:
   - Google Drive is authorized in Google Colab to ensure proper access and permissions for interacting with Google Sheets.
