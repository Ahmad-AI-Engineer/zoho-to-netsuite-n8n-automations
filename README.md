# Zoho to NetSuite n8n Automation Suite

This repository contains a set of independent n8n automation workflows for integrating Zoho Billing operations with Oracle NetSuite.

The workflows are designed to automate key finance and billing processes such as invoices, payments, credit memos, and void invoice handling.

## Workflows Included

| Workflow | Description |
|---|---|
| Invoice Automation | Syncs Zoho invoices into NetSuite |
| Payment Automation | Syncs Zoho payment data into NetSuite |
| Credit Memo Automation | Automates Zoho to NetSuite credit memo processing |
| Void Invoice Credit Memo Automation | Handles void invoice scenarios and related credit memo automation |

## Repository Structure

```text
zoho-to-netsuite-n8n-automations/
│
├── workflows/
│   ├── invoice-automation.json
│   ├── payment-automation.json
│   ├── credit-memo-automation.json
│   └── void-invoice-credit-memo-automation.json
│
├── documentation/
│   ├── invoice-automation.md
│   ├── payment-automation.md
│   ├── credit-memo-automation.md
│   └── void-invoice-credit-memo-automation.md
│
├── screenshots/
│   ├── invoice-automation/
│   ├── payment-automation/
│   ├── credit-memo-automation/
│   └── void-invoice-credit-memo-automation/
│
└── README.md