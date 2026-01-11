# n8n-AI-Content-Automation-Workflow
This project is an end-to-end content automation workflow built with n8n. It automatically transforms topics stored in a spreadsheet into refined, trend-based content using HTTP requests and an AI agent.  The workflow is designed to reduce manual research and content creation by leveraging automation, APIs, and AI.
⚙️ How the Workflow Works

Input Source

Topics are read from a Google Sheet (or any connected spreadsheet).

Trending Content Search

An HTTP Request node searches for trending articles related to each topic.

Content Generation

Based on the retrieved articles, the workflow generates three draft contents.

AI Refinement

An AI Agent merges the three drafts into one cohesive, refined, and high-quality content piece.

Output

The final content is automatically updated back into the spreadsheet.

🧠 Key Features

Fully automated content pipeline

Real-time trend-based research

AI-powered content merging and refinement

Spreadsheet-driven input and output

Scalable and reusable workflow

🛠️ Tools & Technologies

n8n – Workflow automation

HTTP Request – Fetch trending articles

AI Agent (LLM) – Content merging and refinement

Google Sheets – Data input and output

🚀 Use Cases

Blog content automation

Social media post generation

SEO-focused content research

Marketing content workflows

AI-assisted writing pipelines

🔧 Setup Instructions

Clone this repository

Import the workflow.json file into your n8n instance

Configure:

Google Sheets credentials

HTTP request parameters

AI agent / LLM credentials

Run the workflow and monitor outputs in the spreadsheet

📈 Future Improvements

Add keyword scoring and ranking

Support multiple content formats (blog, LinkedIn, X)

Add scheduling and publishing automation

Improve prompt engineering for AI refinement

👤 Author

Muhammad Yunusa Badamasi
Data Scientist | Automation Engineer | AI Enthusiast
