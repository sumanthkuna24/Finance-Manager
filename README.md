# Personal Finance Manager & Budget Tracker

A Laravel MVC-based web application that helps users manage personal finances efficiently by tracking income, expenses, budgets, savings, and financial accounts. The platform provides user-specific reports, charts, and insights to support better financial planning and spending management.

---

## 📌 Project Overview

The Personal Finance Manager & Budget Tracker is designed to simplify personal financial management through a centralized digital platform.

Users can:

* Register and manage their accounts
* Add and manage finance accounts (bank accounts, savings accounts, wallets)
* Track income and expenses
* Create category-based budgets
* Monitor account balances and net savings
* Analyze spending habits through reports and charts
* Receive budget warnings and financial insights

Administrators can:

* Manage categories
* Monitor platform activity
* Verify finance accounts
* Access administrative analytics

---

## 🚀 Features

### User Management

* User Registration
* User Login & Logout
* Session-Based Authentication
* Role-Based Access (User/Admin)

### Finance Account Management

* Add Finance Accounts
* Update Account Details
* Account Verification
* Track Account Balances
* Net Savings Calculation

### Transaction Management

* Add Income Transactions
* Add Expense Transactions
* Edit Transactions
* Delete Transactions
* Automatic Account Balance Synchronization

### Budget Management

* Create Monthly Budgets
* Category-Based Budgets
* Budget Progress Tracking
* Overspending Alerts

### Reports & Analytics

* Monthly Income Summary
* Monthly Expense Summary
* Category-Wise Expense Analysis
* Savings Overview
* Dynamic Charts & Graphs
* User-Specific Reports

### Dashboard

* Monthly Income
* Monthly Expenses
* Net Savings
* Budget Status
* Recent Transactions
* Financial Insights

---

## 🏗️ Technology Stack

### Frontend

* HTML5
* CSS3
* Bootstrap 5
* JavaScript
* Blade Templates
* Chart.js

### Backend

* PHP
* Laravel MVC Framework
* Eloquent ORM

### Database

* MySQL

### Development Tools

* Visual Studio Code
* Composer
* Git & GitHub
* XAMPP / Laragon

---

## 📂 Project Modules

### 1. Authentication Module

* Registration
* Login
* Logout
* Session Management

### 2. Finance Accounts Module

* Account Creation
* Account Verification
* Balance Tracking

### 3. Categories Module

* Income Categories
* Expense Categories

### 4. Transactions Module

* Income Tracking
* Expense Tracking
* Account Balance Updates

### 5. Budget Module

* Monthly Budgets
* Spending Analysis
* Budget Warnings

### 6. Reports Module

* Financial Reports
* Expense Analysis
* Dynamic Charts

### 7. Admin Module

* User Monitoring
* Category Management
* Account Verification
* Administrative Analytics

---

## 🗄️ Database Schema

### Users

* id
* name
* email
* password
* role

### Finance Accounts

* id
* user_id
* bank_name
* account_type
* balance
* status

### Categories

* id
* category_name
* type

### Transactions

* id
* user_id
* finance_account_id
* category_id
* type
* amount
* description
* transaction_date

### Budgets

* id
* user_id
* category_id
* budget_amount
* month
* year

---

## 🔄 Application Flow

1. User registers and logs in.
2. User adds finance accounts.
3. Admin verifies accounts.
4. User records income and expense transactions.
5. Account balances update automatically.
6. User creates category-wise budgets.
7. System tracks spending against budgets.
8. Reports and charts are generated dynamically.
9. Dashboard displays financial insights and savings overview.

---

## 📊 Graphs & Reports

Graphs are generated using **Chart.js**.

Flow:

Database → Controller → Data Processing → Blade View → Chart.js → Graph Display

Available Visualizations:

* Expense Distribution Chart
* Income vs Expense Analysis
* Category-Wise Expense Reports
* Financial Summary Insights

---

## 🔐 Authentication

The project uses **Session-Based Authentication**.

After successful login:

* User ID is stored in session
* User Role is stored in session

This allows role-based access and user-specific data filtering.

---

## 🎯 MVC Architecture

### Model

Handles database operations and Eloquent relationships.

### View

Displays data using Blade templates and Bootstrap UI.

### Controller

Processes requests, validates data, interacts with models, and returns views.

### Request Flow

User Action → Route → Controller → Validation → Model → Database → View → Response

---

## 📈 Future Enhancements

* Email Notifications
* Mobile Application
* AI-Based Financial Suggestions
* Export Reports (PDF/Excel)
* Multi-Currency Support
* Advanced Financial Analytics

---

## 👨‍💻 Developed For

MVC Programming Course Project

Personal Finance Manager & Budget Tracker

Built using Laravel MVC Architecture.
