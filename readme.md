# AI-Powered Web Scraper and Summarizer

This project is an **AI-powered web scraper and summarizer** built by Krishna Prasad Khanal. It fetches the contents of a website, processes the text, and provides a concise summary using OpenAI's API. The tool can be used to analyze websites, extract key information, and generate a short, often humorous, summary in Markdown format.

---

## Features

- Fetches website content and links.
- Strips irrelevant HTML elements like scripts, styles, images, and inputs.
- Truncates content for concise processing (up to 2,000 characters).
- Summarizes website content using OpenAI's GPT models (`gpt-4.1-mini`, `gpt-5-nano`).
- Displays output in Markdown for easy readability.
- Handles multiple websites and URLs dynamically.

---

## Requirements

Python >= 3.12

Required Python packages:

- `beautifulsoup4`
- `requests`
- `python-dotenv`
- `openai`
- `ipython`

Install dependencies with Poetry:

```bash
poetry add beautifulsoup4 requests python-dotenv openai ipython

## setub 

-clone repo
(git clone https://github.com/krishnaamen/ai-powered-web-scraper-summerizer.git
cd ai-powered-web-scraper
)
-create .env file  
(OPENAI_API_KEY=your_openai_api_key_here)
-- 
