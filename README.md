# slack-installation-workflow
This n8n workflow automatically checks a user's preferred installation date
submitted via a form. If the date is within the next 7 days, it sends a
notification message to a Slack channel.
## Problem
Service-based businesses often miss urgent installation requests
because form submissions are checked manually.
This can lead to delayed responses and poor customer experience.
## Solution
This workflow automates the process by:
- Triggering on form submission
- Checking if the preferred installation date is within 7 days
- Sending an instant Slack alert for urgent installations
- Separating urgent and non-urgent requests automatically
## Workflow Logic
1. User submits a form with email and preferred installation date
2. n8n checks if the installation date is within the next 7 days
3. If YES → send a Slack message to the team
4. If NO → route the data to a separate flow (future follow-up / todo)
## Tools Used
- n8n (Self-hosted)
- Slack
- Form Trigger (n8n)
## Use Cases
- Internet service providers
- Solar panel installation companies
- CCTV and security service providers
- Any business offering scheduled installations
## Disclaimer
This workflow is shared for portfolio and educational purposes.
Credentials and sensitive data are excluded.
