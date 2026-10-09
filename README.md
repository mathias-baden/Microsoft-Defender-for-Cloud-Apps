# Microsoft Defender for Cloud Apps

Scripts and tools for **Microsoft Defender for Cloud Apps (MDCA)** — built from real-world deployments.

🌐 Written up in more depth at [mathiasbaden.com](https://mathiasbaden.com)

## 🧰 Tools

### [Policy Backup](./Policy%20Backup/)
A PowerShell script that pulls every MDCA policy via the API and backs each one up as JSON to an Azure Storage container — a versioned, restorable copy of your policy config, since the portal has no native export/restore.
`PowerShell` · `MDCA API` · `Azure Storage`

## A note on the examples

Any app IDs, tenant IDs, secrets, or tokens in these files are **placeholders**. Replace them with your own — and never commit real secrets — before running anything. Each tool's readme says where.

## License

MIT — Copyright (c) 2026 Mathias Baden Frederiksen — [mathiasbaden.com](https://mathiasbaden.com). Adapt freely.

---

⭐ If something here helps, a star helps others find it too.
