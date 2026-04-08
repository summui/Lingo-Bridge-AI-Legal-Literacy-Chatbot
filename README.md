\# Lingo Bridge: AI Legal Literacy ChatBot



> \*Demystifying the law in 60 seconds.\*



Lingo Bridge is an AI-powered assistant designed to bridge the gap between complex legal jargon and everyday understanding. Built on n8n, this tool transforms dense legal documents into plain, actionable English, helping non-legal professionals identify risks and understand their obligations.



&#x20;\*\*UN SDG 16 — Peace, Justice and Strong Institutions\*\*.



\---



\## 🚀 Features



\- \*\*Legal Jargon Simplification:\*\* Automatically translates "legalese" into simple, easy-to-understand language.

\- \*\*Red Flag Detection:\*\* Identifies and flags concerning clauses, unusual terms, or potential legal traps.

\- \*\*Visual Document Analysis:\*\* Uses advanced vision capabilities to analyze images of physical legal documents — no scanner needed.

\- \*\*Contextual Memory:\*\* Features a conversation buffer that remembers the last 10 interactions, allowing for detailed follow-up questions.

\- \*\*Actionable Insights:\*\* Provides clear summaries of deadlines, key obligations, and important provisions.



\---



\## 🛠️ Tech Stack



| Layer | Tool |

|---|---|

| Workflow Automation | n8n |

| AI Model | Google Gemini 1.5 Pro |

| Framework | LangChain (via n8n nodes) |

| Memory Management | Window Buffer Memory (10-turn limit) |



\---



\## 📋 Prerequisites



To deploy this workflow, you will need:



\- An active n8n instance (Desktop, Cloud, or Self-hosted)

\- A Google Gemini API Key from \[Google AI Studio]

\- The `Lingo Bridge-AI Legal Literacy ChatBot.json` workflow file



\---



\## 🔧 Setup Instructions



\### 1. Import Workflow

\- Open your n8n canvas

\- Click the menu → select \*\*Import from File\*\*

\- Select the `Lingo Bridge-AI Legal Literacy ChatBot.json` file



\### 2. Configure AI Credentials

\- Locate and open the node named \*\*Gemini 1.5 Pro\*\*

\- In the \*"Credential for Google Gemini(PaLM) API"\* section, select \*\*Create New Credential\*\*

\- Paste your API Key and save



\### 3. Deploy \& Test

\- Ensure the \*\*On Chat Message\*\* node is active

\- Use the built-in n8n chat interface to upload a document image and begin the analysis



\---



\## ⚡ Quick Start for Judges



1\. Import the JSON file into your n8n instance

2\. Open the "Gemini 1.5 Pro" node

3\. Add your Google Gemini API key (free at https://aistudio.google.com/apikey)

4\. Click Activate → Start chatting



Total setup time: \~2 minutes



\---



\## 🤖 Model Compatibility Note



This project was built and tested using \*\*Google Gemini 1.5 Pro\*\*.



If `gemini-1.5-pro` is unavailable in your region or on your account, the following models will work the same way and produce equivalent results:



| Model | Notes |

|---|---|

| `gemini-1.5-flash` | Faster, slightly lighter — recommended alternative |

| `gemini-2.0-flash` | Newer, also works well |

| `gemini-1.5-pro-latest` | Latest stable version of 1.5 Pro |



\*\*To switch models:\*\*

\- Open the \*\*Gemini 1.5 Pro\*\* node in n8n

\- Change the model name in the dropdown or model field

\- Save and re-activate the workflow



\---



\## ⚖️ Disclaimer



This tool is for \*\*educational and informational purposes only\*\*. Lingo Bridge provides AI-generated analysis and does \*\*not\*\* constitute official legal advice. Always consult with a qualified legal professional before signing or agreeing to any binding documents.



\---





