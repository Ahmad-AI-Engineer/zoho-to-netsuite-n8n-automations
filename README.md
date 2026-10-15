# Zoho to NetSuite n8n Automation Suite

This repository contains a set of n8n workflows for automating finance operations between Zoho Billing and Oracle NetSuite.

The project is organized into two groups:

- **Main workflows** — handle the core Zoho to NetSuite transaction automation.
- **Supporting workflows** — update the Zoho "Synced to NetSuite" checkbox after processing.

## Main Workflows

| Workflow | Description |
|---|---|
| Invoice Automation | Syncs Zoho invoices into NetSuite |
| Payment Automation | Syncs Zoho payment data into NetSuite |
| Credit Memo Automation | Syncs Zoho credit memos into NetSuite |
| Void Invoice Credit Memo Automation | Handles void invoice scenarios and related credit memo processing |

## Supporting Workflows

| Workflow | Description |
|---|---|
| Mark Invoice Synced Checkbox | Marks the Zoho invoice as synced to NetSuite |
| Mark Payment Synced Checkbox | Marks the Zoho payment as synced to NetSuite |
| Mark Credit Memo Synced Checkbox | Marks the Zoho credit memo as synced to NetSuite |

## Repository Structure

```text
zoho-to-netsuite-n8n-automations/
│
├── README.md
│
├── workflows/
│   ├── main/
│   │   ├── invoice-automation.json
│   │   ├── payment-automation.json
│   │   ├── credit-memo-automation.json
│   │   └── void-invoice-credit-memo-automation.json
│   │
│   └── supporting/
│       ├── mark-invoice-synced-checkbox.json
│       ├── mark-payment-synced-checkbox.json
│       └── mark-credit-memo-synced-checkbox.json
│
├── documentation/
│   ├── invoice-automation.md
│   ├── payment-automation.md
│   ├── credit-memo-automation.md
│   ├── void-invoice-credit-memo-automation.md
│   └── supporting-workflows.md
│
└── screenshots/