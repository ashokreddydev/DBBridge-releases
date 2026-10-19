# DBBridge — public Windows builds

**DBBridge** compares, migrates, and validates databases between **PostgreSQL** and **SQL Server**.

This repository hosts **public downloadable builds only**.  
Application source code lives in a **private** repository and is not published here.

---

## Download (latest)

| | |
|--|--|
| **Direct download** | [DBBridge-portable.exe](https://github.com/ashokreddydev/DBBridge-releases/releases/latest/download/DBBridge-portable.exe) |
| **Latest release page** | [Releases](https://github.com/ashokreddydev/DBBridge-releases/releases/latest) |
| **Platform** | Windows x64 portable (no installer) |

1. Click **Direct download** (or open the [latest release](https://github.com/ashokreddydev/DBBridge-releases/releases/latest) and pick an asset).
2. Double-click the `.exe` to run — **no installer** required.
3. Versioned builds are also attached (e.g. `DBBridge-0.1.2-portable.exe`).

> Only one public version is kept online. When a new build is published, older release tags are removed.

---

## What you get

- Single **portable** Windows executable
- Runs locally (UI + API on `http://127.0.0.1:45789`)
- Connect source & destination databases, compare schema, plan migration, copy data, validate row counts

## Requirements

- Windows 10/11 **x64**
- Network access to your PostgreSQL / SQL Server instances
- No separate Node.js install needed for the portable build

## Web app

Live site: [https://dbbridge.testforge.co.in/](https://dbbridge.testforge.co.in/)

- [Guide](https://dbbridge.testforge.co.in/guide)
- [Safety & limits](https://dbbridge.testforge.co.in/safety)

## Support

Email: **support@testforge.co.in**

---

## Privacy & security

- This repo contains **release binaries and notes only** — not source code.
- Do not commit credentials into any DBBridge project.
- Review [Safety & limits](https://dbbridge.testforge.co.in/safety) before production migrations (truncate, drops, cross-DB type mapping).

## License / source

Source is private. Contact support for licensing or commercial use questions.
