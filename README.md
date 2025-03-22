# Jordan Tax Service & JoFotara Integration

This repository contains code/documentation/tools related to integrating with **Jordan Tax Service** and the **JoFotara** national electronic invoicing system in Jordan. Below, you'll find an explanation of these entities and how they are used.

## Table of Contents
- [What is JoFotara?](#what-is-jofotara)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

---

## What is JoFotara?

**JoFotara** is Jordan's national electronic invoicing system, launched by the **Income and Sales Tax Department (ISTD)** in collaboration with the **Ministry of Digital Economy and Entrepreneurship (MDEE)**. It aims to:
- Enhance transparency in sales and purchase transactions.
- Streamline tax data collection for the ISTD.
- Modernize Jordan’s tax infrastructure by digitizing invoicing processes.

### Key Features of JoFotara
- **Electronic Invoice Submission**: Businesses submit invoices via the JoFotara portal or integrated systems.
- **QR Code Verification**: After submission, the ISTD generates a QR code to be included on invoices, ensuring they are tax-compliant and verified.
- **Compliance**: Mandatory for Business-to-Government (B2G) transactions since May 2024; encouraged for all businesses to improve accountability.
- **Phase 2 Implementation**: Starting April 1, 2025, all goods and services transactions will require tax-compliant e-invoices for tax deductions.

JoFotara addresses Jordan’s previous lack of a unified invoicing system, simplifying tax reporting and reducing fraudulent practices.

---

## Usage

This project provides tools/code to integrate with the JoFotara system, enabling businesses to:
1. **Generate Electronic Invoices**: Create invoices that comply with ISTD regulations.
2. **Submit to JoFotara**: Send invoices to the JoFotara platform via API or manual upload.
3. **Retrieve QR Codes**: Include ISTD-generated QR codes in invoices for verification.
4. **Ensure Compliance**: Meet Jordan’s evolving e-invoicing mandates (e.g., Phase 2 starting April 2025).

### Example Use Case
A Jordanian business can use this tool to:
- Automate invoice creation in their ERP system.
- Connect to JoFotara via API to submit invoices.
- Receive and embed QR codes in customer invoices, ensuring tax compliance.

### Prerequisites
- A registered account with the JoFotara portal (required by May 2024 for B2G compliance).
- API credentials or access to the JoFotara system (if applicable).
- Basic understanding of Jordan’s tax regulations.

---

