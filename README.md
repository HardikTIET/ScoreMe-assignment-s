📄 Flask PDF to Excel Converter
🌟 Overview
This is a Flask-based web application that allows users to upload a PDF file and converts it into an Excel file while preserving the original structure and layout. The app uses PyMuPDF (fitz) for extracting text and openpyxl for generating Excel files.

✨ Features
✅ Upload a PDF file effortlessly
✅ Extract text while maintaining the format
✅ Export structured data to an Excel file
✅ Download the converted file with a single click

⚡ Installation Guide
Follow these simple steps to set up and run the project on your local machine:

1️⃣ Clone the Repository
sh
Copy
Edit
git clone <repository-url>
cd pdf-to-excel-flask
2️⃣ Create a Virtual Environment
sh
Copy
Edit
python -m venv venv
Activate on macOS/Linux
sh
Copy
Edit
source venv/bin/activate
Activate on Windows
sh
Copy
Edit
venv\Scripts\activate
3️⃣ Install Dependencies
sh
Copy
Edit
pip install -r requirements.txt
🚀 How to Use
1️⃣ Run the Flask App

sh
Copy
Edit
python app.py
2️⃣ Open the Application in Your Browser

sh
Copy
Edit
http://127.0.0.1:5000
3️⃣ Upload a PDF File and let the magic happen! 🎩✨
4️⃣ Download the Converted Excel File 📥

🛠 Tech Stack
🏗 Flask – Web framework
📄 PyMuPDF (fitz) – PDF text extraction
📊 openpyxl – Excel file creation
🚀 Future Enhancements
🔹 Support for tables and images
🔹 Improved layout preservation
🔹 Multi-page PDF handling

