# document-processing-with-azure-ai
A smart document analysis tool built using Microsoft Azure Document Intelligence to extract, classify, and process information from PDFs and images.
# Smart Document Analyzer using Azure Document Intelligence

This project is built using **Microsoft Azure Document Intelligence** to extract, analyze, and process key information from documents such as invoices, resumes, certificates, and more.

It leverages Microsoft’s AI Form Recognizer service to automate document reading, classification, layout detection, and structured data extraction — making it highly useful for educational, administrative, and enterprise applications.

---

## 🚀 Features

- 📄 Analyze layout and structure of scanned documents
- 🗂️ Extract key-value pairs, tables, and handwritten text
- 🔐 Optional redaction of PII using Azure AI and GPT-4o (advanced use case)
- 📤 Upload PDF or image files for processing
- 📊 Display structured results as JSON or in formatted views

---

## 🛠️ Tech Stack

- Microsoft Azure Document Intelligence (Form Recognizer)
- Python (official Azure SDK samples)
- Visual Studio Code + Dev Container / GitHub Codespaces
- JSON for result formatting
- Optional: OpenAI GPT-4o integration for smart summarization/redaction

---

## 📂 Project Structure

azure-ai-document-processing-samples-main/
├── classification/
├── extraction/
├── redaction/
├── LICENSE
├── README.md
└── requirements.txt


Each folder contains a complete working sample:
- **Classification** – Detects and classifies document types.
- **Extraction** – Extracts layout, fields, and tables.
- **Redaction** – Identifies and redacts sensitive info using GPT.

---

## ▶️ How to Run

1. **Clone the repository**
```bash
git clone https://github.com/your-username/smart-document-analyzer.git
cd smart-document-analyzer

2. Set up a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

Install dependencies
pip install -r requirements.txt

Configure Azure Credentials
Set up your Azure Form Recognizer keys and endpoint:
export AZURE_FORM_RECOGNIZER_ENDPOINT="<your_endpoint>"
export AZURE_FORM_RECOGNIZER_KEY="<your_key>"
export AZURE_FORM_RECOGNIZER_ENDPOINT="<your_endpoint>"
export AZURE_FORM_RECOGNIZER_KEY="<your_key>"

Run a sample
python extraction/analyze_document.py --file <path_to_your_document>
🙌 Acknowledgements
Microsoft Azure Document Intelligence

Azure Samples GitHub Repository

---

Let me know if you also want:
- A version with screenshots added
- A version in Hindi-English mixed tone for blog post or explanation  
- Help with `requirements.txt` or `.gitignore`

Once you push this, share the link and I can review it quickly before your June 15 deadline!
