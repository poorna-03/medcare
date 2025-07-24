# MedCare – AI-Driven Chronic Disease Treatment Workflow (n8n)

**MedCare** is an automated, no-code AI system built with **n8n** to assist in diagnosing and recommending treatment plans for chronic diseases, tailored to the Indian healthcare context.

The system collects patient data via a form and uses LangChain AI agents to interpret symptoms. It then calls a sub-workflow (`medcaresub`) that fetches verified treatment details from a Google Sheet. A diagnosis summary is generated using Gemini AI and sent to the patient’s email.

### Core Components:
- n8n form trigger for patient data intake
- Code and AI nodes for reasoning and formatting
- Sub-workflow integration with Google Sheets
- Email delivery of personalized diagnosis

This project was developed during the **Agentic AI Bootcamp** and demonstrates the potential of agentic workflows for accessible, affordable healthcare automation.

### Files:
- `medcare.json` – Main workflow
- `medcaresub.json` – Sub-workflow
- Google Sheet – Verified medical dataset

### License:
MIT License

For questions or collaboration, contact: 
poorna7708@gmail.com
https://www.linkedin.com/in/poorna-devi-m-snsinstitutions/
