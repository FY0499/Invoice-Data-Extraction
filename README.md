# Invoice Data Extraction

I built and tested this workflow from start to finish.

I built this n8n workflow to extract structured information from PDF invoices and save the results in a data table.

<img width="721" height="223" alt="Invoice Data Extraction workflow demo" src="https://github.com/user-attachments/assets/0c4fa823-3c60-4063-b668-b879796ca54c" />

## How it works

1. The user submits an invoice through a form.
2. The workflow extracts the content from the uploaded PDF.
3. The AI agent processes the extracted text.
4. The Information Extractor organizes the invoice details into structured fields.
5. The results are saved to an n8n Data Table.

## Technologies

n8n, Google Gemini, Information Extractor, PDF extraction, and n8n Data Tables.

## Setup

Import [workflow.json](./workflow.json) into n8n, configure the Gemini credentials and form, and select the Data Table where the extracted invoice information will be stored.
