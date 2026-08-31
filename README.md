# Kiela King

CS and Math at UW-Madison. Last summer I was the entire AI function at **Cypress
Industries**, a manufacturer — one intern, no senior engineer to review the work,
and back-office processes that were being done by hand.

I built tools for accounts payable, accounts receivable, sales-order entry,
purchasing follow-up, and ERP reporting. Several are in production and run
without me. All of them stop and ask a person before doing anything that costs
money.

## Repos

| Repo | What it is |
|---|---|
| [**erp-query-mcp**](https://github.com/k1ek1ng/erp-query-mcp) | MCP server giving an LLM read-only SQL access to an ERP database. Free-form SQL with guardrails — and a note on why the production version deliberately did not work this way. |
| [**ai-document-extractor**](https://github.com/k1ek1ng/ai-document-extractor) | Invoice PDFs to validated JSON and Excel. Text-layer engine first, vision model second, one schema that checks the arithmetic either way. |

## Write-ups

Proprietary work, described with permission — [full set](https://github.com/k1ek1ng/portfolio):

- [AP invoice matching and vouchering](https://github.com/k1ek1ng/portfolio/blob/main/case-study-ap-invoice-agent.md) — why price matching is exact at 4 decimal places, and what a backtest against approved invoices can and cannot prove
- [Customer PO to sales order](https://github.com/k1ek1ng/portfolio/blob/main/case-study-po-to-so.md) — extraction coverage 54% to 84% on a real corpus, and idempotent ERP writes
- [AR invoice delivery](https://github.com/k1ek1ng/portfolio/blob/main/case-study-ar-invoicing-pipeline.md) — the problem was customer identity, not email

## Stack

Python, Node.js, SQL Server, LLM APIs, MCP, Playwright, pandas/openpyxl

kielaemmaking@gmail.com
