# RFQ → Quote Copilot — demo

A deterministic, zero-dependency single-page demo of an **agentic RFQ → Quote copilot**, built on **Ciklum's Prodigy Agentic Framework**.

It reads an incoming customer request (email, chat, or a transcribed phone call), searches supplier catalogs (Advantech + Moxa), matches each line to a SKU **with a citation back to the source page**, lets a **human approve every line**, and generates a branded quotation. Two scenarios include a **"part not found" guardrail** — the agent flags the item and refuses to invent a SKU.

**Live demo:** https://giqciklum.github.io/rfq-quote-agent-demo/

- Single static file, no backend, no API keys, no build step — it runs anywhere and can't fail live.
- Demo data is illustrative and prices are representative (a real deployment would price from an ERP/authoritative feed, never a scraped page).

*Powered by the Prodigy Agentic Framework — Ciklum.*
