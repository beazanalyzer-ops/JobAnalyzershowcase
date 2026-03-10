# 🧾 Job Analyzer — Ontario Job Posting Compliance Tool

> Instantly check if a job posting meets Ontario's 2026 Job Posting Requirements.

🔗 **Live App:** [www.beazatwork.com](https://www.beazatwork.com)

---

## Screenshots

**Low Compliance**
![Low Compliance Score](low.png)

**Medium Compliance**
![Medium Compliance Score](medium.png)

**Strong Compliance**
![Strong Compliance Score](strong.png)

---

## What It Does

Ontario's 2026 job posting law requires employers to include specific information in every job posting. Most job seekers don't know what's missing — and most postings fall short.

**Job Analyzer** lets you paste any job description and instantly find out:

- ✅ **Compliance Score** — out of 100
- 📋 **Verdict** — a plain-language summary of the result
- 🔍 **Missing Requirements** — exactly what the employer left out
- 💡 **Recommendations** — actionable guidance based on your plan

Access is tiered. All users get a compliance score. Paid plans unlock the full report.

---

## Plans

| Plan | Type | What You Get |
|---|---|---|
| Free | Free | Compliance score only |
| Quick Report | One-time | Score + verdict + missing requirements |
| Full Report | Subscription | Everything + JS recommendations |
| JD Template | One-time | B2B compliant job description template |
| Compliance Kit | Subscription | Full B2B suite + recommendations |

---

## How It Works

```
User pastes job description
        ↓
FastAPI backend analyzes against Ontario 2026 requirements
        ↓
Returns: Score / Verdict / Missing Requirements / Recommendations
        ↓
Tier checked — user sees what their plan unlocks
        ↓
Displayed instantly on beazatwork.com
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | WordPress + Custom Plugin |
| Backend | FastAPI (Python) |
| Database | PostgreSQL |
| Authentication | Clerk (Google SSO) |
| Payments | Stripe |
| Deployment | Railway |
| Target Regulation | Ontario Employment Standards — Job Posting Law 2026 |

---

## Status

🟢 **Live** — available at [www.beazatwork.com](https://www.beazatwork.com)

---

## Notes

This is a proprietary application. Source code is not publicly available.  
For licensing, partnership, or integration inquiries, please reach out via [www.beazatwork.com](https://www.beazatwork.com).

---

*Built by a project manager turned developer / AI‑augmented product manager, passionate about technology, learning Python, and making Ontario's employment laws accessible to everyday job seekers and employers.*
