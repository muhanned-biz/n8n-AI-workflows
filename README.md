# n8n AI Workflows

AI automation and agentic workflows built in n8n by Muhanned Thengat.

| Workflow | Description |
| --- | --- |
| [AI Personal Assistant (Telegram)](telegram-ai-assistant) | Telegram-based AI agent that sends and reads Gmail, looks up Google Contacts, and creates Google Calendar events from plain-language messages, asking for clarification when a request is unclear. |
| [LinkedIn Content Creator](linkedin-content-creator) | Pulls a topic from Google Sheets, researches it with Tavily web search, writes a LinkedIn post with an AI agent, and generates the next topic so the content queue refills itself. |
| [RAG Pipeline & Chatbot](rag-pipeline-chatbot) | Watches a Google Drive folder, splits and embeds new documents into Pinecone, and serves a chatbot that answers questions from that knowledge base. |
| [AI Customer Support Email Agent](customer-support-email-agent) | Monitors Gmail, classifies incoming emails with AI, and replies to support questions using answers retrieved from a Pinecone knowledge base. |
| [Voice Email Agent](voice-email-agent) | Webhook-triggered agent that turns voice instructions into finished emails, finding recipients in a Google Sheets contact list and sending through Gmail. |
| [Invoice Data Extractor](invoice-data-extractor) | Detects new PDF invoices in Google Drive, extracts company, invoice number, dates and total amount with AI, and logs them to Google Sheets. |
| [Web Scraper with Firecrawl](firecrawl-web-scraper) | Extracts structured data from websites using Firecrawl's AI extraction API, polling until results are ready and saving them to Google Sheets. |

All API keys and personal details have been removed. Connect your own credentials after importing.
