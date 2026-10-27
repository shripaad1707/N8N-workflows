# Lead Reactivation

Re-engages old or cold leads with an email and two WhatsApp messages, and keeps the record up to date.

## How it works

1. Webhook receives the lead to reactivate
2. Validates inputs and creates an Airtable record
3. Sends a reactivation email and a first WhatsApp message
4. Waits 2 days, sends a second WhatsApp message and updates the record

## Built with

Webhook, Email (SMTP), WhatsApp via HTTP API, Airtable

## Set it up

1. In n8n, open **Workflows → Import from file** and choose `workflow.json`.
2. Connect your own credentials: SMTP account, WhatsApp API token, Airtable token.
3. Replace the example email addresses and sheet IDs with yours.
4. Run it once with test data, then activate it.
