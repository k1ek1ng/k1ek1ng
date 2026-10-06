# Kiela King

CS and Math at UW-Madison. In summer 2026 I was the sole Software Engineering
Intern at **Cypress Industries**, a mid-sized manufacturer, automating finance,
procurement, quoting, and order entry on the company's ERP.

What's in production:

| Tool | What it does |
|---|---|
| **ERP query server** | Lets 10 executives, including the CEO and CFO, ask the ERP questions in plain English. 36 read-only tools, per-user access tokens, and an audit log. |
| **PO to sales order** | Turns emailed customer PO PDFs into ERP sales orders after a person approves them. Saves about an hour per order. |
| **AP invoice pipeline** | Checks supplier invoices against the PO and receipts, then posts approved ones to the ERP. |
| **AR invoice delivery** | Drafts one email per customer with that day's invoices attached, for AR to review and send. |
| **CAD drawing to quote** | Turns customer drawings into quote workbooks pre-filled with ERP part data. Used daily by the quoting team. |
| **Live reports** | Production, shortage, and cost-variance reports that pull fresh numbers from the ERP on their own instead of being rebuilt by hand. |
| **Supplier follow-up** | A weekly job, running unattended since June, that flags overdue supplier orders for buyers. |

Anything that writes to the ERP waits for a person to approve it first.

## Repos

| Repo | What it is |
|---|---|
| [**erp-query-mcp**](https://github.com/k1ek1ng/erp-query-mcp) | Public rebuild of the ERP query server against a synthetic database, plus why the production version took a stricter design. |
| [**ai-document-extractor**](https://github.com/k1ek1ng/ai-document-extractor) | Invoice PDFs to validated JSON and Excel. Text-layer engine first, vision model second, one schema that checks the arithmetic either way. |

## Write-ups

Proprietary work, described with permission ([full set](https://github.com/k1ek1ng/portfolio)):

- [Customer PO to sales order](https://github.com/k1ek1ng/portfolio/blob/main/case-study-po-to-so.md)
- [AP invoice matching and vouchering](https://github.com/k1ek1ng/portfolio/blob/main/case-study-ap-invoice-agent.md)
- [AR invoice delivery](https://github.com/k1ek1ng/portfolio/blob/main/case-study-ar-invoicing-pipeline.md)

## Stack

Python, Node.js, SQL Server, LLM APIs, MCP, Playwright, pandas/openpyxl

kielaemmaking@gmail.com
