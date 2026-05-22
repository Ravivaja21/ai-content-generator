# 🤖 AI Content Generator

An automation workflow that generates AI-written blog posts and saves them directly to Google Docs.

## 🔧 Tech Stack
- **n8n** - Workflow automation
- **Google Gemini AI** - Content generation
- **Google Docs API** - Document creation
- **Webhook** - HTTP trigger

## ⚡ How It Works
1. Webhook receives a topic via URL parameter
2. Gemini AI generates a full blog post
3. Google Docs creates a new document
4. Content is inserted into the document automatically

## 🚀 Workflow
`Webhook → Gemini AI → Create Doc → Update Doc`

## 👨‍💻 Built by
Ravi Vaja | AI Automation Developer
