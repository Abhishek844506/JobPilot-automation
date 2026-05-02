# ✈️ JobPilot — AI Job Application Automation Agent

> Paste a job URL + upload your resume → get a complete 
> application package in 60 seconds, delivered to your inbox.

## 🎯 What It Does
JobPilot is an AI automation agent built with n8n that takes 
a job URL and resume, then automatically generates:

- 📄 **Tailored Resume** — bullet points matched to the JD
- ✉️ **Cover Letter** — personalized, sounds human
- 📊 **Profile Match Score** — skills & experience % breakdown
- 🏢 **Company Research** — culture, values, interview questions
- 🎯 **Interview Q&A** — 5 questions with strong answers

Everything gets saved to **Notion** and emailed as a **PDF** 
— fully automatically, no manual steps.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| n8n | Workflow automation |
| Jina.ai | Job description scraper |
| OpenAI GPT-4o-mini | Resume + Cover Letter |
| Groq Llama 3.3 | Research + Interview + Match Score |
| PDFShift | PDF generation |
| Notion API | Database storage |
| Gmail | Email delivery |

---

## 🔄 How It Works

User submits job URL + resume on web form

↓

Webhook triggers n8n workflow

↓

Jina.ai scrapes job description

↓

5 AI tasks run in parallel:

├── Resume Tailor    (OpenAI)

├── Cover Letter     (OpenAI)

├── Interview QnA    (Groq)

├── Company Research (Groq)

└── Profile Match    (Groq)

↓

Results merge → save to Notion

↓

PDF generated → sent to Gmail

## 📸 Screenshots

### n8n Workflow
<img width="1920" height="1080" alt="jobpilot_workflow_n8n" src="https://github.com/user-attachments/assets/adba70e9-51d3-4a0e-a7d0-11b2c9beb87b" />


### Notion Database
<img width="1920" height="1080" alt="notion_database_screenshot" src="https://github.com/user-attachments/assets/cca277be-2a78-49b5-bdb0-97474956ae73" />


### PDF Output
<img width="596" height="437" alt="{2A6EE766-8A57-4B01-9C1D-FCC07AB7621B}" src="https://github.com/user-attachments/assets/5884d3e2-a3cc-40f3-b216-47b47d333830" />
<img width="303" height="389" alt="{DC20644C-3C2D-43C5-8C01-2F0AD5558A1F}" src="https://github.com/user-attachments/assets/deaddef9-9667-47a7-8ac6-0dc7fb5ac4d0" />
<img width="303" height="330" alt="{436B1E2F-5D13-4FD5-A635-EBD2366DE566}" src="https://github.com/user-attachments/assets/9ef4717c-bedc-4c66-bfef-2b936e523939" />
<img width="299" height="390" alt="{8CF5E811-8C25-495E-A64A-0B441E691C92}" src="https://github.com/user-attachments/assets/84d1ac78-50c6-42ad-b743-be313b4fb987" />




## 👨‍💻 Built By

**Abhishek Kumar Nirankari**  
