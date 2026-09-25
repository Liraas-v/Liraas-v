<div align="center">

# Henrique Lira

**Software Engineering Student @ FIAP**

`Data` • `Artificial Intelligence` • `Automation` • `Software Development`

São Paulo, Brazil

</div>

## About

Software Engineering student at FIAP (1st year), building real products since day one.
I focus on **Data, AI and Automation**, with hands-on work in Python and SQL.
I'm currently studying RAG, LLMs, AI Agents and Data Analysis with Pandas, and looking for my **first internship** in Data, AI or Software Development.

## Featured Projects

### 📈 Farol B3: personal investment assistant *(in production)*
Analyzes Brazilian stocks and REITs (B3) and tells me when something is worth a look. I've been using it for months to track my own portfolio.

- **Attractiveness score** per asset, combining valuation (P/B vs. historical median), dividend yield and beta, with configurable weights.
- **Automated pipeline:** a scheduled job runs every 30 minutes during market hours, plus a daily radar that scans assets outside my portfolio. Alerts go out by email.
- **Web dashboard:** portfolio profit/loss, watchlist, market radar, alert history and saved analyses written in Markdown.
- **Reliability work:** retry with backoff, automatic history retention, fixes for alert flooding, CI with linting and type checking.

`Python` · `Supabase (PostgreSQL)` · `GitHub Actions` · `Next.js` · `TypeScript` · `Vercel` · `brapi.dev API`
*Private repository.*

### 🧼 Lira Sneakers Manager: management system for my sneaker laundry *(active development)*
End-to-end system for a real business I own: customer → intake → photos and diagnosis → quote → service order → payment → delivery. The MVP is complete and the product keeps evolving in documented phases (mobile-first service flow and a full visual redesign are the latest).

- **Multi-item service orders:** each pair has its own state machine, and the order status is derived from its pairs.
- **Versioned quotes** with partial approval per pair, automatic expiry, and partial payments with refunds.
- **Kanban board** with drag-and-drop, a command palette (`Ctrl+K`) and an operational and financial dashboard.
- **Customer messaging via WhatsApp** generated per milestone, with no customer portal to maintain.
- **Security and access control:** permission-based roles (admin, attendant, operator, finance), audit log, login lockout and rate limiting, hardened headers.
- **Multi-tenant from the first migration**, designed to be offered to other laundries.
- **Engineering practice:** solo project built spec-first, one documented plan per phase, with CI on every pull request.

`Python` · `FastAPI` · `SQLAlchemy` · `PostgreSQL` · `Next.js` · `TypeScript` · `Tailwind` · `TanStack Query`
*Private repository.*

### 🤖 [personal-finance-agent](https://github.com/Liraas-v/personal-finance-agent)
Local, offline personal finance agent: log expenses by text, voice or receipt photo, categorized by a local LLM (Ollama), with no data sent to external servers.
`Next.js` · `TypeScript` · `Ollama` · `Zustand`

### 🌐 [Landing-page-lira-sneakers-v2](https://github.com/Liraas-v/Landing-page-lira-sneakers-v2)
Landing page for the sneaker cleaning business I own in São Paulo.
`HTML` · `CSS` · `JavaScript`

## Languages & Tools

<div align="center">

<img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,tailwind,fastapi,postgres,supabase,docker,git,github,vscode,vercel" />

</div>

## Contact

📧 [henriqueliracosta6@gmail.com](mailto:henriqueliracosta6@gmail.com) <br>
💼 [LinkedIn](https://www.linkedin.com/in/henriqueliracosta/)
