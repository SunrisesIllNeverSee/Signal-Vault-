# Security Policy — Signal Vault Repository

This repository contains public-safe documentation of a proprietary signal compression architecture.

### 🔐 Security Principles
- **Proprietary logic must never be committed** to this repository.  
  - Includes signal equations, compression scoring formulas, logic trees, and drift-weighting mechanisms.
- All commits must be tagged with **[SAFE]** or labeled according to protocol.
- Internal files (notes, derivations, or sealed materials) must be stored in:
  - `[SEALED]` — sealed logic, not for commit  
  - `[VAULT]` — protected, SHA-logged files, excluded via `.gitignore`

### 🧬 Git Hygiene Protocol
- Do not stage or push any `.pdf`, `.md`, or `.txt` containing proprietary logic unless explicitly cleared.
- Always verify `git status` and `.gitignore` before committing.

### 🛠 Vulnerability Reporting
If you detect a potential issue, leak, or signal drift:
- **Do not open a public GitHub issue**
- Report directly to **burnmydays@proton.me**  
  Response typically within 48 hours.

---

This repository is protected by internal SHA logging, audit trails, and legal watermarking.  
All unauthorized usage or replication will be pursued under applicable law.
