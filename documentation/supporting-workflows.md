# Supporting Synced Checkbox Workflows

## Overview

These supporting n8n workflows update the Zoho Billing **Synced to NetSuite** checkbox after transaction processing.

They help prevent the same Zoho record from being processed repeatedly by identifying records that have already been synchronized with NetSuite.

## Supporting Workflows

### 1. Invoice Synced Checkbox

Workflow file:

```text
workflows/supporting/mark-invoice-synced-checkbox.json