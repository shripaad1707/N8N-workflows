# Lead Capture, CRM and Follow-up

Takes a form submission from a website, stores it, confirms it to the lead, alerts the owner and follows up automatically.

## How it works

1. Webhook receives the form submission
2. Validates the fields and logs errors
3. Appends the lead to Google Sheets
4. Emails a confirmation to the lead and a notification to the owner
5. Sends follow-up #1, waits 3 days, sends follow-up #2 and tags the lead in the sheet

## Built with

Webhook, Google Sheets, Email (SMTP), Wait

## Set it up

1. In n8n, open **Workflows → Import from file** and choose `workflow.json`.
2. Connect your own credentials: Google Sheets OAuth, SMTP account.
3. Replace the example email addresses and sheet IDs with yours.
4. Run it once with test data, then activate it.
