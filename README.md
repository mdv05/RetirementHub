# RetireHub

A financial wellness platform that helps early-career employees start planning for retirement. Employers can publish learning modules, trusted resources and newsletters, and employees get a calculator and an AI coach in one place.

**Live site:** https://retirementhub-d274c.web.app

RetireHub was my team's winning intern project at Segal (summer 2025). The company name and logo on the site are placeholders ("Seagull"), not real branding.

## What's in it
- **Three views:** admin, organization and employee, each with its own content controls
- **Retirement calculator:** links to [FutureScope](https://github.com/mdv05/financial-calculator), a Monte Carlo retirement projection app
- **AI coach:** links to [RetireChat](https://github.com/mdv05/RetirementChat), a Streamlit chatbot on the Gemini API

## Tech
Static HTML, JavaScript and Bootstrap 5, hosted on Firebase. This is a proof of concept: logins are demo accounts and content is saved in the browser's local storage, not a database.

## Deploy
```bash
firebase deploy --only hosting
```
