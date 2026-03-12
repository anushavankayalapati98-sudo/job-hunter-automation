# job-hunter-automation
Automated LinkedIn job hunting workflow built with n8n for Business Analyst roles in Singapore


# LinkedIn Job Hunter Automation

An automated job hunting workflow built using **n8n** that scrapes 
LinkedIn job postings, matches them to a resume using AI, 
and sends email notifications for relevant opportunities.

## What It Does

- Runs on a **scheduled trigger** automatically
- Downloads and extracts resume from Google Drive (PDF)
- Fetches live job postings from **LinkedIn** based on keywords
- Uses **AI Agent + Google Gemini** to match jobs to resume
- Logs matched jobs into **Google Sheets**
- Sends **Gmail notifications** for matching jobs
- Loops through all jobs automatically

## Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation platform |
| Google Gemini AI | Resume-to-job matching using AI |
| LinkedIn | Job data source |
| Google Drive | Resume storage |
| Google Sheets | Job tracking database |
| Gmail | Email notifications |
| JavaScript | Custom logic & data processing |

## Workflow Screenshot

![Workflow](screenshot.png)

##  How to Set It Up

1. Install n8n (https://n8n.io)
2. Import `workflow.json` into your n8n instance
3. Connect your credentials:
   - Google Drive
   - Google Sheets
   - Gmail
   - LinkedIn
   - Google Gemini API
4. Update the Google Sheet with your job search keywords
5. Run the workflow!

##  Search Configuration

| Field | Value |
|-------|-------|
| Keyword | Business Analyst |
| Location | Singapore |
| Experience Level | Entry-Level, Associate, Mid-Level |



## Built By

**Anusha Vankayalapati**  
Business Analyst | IT Service Delivery | Singapore  
anushavankayalapati98@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/vankayalapati-anusha/)

---
 If you find this useful, please star the repository!
<img width="451" height="696" alt="image" src="https://github.com/user-attachments/assets/4dc2ee00-b2a0-4c26-a2b0-20ddff5d2ba5" />
