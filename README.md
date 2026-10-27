# Invoice Data Extraction

An n8n workflow concept for extracting structured invoice fields from PDF documents and storing results for review.

## Setup
1. Import the workflow JSON once added to this repository.
2. Configure the input trigger, extraction model/API, and destination data table.
3. Verify dates, supplier names, totals, and currencies against sample invoices.
4. Add a human review step for low-confidence results.

## Security
Use synthetic invoices in demos and never commit real financial documents or credentials. End-to-end testing is not confirmed.

## Project status
This README documents the project scope and setup expectations. The workflow export must be present in the repository before it can be imported; validate the finished workflow in your own n8n instance before relying on it.

<img width="721" height="223" alt="image" src="https://github.com/user-attachments/assets/0c4fa823-3c60-4063-b668-b879796ca54c" />
