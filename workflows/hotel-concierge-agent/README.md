# Hotel Concierge Agent

An email assistant for a hotel that answers guest questions from the hotel's own documents and keeps billing records.

## How it works

1. Gmail trigger picks up guest emails
2. A Gemini-powered agent answers using a Pinecone knowledge base
3. Documents dropped into a Google Drive folder are split, embedded and added to the knowledge base automatically
4. A second agent records billing details to Google Sheets
5. Replies to the guest in the same thread

## Built with

Gmail, Google Gemini (chat and embeddings), Pinecone, Google Drive, Google Sheets

## Set it up

1. In n8n, open **Workflows → Import from file** and choose `workflow.json`.
2. Connect your own credentials: Gmail and Drive OAuth, Gemini API key, Pinecone API key.
3. Replace the example email addresses and sheet IDs with yours.
4. Run it once with test data, then activate it.
