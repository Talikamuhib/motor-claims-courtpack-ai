# Court Pack Analyst (MVP)

An AI-powered prototype for automating motor insurance court pack analysis. This project extracts structured claim data from complex, unstructured legal documents and provides explainable insights to support faster and more accurate decision-making.

The system is designed as a lightweight MVP aligned with real-world insurance workflows. It focuses on practical automation, auditability, and scalability rather than heavy model complexity.

## Key Features

- Upload court pack PDFs through a simple Streamlit interface  
- Extract structured claim fields such as accident date, hire duration, vehicle registration, and cost details  
- Provide page-level evidence and confidence scores for each extracted field  
- Detect timeline and cost inconsistencies using rule-based validation  
- Generate risk and fraud indicators for early triage  
- Export results as JSON and CSV for downstream processing  

## Why This Matters

Motor insurance claims involve large, unstructured court bundles that require significant manual effort to review. This prototype demonstrates how document AI can reduce turnaround time, improve consistency, and support compliance-ready workflows with transparent decision support.

## Tech Stack

- Python  
- Streamlit  
- PyMuPDF  
- Pydantic  
- Pandas  

## Getting Started

Install dependencies:

```bash
pip install -r requirements.txt

#to run app

streamlit run app.py
