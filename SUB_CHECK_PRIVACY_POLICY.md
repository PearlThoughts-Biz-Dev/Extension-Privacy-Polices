# Privacy Policy for Sub Check

**Last Updated:** April 6, 2026

## Overview

Sub Check is a browser extension that helps email senders verify recipient subscription status in Gmail and Outlook before sending, and insert unsubscribe links when needed.

## Information We Collect

### 1. Recipient Data
- **Recipient email address**: Read from the compose window To field or manually entered by the user.
- **Optional recipient name**: Collected only if the user enters it in the Sub Check panel.

### 2. Extension Usage Data
- **Subscription check request data**: Email address sent to our backend to check subscription status.
- **Person save request data**: Email address and optional name sent only when user clicks save.
- **Unsubscribe token request data**: Email address sent only when user requests link insertion.

## How We Use Your Information

- Determine whether the recipient is subscribed or unsubscribed.
- Optionally save recipient details when explicitly requested by the user.
- Generate an unsubscribe URL and insert it into the email draft when explicitly requested by the user.

## Data Storage

### Local Storage
- The extension does not permanently store recipient records in local extension storage for this feature.
- Data is handled within the active compose session.

### Remote Processing
- Requests are sent to: `https://unsubscribe-feature-production.up.railway.app`
- The backend processes check, save, and token generation requests required for extension functionality.

## Data Sharing

We do NOT:
- Sell personal data.
- Share personal data for advertising.
- Use collected data for unrelated profiling.

We DO share data with:
- **Sub Check backend service** hosted on Railway, solely to provide the extension feature.

## Permissions Explained

- **Gmail/Outlook host permissions**: Required to add the Sub Check interface inside compose windows and read recipient/email body content for user-triggered actions.
- **Backend host permission**: Required to call check/save/token APIs.

## Data Retention

- Extension-side data is transient within the compose flow.
- Any server-side retention is limited to service operation and compliance needs.

## User Control

Users control all actions through explicit button clicks in the Sub Check panel:
- Check
- Save Person & Insert Unsubscribe Link
- Insert Unsubscribe Link

Users can stop all processing by uninstalling the extension.

## Security

- API communication is performed over HTTPS.
- Access to recipient data is limited to extension functionality.

## Changes to This Policy

This policy may be updated periodically. The "Last Updated" date will reflect the most recent revision.

## Contact

For privacy questions or data requests, contact Pearl Thoughts support.
