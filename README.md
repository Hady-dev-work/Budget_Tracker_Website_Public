*Code available upon request (private for academic integrity).*
# Budget Tracker Website
A website for tracking purchases, visualizing purchase data, and setting and viewing budget goals

Developed from scratch with a full-stack web development process, secure login, backend, and clean front-end design.

## Collaborators

* Hady Kotifani, kotif004@umn.edu
* Nicholas Soto, soto0056@umn.edu
* Tyler Chan, chen7751@umn.edu
* Connor Holm, holm0850@umn.edu
* Jiatan Julia Huang, huan2460@umn.edu

## Overview
* Created Multiple web pages to record purchases and manage budget goals

## Tech Stack
- **Frontend:** React (Single Page Application with React Router), Tailwind CSS, amCharts
- **Backend:** Azure Serverless Functions (Node.js runtime)
- **Database:** Azure Cosmos DB (MongoDB)
- **Authentication:** Azure Active Directory Authentication (For login and account management)
- **Relevant Concepts:** Progressive Web App development, mobile-first principles, routing, cloud-based data processing, and user authentication
- **Device Integrations:** Device Camera
- **Other**: *Postman* for testing routing and ensuring that the proper HTTP request method is returned
- **Hosting:** Azure Cloud Platform

## Features


### User Access & Authentication
- Splash page displayed for non-logged-in users  
- Create an account or log in using Azure Authentication with their Google, git, or username and password login options
- Logged-in users are redirected to their personalized dashboard  
- Non-logged-in users cannot access budget features  

### Dashboard
- Displays monthly budget overview, including total budget, amount spent, remaining balance, and days left in the month  
- Provides insights such as whether the user is on track with their budget goals  
- Shows a chart visualizing spending statistics for the current month  
- Lists recent transactions for quick reference  
- Includes a pie chart summarizing spending by category  

### Budget Planning
- Set a monthly income and savings target to automatically calculate a monthly budget  
- View projected savings over 1, 2, and 3 years based on the current savings goal  
- Save or discard a generated budget plan  
- Create and delete custom spending categories  

### Transactions
- Add new transactions with fields for name, amount, category, and date  
- Edit or delete existing transactions  
- View all transactions in chronological order  
- Filter transactions by category  
- View total expenses for filtered transactions  

### Receipt Scanning
- Upload and scan receipts using the device camera or photo library
- Integrate Microsoft Azure AI for receipt image parsing
- Automatically extract details for the purchase items' names and cost

### Analytics & Summaries
- Interactive pie chart showing category-based spending for the current month  
- Advanced summary page featuring a bar graph of monthly expenses over time  
- Yearly spending summaries for long-term analysis
- Use of amCharts for data visualization

### Progressive Web App (PWA)
- Can be downloaded and launched as a standalone web app on desktop or mobile devices  
- Implemented for mobile-first responsiveness for mobile interface considerations

### Hosting & Infrastructure
- Fully deployed on **Microsoft Azure** using serverless backend functions and Cosmos DB (MongoDB mode)  

## Website Images

### **Figure 1**: Splashpage
![Screenshot 2024-05-06 004536](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/c2ac2299-39b5-45c3-aaff-68a66d155b64)

![Screenshot 2024-05-06 004559](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/9908223a-4ebd-4b64-b003-c35f0d22eafa)
*Splash page for new users who are not logged in*

---

### **Figure 2**: Empty Dashboard
![Screenshot 2024-05-06 004708](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/227e901e-4565-4f57-916b-d060bb82ec7c)
*Empty Dashboard for a new user*

---

### **Figure 3**: Set Budget Goals
![Screenshot 2024-05-06 004752](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/15f60f21-be1f-4ef1-a2f4-11c71c8d4084)
*Set up a budget based on monthly income and expected savings*

---

### **Figure 4**: Create Categories to Sort Transactions
![Screenshot 2024-05-06 021528](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/a905d4d2-5933-429b-9fa4-66ca5103f943)
*Create and delete categories for sorting transactions*

---

### **Figure 5**: Specify and Record Transaction Details
![Screenshot 2024-05-06 021953](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/9adc5d4a-e8fc-4269-9590-33fbcc413a88)
*Create and customize transaction details*

---

### **Figure 6**: View All Transactions
![Screenshot 2024-05-06 021844](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/ae02c253-4d85-4356-9abb-77eb0ab689d8)
*See a list of all transactions, their totals, and sort them by category*

---

### **Figure 7**: Scan Receipts
![Screenshot 2024-05-06 022405](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/e6de4ced-5458-48d9-89eb-76fc539feeb4)
*Scan Receipts to capture transaction details*

---

### **Figure 8**: Edit Transaction Details
![Screenshot 2024-05-06 022020](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/a92ebd06-392e-4f73-8de9-dd67f01f04a3)
*Edit transaction details after adding or scanning them*

---

### **Figure 9**: Informative Dashboard
![Screenshot 2024-05-06 022150](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/0355e12e-81e6-440d-876c-99e494f8f1c3)
*A fully lived-in dashboard, showing your most recent transactions, budget progress, and a glance at summaries!*

---

### **Figure 10**: Spending Summaries
![Screenshot 2024-05-06 023012](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/b7b36210-ccda-4597-8185-3b33370bf378)
*See advanced data summary on monthly or yearly transactions*

---

### **Figure 11**: Add to Home Screen
![screenshot_2024-05-05_at_10 04 27___pm_720](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/b329cffb-8f2e-441f-a4ae-83347c270d2e)
*Download the Web App to Desktop*

---

### **Figure 12**: Look at Web App
![Screenshot 2024-05-06 023638](https://github.com/csci5117s24/project-2-html-heroes-2/assets/123435208/92f0e711-caa1-40d9-a6fc-5e9d4a820f7b)
*Web App in its own personalized window*

---

## External Dependencies

**Document integrations with 3rd Party code or services here. (e.g., React, Azure serverless functions, Azure nosql).**

* Library or service name: description of use
* [Azure AI Document Intelligence](https://azure.microsoft.com/en-us/products/ai-services/ai-document-intelligence): used to scan receipt for information.
* Tailwind CSS
