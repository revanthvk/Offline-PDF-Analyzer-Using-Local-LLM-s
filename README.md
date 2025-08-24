# Offline PDF Analyzer

An AI-powered Offline PDF & Document Analyzer developed during my DRDO Internship.  
This project enables intelligent document processing, semantic search, summarization, and question answering without internet dependency, ensuring data privacy and security.

---

## Features
- Multi-format support: PDF, DOC, DOCX  
- OCR support: Extract text from scanned PDFs  
- Smart chunking and ranking of document content  
- LLM-powered question answering with offline models  
- Semantic search using embeddings (SentenceTransformers + ChromaDB)  
- Local storage with SQLite for efficient retrieval  
- Export results to PDF/Word format  
- Completely offline – No cloud dependency  

---

## Tech Stack
- Python  
- Streamlit (for UI)  
- SentenceTransformers (embeddings)  
- ChromaDB (vector database)  
- cTransformers (for running local LLMs)  
- PyPDF2 / pdfplumber / pytesseract (for PDF & OCR handling)  
- SQLite (local data storage)  

---

## Project Structure
Offline-PDF-Analyzer/
│── app/ # Streamlit app files
│── components/ # UI & functional components
│── lib/ # Core logic (embeddings, OCR, LLM integration)
│── data/ # Input documents
│── outputs/ # Exported results (PDF/Word)
│── requirements.txt # Python dependencies
│── README.md # Project documentation

yaml
Copy
Edit

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/offline-pdf-analyzer.git
   cd offline-pdf-analyzer
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app/main.py
Use Cases
Students – Generate questions and summaries from textbooks

Legal sector – Case law and document search

Medical field – Research paper and document analysis

Restaurants – Recipe search and management

Results and Improvements
Achieved faster retrieval compared to existing PDF analyzers

Added OCR and export features missing in many tools

Offline LLM integration ensures security for sensitive data

Project Info
Project Title: Offline PDF Analyzer

Organization: DRDO (Internship Project)

Domain: AI, NLP, Document Analysis

Contributing
Contributions are welcome. Feel free to open issues or submit pull requests.

License
This project is for educational and research purposes (DRDO Internship).

yaml
Copy
Edit

---

Mate, do you also want me to create a **short 2–3 line description** from this README that you can use for the repo’s sidebar (About section on GitHub)?
