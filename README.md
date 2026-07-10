# AI-Powered Lead Generation System

## Project Overview

The AI-Powered Lead Generation System is a Salesforce CRM application designed to help organizations manage, analyze, and prioritize customer leads efficiently. The application leverages Salesforce automation and Einstein Prompt Builder to provide AI-generated lead summaries, enabling sales teams to make informed decisions and improve customer engagement.

This project demonstrates the use of Salesforce custom objects, Lightning applications, automation using Flows, AI-powered summaries, reports, dashboards, and role-based security.

---

## Objectives

- Manage customer leads efficiently.
- Generate AI-powered lead summaries.
- Organize customer interactions.
- Track website visits and follow-up activities.
- Improve lead prioritization using AI predictions.
- Provide reports and dashboards for business insights.

---

## Technologies Used

- Salesforce Developer Edition
- Salesforce Lightning Experience
- Salesforce DX
- VS Code
- Salesforce CLI
- Einstein Prompt Builder
- Flow Builder
- Reports & Dashboards
- Git & GitHub

---

## Features

- AI Lead Management
- AI-generated Lead Summary using Einstein Prompt Builder
- AI Prediction Management
- Conversation Tracking
- Website Visit Tracking
- Follow-up Management
- CSV Data Import
- Record Triggered Flow Automation
- Reports and Dashboards
- Role-based User Access

---

# Application Workflow

1. User logs into Salesforce.
2. Opens the AI-Powered Lead Generation System application.
3. Creates or imports AI Leads.
4. AI Summary is generated using Einstein Prompt Builder.
5. AI Prediction record is created for lead evaluation.
6. Sales team records customer conversations.
7. Website visit information is maintained.
8. Follow-up tasks are created.
9. Reports and Dashboards display lead analytics.

---

# Custom Objects

## AI Leads

Stores customer lead information.

### Sample Fields

- AI Lead Name
- Email
- Phone
- Company
- Industry
- Lead Category
- Qualification Status
- Product Interest
- AI Summary

---

## AI Predictions

Stores lead prediction information.

### Fields

- AI Prediction Name
- Lead Score
- Prediction Date
- Prediction Result
- Recommendation

---

## Conversations

Stores customer communication details.

### Example Fields

- Conversation Name
- Channel
- Status
- Notes

---

## Website Visits

Stores customer website activity.

### Example Fields

- Visit Name
- Page Visited
- Duration
- Visit Date

---

## Follow-Ups

Stores follow-up activities.

### Example Fields

- Follow-Up Name
- Due Date
- Status
- Assigned User

---

# AI Features

This project uses Salesforce Einstein Prompt Builder to generate AI-powered summaries for customer leads.

The AI Summary helps sales representatives understand customer information quickly and prioritize interactions.

The AI Prediction object stores lead score, prediction result, and recommendations for decision-making.

---

# Automation

Record Triggered Flow

When a new AI Lead is created:

- Flow executes automatically.
- AI Summary can be generated.
- Notifications can be sent.
- Validation rules ensure correct data.

---

# Reports

The application includes reports such as:

- Total AI Leads
- Leads by Qualification Status
- Leads by Industry
- Leads by Category
- AI Prediction Summary
- Website Visit Summary
- Follow-Up Summary

---

# Dashboard

The dashboard provides:

- Total AI Leads
- Qualified vs Unqualified Leads
- Lead Categories
- Industry Distribution
- AI Prediction Summary
- Follow-Up Status

---

# User Roles

## System Administrator

- Manages users
- Configures application
- Imports data
- Manages security
- Creates reports and dashboards

---

## AI Lead Manager

- Creates AI Leads
- Imports Lead data
- Reviews AI Summary
- Creates AI Predictions
- Assigns follow-ups

---

## Sales Agent

- Views assigned leads
- Reviews AI Summary
- Contacts customers
- Updates conversations
- Updates follow-up records

---

# Security

The application uses:

- Profiles
- Roles
- Object Permissions
- Sharing Rules

to provide secure access to business data.

---

# Sample Workflow

Customer Information

↓

Create AI Lead

↓

Generate AI Summary

↓

Create AI Prediction

↓

Contact Customer

↓

Record Conversation

↓

Track Website Visit

↓

Schedule Follow-Up

↓

Monitor Dashboard

---

# Folder Structure

```
force-app/
│
├── applications
├── classes
├── flexipages
├── flows
├── layouts
├── lwc
├── objects
├── permissionsets
├── profiles
├── reports
├── dashboards
├── staticresources
├── tabs
├── triggers
```

---

# Deployment

1. Clone the repository.

```
git clone https://github.com/pardhu-2412/AI-Powered-Lead-Generation-System.git
```

2. Authorize Salesforce Org.

```
sf org login web
```

3. Deploy source.

```
sf project deploy start
```

4. Import sample CSV files.

5. Open the AI-Powered Lead Generation System application.

---

# Future Enhancements

- Automatic AI Lead Scoring using Einstein Lead Scoring
- Agentforce Integration
- Email Automation
- SMS Notifications
- Web-to-Lead Integration
- External AI Integration (OpenAI/Gemini)
- Predictive Analytics
- Mobile Optimization

---

# Repository

GitHub Repository:

https://github.com/pardhu-2412/AI-Powered-Lead-Generation-System

---

- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/)
- [Salesforce CLI Plugin Development Guide](https://developer.salesforce.com/docs/platform/salesforce-cli-plugin/guide/conceptual-overview.html)
- [Salesforce VS Code Extensions Documentation](https://developer.salesforce.com/tools/vscode/)

