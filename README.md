# DBBridge â€” public Windows builds

**DBBridge** compares, migrates, and validates databases between **PostgreSQL** and **SQL Server**.

This repository hosts **public downloadable builds only**.  
Application source code lives in a **private** repository and is not published here.

---

## Download (latest)

| | |
|--|--|
| **Latest release** | [Releases](https://github.com/ashokreddydev/DBBridge-releases/releases/latest) |
| **Current build** | [DBBridge 0.1.2 Portable (Windows)](https://github.com/ashokreddydev/DBBridge-releases/releases/tag/v0.1.2-portable) |
| **File** | `DBBridge-0.1.2-portable.exe` (Windows x64, portable) |

1. Open the [latest release](https://github.com/ashokreddydev/DBBridge-releases/releases/latest).
2. Under **Assets**, download `DBBridge-*-portable.exe`.
3. Double-click the `.exe` to run â€” **no installer** required.

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

- This repo contains **release binaries and notes only** â€” not source code.
- Do not commit credentials into any DBBridge project.
- Review [Safety & limits](https://dbbridge.testforge.co.in/safety) before production migrations (truncate, drops, cross-DB type mapping).

## License / source

Source is private. Contact support for licensing or commercial use questions.
