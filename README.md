# Automation Workflows

Ready-to-import n8n workflows for small businesses: lead qualification, lead capture and follow-up, reactivation of cold leads, appointment booking, social media content and an AI concierge.

Each workflow sits in its own folder with a `workflow.json` you can import and a README that explains what it does and what it needs.

| Workflow | What it does |
| --- | --- |
| [Lead Qualification Agent](workflows/lead-qualification-agent/) | Reads new enquiries from a Gmail inbox, decides whether each lead is hot, warm or cold, replies in the right tone and logs the lead to Google Sheets. |
| [Lead Capture, CRM and Follow-up](workflows/lead-capture-follow-up/) | Takes a form submission from a website, stores it, confirms it to the lead, alerts the owner and follows up automatically. |
| [Lead Reactivation](workflows/lead-reactivation/) | Re-engages old or cold leads with an email and two WhatsApp messages, and keeps the record up to date. |
| [Appointment Booking](workflows/appointment-booking/) | Books an appointment from a web request, puts it in the calendar and sends a confirmation and a reminder. |
| [Social Media Content](workflows/social-media-content/) | Turns one idea typed into a chat into platform-ready posts for Instagram and LinkedIn, with a generated image, and logs everything. |
| [Hotel Concierge Agent](workflows/hotel-concierge-agent/) | An email assistant for a hotel that answers guest questions from the hotel's own documents and keeps billing records. |

## Using a workflow

1. In n8n, go to **Workflows → Import from file** and pick the folder's `workflow.json`.
2. Add your own credentials (the exports contain no keys).
3. Swap the example addresses, sheet IDs and prompts for your own.
4. Test with sample data, then activate.

## About

Built by [Shripaad Koduri](https://shripaads-agency.vercel.app), who builds websites, web apps and AI automations for businesses. Email shripaad17@gmail.com.

Licensed under the terms in [LICENSE](LICENSE).
