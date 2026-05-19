# Privacy Policy for Schedula Invoice Automation

**Last Updated:** May 19, 2026

## Overview

Schedula Invoice Automation is a browser extension used to upload an SMS billing CSV and trigger Zoho invoice draft creation for Schedula billing operations.

## Information We Collect

### 1. User-Provided Billing Inputs
- **Month and year**: Entered by the user to identify the billing period.
- **Optional IVR number**: Entered only when the user wants to run a single-IVR draft.
- **GST toggle selection**: Indicates whether the user wants GST-enabled or GST-disabled draft generation.

### 2. File Data
- **SMS CSV file**: Selected manually by the user and uploaded to our backend for billing calculation.
- The CSV may contain billing-related records such as virtual numbers and SMS pricing data needed for invoice generation.

### 3. Operational Request Data
- **Draft generation request data**: Month, year, optional IVR number, and GST mode are sent to our backend to run invoice drafting.
- **Backend response data**: Success, failure, and issue details are returned to the extension and shown to the user.

## How We Use Your Information

- Upload the SMS billing CSV needed for invoice calculations.
- Trigger batch or single-IVR Zoho draft generation.
- Apply the user-selected GST mode during invoice creation.
- Display upload and draft results back to the user.

## Data Storage

### Local Browser Storage
- The extension does not currently persist invoice or CSV records in browser storage as part of its main workflow.
- Data is used within the active extension session.

### Remote Processing
- Requests are sent to the Schedula Invoice Automation backend hosted on Railway.
- Uploaded CSV content is processed by the backend to calculate SMS usage and prepare invoice drafts.
- The backend may temporarily or operationally store uploaded CSV files and generated draft-processing data as required for service functionality.

## Data Sharing

We do NOT:
- Sell personal or business data.
- Share uploaded billing data for advertising.
- Use collected data for unrelated profiling.

We DO share data with:
- **Schedula Invoice Automation backend service** hosted on Railway, solely to provide upload and invoice-drafting functionality.
- **Zoho Books**, only as needed to create invoice drafts requested by the user.

## Third-Party Services

- **Railway**: Hosting provider for the backend service.
- **Zoho Books**: Used to create invoice drafts.

## Permissions Explained

- **tabs**: Required to open the full invoice automation console in a new browser tab from the extension popup.
- **host permissions**: Required to communicate with the backend API used for CSV upload and invoice draft generation.

## Data Retention

- Extension-side usage is session-oriented.
- Any backend-side retention is limited to operational, billing, and support needs.

## User Control

Users control all actions through explicit interaction in the extension:
- choosing the billing month and year
- selecting the CSV file
- optionally entering an IVR number
- choosing GST On or GST Off
- clicking the run button

Users can stop all processing by closing or uninstalling the extension.

## Security

- API communication is performed over HTTPS.
- Data processing is limited to the invoice automation workflow.

## Changes to This Policy

This policy may be updated periodically. The "Last Updated" date will reflect the most recent revision.

## Contact

For privacy questions or data requests, contact Pearl Thoughts support.
