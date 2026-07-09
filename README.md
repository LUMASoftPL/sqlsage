# SQL Sage

**SQL Sage is an English-language extension you install inside SQL Server Management Studio 22 on Windows (a VSIX add-in)** — an AI pair-DBA that explains errors, tunes slow queries and runs SQL safely, signed in with your own Claude or ChatGPT account (no API key). It runs as part of SSMS on your machine; it is **not** a web app or an online SQL editor.

![SQL Sage inside SSMS](assets/screenshot.png)

## Why it's different

- **Deterministic DBA tools — it reads the server, it doesn't guess.** Query Store regressions, backup/RPO health, missing-index recommendations (cross-checked against existing indexes), wait stats, live blocking & deadlock triage, permissions audit — values come from DMVs and catalogs, not the model.
- **Keyless.** Runs on the Claude or ChatGPT account you already pay for (via Claude Code or Codex) — no separate API key, no metered second AI bill. Multi-provider: Anthropic Claude **and** OpenAI Codex / ChatGPT.
- **Safe by default.** A ScriptDom gate classifies every statement before it runs: reads execute, writes and DDL stop for your explicit confirmation with the exact SQL in front of you.

## Download

Get the signed installer from the [**latest release**](https://github.com/LUMASoftPL/sqlsage/releases/latest), or from the website: **https://sqlsage.lumasoft.pl**

- Windows · SSMS 22 · x64 / Arm64
- Every install starts with a **30-day free trial** (all features, no credit card)
- Own it once from **$39**, or subscribe from **$29/year**

The installer is Authenticode-signed by **LUMA sp. z o.o.** (Certum). While download reputation builds, Windows SmartScreen may still prompt — choose **More info → Run anyway**.

## Support & feedback

- Issues and feature requests: [GitHub Issues](https://github.com/LUMASoftPL/sqlsage/issues)
- Email: support@lumasoft.pl
- Docs: https://sqlsage.lumasoft.pl

---

SQL Sage is a commercial product by **Luma (LUMA sp. z o.o.)**. This repository hosts releases, docs and issue tracking; the product source is not open-source. Not affiliated with Microsoft, Anthropic or OpenAI.
