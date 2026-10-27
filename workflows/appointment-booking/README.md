# Appointment Booking

Books an appointment from a web request, puts it in the calendar and sends a confirmation and a reminder.

## How it works

1. Webhook receives the booking request
2. Saves the appointment to Google Sheets
3. Creates the Google Calendar event
4. Emails an HTML confirmation
5. Waits until 24 hours before and sends a reminder

## Built with

Webhook, Google Sheets, Google Calendar, Gmail

## Set it up

1. In n8n, open **Workflows → Import from file** and choose `workflow.json`.
2. Connect your own credentials: Google Sheets, Calendar and Gmail OAuth.
3. Replace the example email addresses and sheet IDs with yours.
4. Run it once with test data, then activate it.
