# AI Resume Generator with n8n

An automation workflow built with **n8n** that generates a professional resume using AI. Users fill out a form, the AI creates resume content, the workflow formats it into HTML, converts it to PDF, and send it in your Gmail.



## Features

- 📄 Resume generation using AI
- 📝 Form-based user input
- 🎨 Professional HTML resume template
- 📑 Automatic PDF generation
- 📧 Gmail delivery



## Workflow

```
Form Trigger
      ↓
AI Agent
      ↓
HTML Template
      ↓
PDF.co
      ↓
Gmail
```



## Technologies Used

- n8n
- AI Agent
- PDF.co
- HTML/CSS
- Gmail



## How to Use

1. Import the workflow into n8n.
2. Configure your credentials:
   - AI Provider
   - PDF.co API
   - Gmail (optional)
3. Activate the workflow.
4. Open the form URL.
5. Fill in your information.
6. Submit the form.
7. Receive the generated resume PDF in your Gmail.



## Notes

Credentials and API keys are not included. You must configure your own credentials before running the workflow.



## Author

**Janwin Malinao**