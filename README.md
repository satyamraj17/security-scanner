AI-powered securtity scanner built with Python and the Google Gemini API. It analyzes source code for common security vulnerabilities such as SQL injection, hardcoded credentials, and weak cryptographic practices. The scanner prompts the AI to identify each issue, classify its severity, explain its impact, and recommend a secure code fix. To improve readability, the results are displayed in the terminal with color-coded severity levels using Colorama.

# NOTE
Add your Google Gemini API key in a file name `.env`
`GOOGLE_API_KEY=<YOUR_API_KEY>`