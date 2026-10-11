# Cargo-Nexus-Main-Workflow-AI-Shipment-Clearance-System
![Cargo Nexus Logo](Cargo%20Nexus%20Project%20logo)
Group 2 TechCrush Capstone Project: An AI-powered container import documentation and port clearance automation system built with n8n, Google Gemini, PostgreSQL, and Freight APIs. Features document extraction, discrepancy detection, human approval, and automated email notifications.
---

## Project Overview

Cargo Nexus is an AI-powered container import documentation
and port clearance automation system developed as part of
the TechCrush Capstone Project – Group 2.

The system uses n8n, Google Gemini AI, PostgreSQL,
webhooks, and email automation to process shipping documents,
identify discrepancies, and support shipment clearance decisions.

## Problem Statement

Manual shipping documentation processes can result in:

- Delays in document verification
- Missing or incomplete shipping documents
- Inconsistent container information
- Repetitive administrative tasks
- Delays in identifying discrepancies

Cargo Nexus aims to reduce these challenges through automation.

## Technologies Used

- n8n – Workflow automation
- Google Gemini AI – Document extraction and AI reporting
- PostgreSQL – Shipment data storage
- Gmail – Notifications and human approval
- Webhooks – Document intake
- JavaScript – Data normalization and discrepancy detection
- HTTP Request – External API integration

## Main Workflow Architecture

1. Receive shipping documents through a webhook.
2. Normalize shipment metadata.
3. Extract information from uploaded documents.
4. Process extracted information using Google Gemini AI.
5. Normalize shipment data.
6. Store shipment records in PostgreSQL.
7. Retrieve shipment documents for comparison.
8. Detect missing information and document discrepancies.
9. Execute the document-processing sub-workflow.
10. Route documents based on comparison results.
11. Request human approval when discrepancies are detected.
12. Update shipment verification status in PostgreSQL.
13. Send automated email notifications.
14. Generate an AI Shipment Readiness Report.

## Key Features

- Automated shipping document intake
- AI-powered document extraction
- Container information normalization
- PostgreSQL database integration
- Document comparison and discrepancy detection
- Human-in-the-loop approval
- Automated email notifications
- AI-generated shipment readiness reports
- Reusable n8n sub-workflow

## Shipping Documents

The project is designed to support:

- Bill of Lading
- Commercial Invoice
- Packing List
- Form M
- Customs Declarations
- Delivery Order
- Container Manifest

## Testing and Results

The workflow has been tested for:

- Shipment data processing
- PostgreSQL record storage and updates
- Document comparison
- Human approval and rejection paths
- Automated email notifications
- AI shipment readiness report generation

The system distinguishes document consistency from
overall shipment clearance readiness.

## Main Workflow

![Main Workflow](Cargo_Nexus_Main_Workflow%20Screenshot.PNG)

## Sub-Workflow

![Sub-Workflow](Screenshot%20for%20Sub-Workflow.PNG)

## Testing Evidence

### Main Workflow Testing

![Main Workflow Testing](Testing%20Evidence%20for%20main%20workflow.PNG)

### Sub-Workflow Testing

![Sub-Workflow Testing](Testing%20Evidence%20For%20sub%20workflow.PNG)

## Project Documentation

[View Project Documentation](Project_Documentation.pdf)

##  Project Team

**Program:** TechCrush Capstone Project

**Group:** Group 2

**Project:** Autonomous Container Import Documentation
and Port Release Engine

## Future Improvements

- Expand support for additional shipping documents
- Improve external maritime API integration
- Enhance automated shipment readiness checks
- Strengthen error handling and retry mechanisms
- Improve reporting and operational monitoring

---

**Cargo Nexus – Smarter Shipping Documentation Through AI Automation.**
