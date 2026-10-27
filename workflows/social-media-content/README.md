# Social Media Content

Turns one idea typed into a chat into platform-ready posts for Instagram and LinkedIn, with a generated image, and logs everything.

## How it works

1. Chat trigger takes the topic and validates it
2. Google Gemini writes a variation for each platform
3. Leonardo AI generates an image
4. Posts are prepared per platform (publishing is simulated)
5. Each post is logged to Google Sheets, with error handling for the model response

## Built with

Chat trigger, Google Gemini, Leonardo AI (HTTP), Google Sheets

## Set it up

1. In n8n, open **Workflows → Import from file** and choose `workflow.json`.
2. Connect your own credentials: Gemini API key, Leonardo AI key, Google Sheets OAuth.
3. Replace the example email addresses and sheet IDs with yours.
4. Run it once with test data, then activate it.
