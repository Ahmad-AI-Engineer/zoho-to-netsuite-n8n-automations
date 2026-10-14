# Void Invoice Credit Memo Automation

## Overview

This workflow automates the handling of void invoice scenarios between Zoho Billing and Oracle NetSuite using n8n.

The goal of this automation is to manage cases where a Zoho invoice is voided and a related credit memo or adjustment process needs to be reflected in NetSuite.

## Business Purpose

Void invoice handling can become complex when billing and accounting systems are separate.

When an invoice is voided in Zoho Billing, finance teams may need to manually update NetSuite, create related credit memo records, or adjust accounting references.

This workflow helps automate that process and reduces manual correction work.

## Workflow File

```text
workflows/void-invoice-credit-memo-automation.json