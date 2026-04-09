---
name: web-extractor
description: Extract and summarize content from any webpage URL including title, headings, metadata, and main text.
---

# Universal Web Extractor

## Instructions

Call the `run_js` tool with:

- data: A JSON string with:
  - url: The full webpage URL to extract content from.

Use this skill whenever the user provides a URL or asks to summarize or extract content from a webpage.

The script will:
- Fetch the webpage (using a CORS-safe proxy)
- Extract title, meta description, headings, and main text
- Return structured content for summarization