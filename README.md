

Customer Service Assistant with AI and Automation (n8n + OpenAI)
-
Description
-
This project is a smart and scalable solution for automating customer service using a web form, AI-powered processing (GPT), Google Sheets storage, and email notifications.
 💡 the small businesses, or agencies looking to improve efficiency without relying on paid tools or complex integrations can use this.
 
  -
  
Flow:
-
![Flow](https://github.com/user-attachments/assets/6cac5d79-3f2d-44d7-96f1-d8c919ca6977)

What does this project do?:
-

🔹 Collect information from a custom web form (name, email, and message).

🔹 Use n8n to process and automate the flow.

🔹 Send the user's message to a language model (OpenAI) to generate an intelligent response.

🔹 Save the data in a Google Sheets spreadsheet for further analysis.

🔹 Send email or Telegram notifications with the processed information.

🛠️ Technologies used
-

- HTML/CSS for the form frontend.

- n8n (visual workflow orchestrator).

- OpenAI API for generating smart responses.

- Google Sheets API for storing data.

- SMTP / Telegram API for automatic notifications.

- Docker + Docker Compose for local development and portability.
-
🎯 Real-life use cases
-
- ✅ Automated customer service for websites or e-commerce sites.

- ✅ Contact form that responds automatically with AI.

- ✅ Recording of leads or inquiries in spreadsheets.

- ✅ Internal notifications to the sales or support team.

- ✅ Automation of responses to surveys or requests.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
⚙️ How to run it locally
-

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Clone the repository

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
git clone https://github.com/youruser/ia-n8n-assistant.git
cd ia-n8n-assistant

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. Launch n8n with Docker
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
docker-compose up -d

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3. Access n8n and configure the workflow

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Open http://localhost:5678

- Import the included workflow (workflow.json)

- Replace your credentials (OpenAI, Gmail, Google Sheets)
---
4. Test the form

---
-Open the index.html file in your browser and send a message.

---
📦 Upcoming improvements
-
---
-🌍 Publish the form on your own domain (Netlify, Vercel).

-💬 Add automatic translation if the message is in another language.

-📊 View statistics from Sheets or Grafana.

-🔐 User authentication for ticket tracking.

---
💼 What can it do?
-
---

- Integrate AI and real automation into business flows.

- Work with real APIs and services used in the industry.

- Solve a specific and common problem: efficient customer service.

- Easily scale to new features or platforms.

Author: [Benjamin] Email: [benjaminmillalonc@gmail.com] LinkedIn: [] Portfolio: [your-site.com]

Thanks for checking out this project! ⭐ If you liked it, give the repo a star or share it.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
