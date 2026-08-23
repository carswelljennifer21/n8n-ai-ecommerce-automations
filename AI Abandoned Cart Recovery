# 🛒 AI Abandoned Cart Recovery

An AI-powered abandoned cart recovery automation built with **n8n, Google Sheets, Ollama AI, and Gmail** that identifies abandoned carts, generates personalized recovery emails, and automatically sends them to customers.

## 🎯 Project Overview

eCommerce businesses often lose potential sales when customers add products to their cart but leave without completing their purchase.

This automation helps address that problem by automatically checking cart records, identifying abandoned carts, using AI to generate a personalized recovery email, and sending the message to the customer.

## 🚨 The Problem

Abandoned carts can result in missed sales opportunities.

Without an automated recovery process:

* Businesses have to manually identify abandoned carts
* Customer follow-ups can be missed
* Teams spend time writing repetitive emails
* Customers may forget about products left in their carts
* Potential sales opportunities can be lost

## 💡 The Solution

This n8n workflow automates the abandoned cart recovery process.

The automation:

1. Runs automatically on a scheduled trigger.
2. Retrieves cart records from Google Sheets.
3. Checks whether the cart status is `Abandoned`.
4. Passes the customer and product information to an AI Agent.
5. Generates a short and personalized recovery email.
6. Sends the email to the customer through Gmail.

## 🔧 Workflow

```text
Schedule Trigger
       ↓
Google Sheets
       ↓
Check Cart Status
       ↓
IF — Abandoned?
       ↓ TRUE
AI Agent
       ↓
Generate Recovery Email
       ↓
Gmail
       ↓
Customer
```

## 🛠️ Technologies Used

* **n8n** — Workflow automation platform
* **Google Sheets** — Stores abandoned cart information
* **Ollama AI** — Generates personalized recovery email content
* **Gmail** — Sends recovery emails to customers

## 📋 Data Used

The workflow uses customer and cart information such as:

* Customer name
* Customer email
* Product name
* Cart value
* Cart status

The AI is instructed to use the provided information without inventing product features, discounts, promotions, or other details.

## ✉️ Example Recovery Email

```text
Subject: Complete Your Purchase

Hi John,

We noticed you left the Bluetooth Speaker in your cart for ₱1,999. If you're still interested, please return to your cart to complete your purchase.

Best regards,
Customer Support
```

## 📊 Example Scenario

A customer adds a product to their cart but does not complete the purchase.

The cart record contains:

```text
Customer: John
Product: Bluetooth Speaker
Cart Value: ₱1,999
Status: Abandoned
```

The workflow processes the record:

```text
Abandoned Cart
       ↓
AI Generates Personalized Email
       ↓
Gmail Sends Recovery Email
       ↓
Customer Receives Follow-Up
```

## 📈 Benefits

This automation can help businesses:

* Recover potential lost sales
* Automate abandoned cart follow-ups
* Reduce repetitive administrative work
* Create personalized customer communication
* Improve follow-up consistency
* Save customer support time
* Scale customer outreach

## 🔐 Security

**Never upload credentials or sensitive information to GitHub.**

Do not include:

* API keys
* OAuth tokens
* Passwords
* n8n credentials
* Private customer information
* Private Google Sheets URLs or data
* Other sensitive authentication information

Before uploading an n8n workflow JSON file, remove or replace credentials and sensitive information.

## 🚀 Possible Improvements

Future versions could include:

* Multiple recovery email stages
* Customer purchase tracking
* Automatic follow-up scheduling
* Cart recovery analytics
* CRM integration
* Shopify integration
* Klaviyo integration
* Customer segmentation
* Recovery conversion tracking
* Human approval before sending emails

## 📌 Project Status

**Completed — Demo / Portfolio Version**

This workflow demonstrates an AI-powered abandoned cart recovery process built with n8n.

The project is designed as a portfolio demonstration of AI automation, eCommerce operations, personalized email automation, and workflow-based customer engagement.

## 👤 Author

**Jennifer**

AI Automation & n8n Workflow Developer

### Skills Demonstrated

`n8n` `AI Automation` `Workflow Automation` `Ollama` `Google Sheets` `Gmail` `eCommerce Automation` `Email Automation` `Customer Engagement` `Process Automation`
