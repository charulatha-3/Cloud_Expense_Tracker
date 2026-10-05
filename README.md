# ☁️ CloudSpend – Cloud-Based Expense Tracker

**CloudSpend** is a simple and user-friendly cloud-based expense tracking application that helps users manage their income, expenses, transactions, and spending categories from a single dashboard.

## 📌 About the Project

CloudSpend provides a centralized platform for recording and monitoring personal financial transactions.

Users can add income and expenses, categorize transactions, search records, edit or delete transactions, and view their overall financial balance.

The current version is a **frontend prototype** using browser LocalStorage. The application can later be connected to AWS cloud services for authentication, database storage, APIs, and cloud hosting.

## ✨ Features

* 💰 Current balance calculation
* 📥 Income tracking
* 📤 Expense tracking
* ➕ Add transactions
* ✏️ Edit transactions
* 🗑️ Delete transactions
* 🔍 Search transactions
* 🏷️ Expense categorization
* 📊 Category-wise expense analysis
* 📅 Transaction date tracking
* 📱 Responsive user interface
* 💾 LocalStorage-based prototype
* ☁️ Cloud-ready architecture

## 📂 Expense Categories

CloudSpend currently supports:

* 🍔 Food
* 🚕 Travel
* 🎓 Education
* 🛒 Shopping
* 💡 Bills
* 📌 Other

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Prototype Storage

* Browser LocalStorage

### Planned Cloud Technologies

* Amazon Cognito
* AWS Lambda
* Amazon API Gateway
* Amazon DynamoDB
* AWS Amplify

## ☁️ Proposed Cloud Architecture

```text
                    USER
                      │
                      ▼
             ┌─────────────────┐
             │  CloudSpend Web │
             │  HTML/CSS/JS    │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Amazon Cognito  │
             │ Authentication  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │   API Gateway   │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │   AWS Lambda    │
             │  Backend Logic  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │    DynamoDB     │
             │ Transaction Data│
             └─────────────────┘
```

## 🔄 Application Workflow

```text
Login
  ↓
Dashboard
  ↓
Add Income / Expense
  ↓
Select Category
  ↓
Save Transaction
  ↓
Calculate Balance
  ↓
Update Dashboard
  ↓
View Spending Analysis
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cloudspend.git
```

### 2. Open the project

Open the `CloudSpend` folder in **Visual Studio Code**.

### 3. Run the application

Open `index.html` using:

* VS Code Live Server
* Google Chrome
* Microsoft Edge
* Any modern web browser

## 📂 Project Structure

```text
CloudSpend/
│
├── index.html
└── README.md
```

## 💾 Data Storage

The current prototype uses **Browser LocalStorage** to save transaction data.

This allows transactions to remain available after refreshing the browser on the same device.

For a production cloud application, LocalStorage can be replaced with **Amazon DynamoDB**.

## 🔮 Future Enhancements

* ☁️ AWS cloud database integration
* 🔐 Amazon Cognito user authentication
* 🗄️ DynamoDB transaction storage
* ⚡ AWS Lambda backend
* 🌐 API Gateway integration
* 📊 Interactive expense charts
* 📅 Monthly and yearly reports
* 📥 Export transactions as CSV
* 📄 Generate PDF financial reports
* 🔔 Budget limit notifications
* 🎯 Monthly spending goals
* 📱 Progressive Web App support
* ☁️ Cloud synchronization across devices

## 🎯 Project Objective

The objective of CloudSpend is to develop a simple financial management application while demonstrating concepts of **web development, data management, cloud computing, serverless architecture, and financial data visualization**.

## 🎓 Academic Use

This project can be used as a **CSE mini project** to demonstrate:

* Frontend development
* JavaScript programming
* CRUD operations
* Client-side data storage
* Cloud computing concepts
* Serverless architecture
* Database management
* Responsive web design

## 👩‍💻 Developed By

**Charulatha S**

B.E. Computer Science Engineering
Prathyusha Engineering College

## 📄 License

This project is created for **educational and academic purposes**.
