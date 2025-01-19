# Gen-AI-Resume-Analyzer
Resume Parser with GPT and PDF Extraction
This project is a Python-based automated system for parsing resumes and extracting key information using GPT-3.5-Turbo and PDFPlumber. The extracted data is saved in a tabular format in an Excel file, making it easier to review and analyze multiple resumes at once.

### Features
PDF Text Extraction: Extracts text from PDF resumes using pdfplumber.
AI-Powered Parsing: Uses OpenAI's GPT-3.5-Turbo to extract important fields like:
Name
Contact Details
University
Year of Study
Course and Discipline
CGPA/Percentage
Key Skills
AI/ML Experience Scores
Gen AI Experience Scores
Total Resume Score
Batch Processing: Supports processing multiple resumes in parallel using ThreadPoolExecutor for better performance.

Excel Output: Saves the parsed data in a tabular format in an Excel file for easy viewing and analysis.

### Workflow
Input: Provide a list of resume files in PDF format.
Processing:
Extracts text from each resume.
Sends the extracted text to OpenAI's GPT model for parsing.
Converts the response into a structured dictionary.

Output: Saves the parsed data as an Excel file with a clean, tabular structure.
