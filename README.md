# Note Summarizer

A simple, interactive web-based tool for summarizing notes into concise, exam-friendly markdown-format outputs. Paste your notes, click "Summarize," and receive a formatted summary with headings, bullet points, tables, and more. Export your summary as PDF or Markdown.

## Features

- **Paste & Summarize:** Enter large blocks of text and generate a structured summary in markdown style.
- **Clean Interface:** Minimal, user-friendly design for distraction-free usage.
- **Markdown Formatting:** Summaries include headings, bullet points, tables, horizontal rules, and emphasis for quick revision.
- **Collapsible Sections:** Headings become collapsible for tidier, more navigable summaries.
- **Export Options:** Download your summary as a PDF or Markdown file for offline use.
- **Spinner Feedback:** Visual loading indicator while summaries are generated.

## How It Works

1. Paste your text into the textarea.
2. Click the **Summarize** button.
3. The app calls the DeepSeek summarizer API to generate a markdown-style summary.
4. The formatted summary appears below, with collapsible sections for easy navigation.
5. Export your summary to PDF or Markdown as needed.

## Usage

1. Open `index.html` in your browser.
2. Paste the notes or content you wish to summarize.
3. Click **Summarize**.
4. Wait for the summary to appear.
5. Use the provided buttons to export your summary.

> **Note:** You need to provide your own API key for OpenRouter/DeepSeek in the script section.

## Technologies Used

- HTML, CSS, JavaScript
- [jsPDF](https://github.com/parallax/jsPDF) for PDF export
- [html2canvas](https://github.com/niklasvh/html2canvas) for rendering HTML to canvas/PDF
- DeepSeek via [OpenRouter API](https://openrouter.ai/)
- No frameworks required

## API Setup

Replace the placeholder in the fetch headers:

```js
"Authorization": "Bearer //Api key from openrouter"
```

with your actual [OpenRouter API key](https://openrouter.ai/keys).

---
