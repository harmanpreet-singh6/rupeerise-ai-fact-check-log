# RupeeRise: Fact-Checking an AI-Written Investor Brief

**A FinTech case study on catching AI hallucinations before they reach investors.**

**Author:** Harmanpreet Singh · BBA (FinTech), Chitkara Business School · **Tools:** Claude, ChatGPT, Perplexity · November 2026

## The case
**RupeeRise** (fictional) is a digital lending app in Bengaluru. Its founder asked AI to write an investor brief on India's digital lending and UPI market and wanted to send it as it was. As a Business Analyst, I checked every claim against official sources before it could reach investors.

## What I did

| Step | Task | Tool |
|---|---|---|
| 1 | Generated the same brief in two AI tools | Claude, ChatGPT |
| 2 | Scored both drafts on 5 criteria | Manual |
| 3 | Listed 20 claims and asked the AI to rate its own confidence | AI + manual |
| 4 | Verified every claim against RBI, NPCI and PIB | Official websites |
| 5 | Opened every source Perplexity cited | Perplexity |

## Results

| Metric | Result |
|---|---|
| Claims checked | 20 |
| Correct | 12 |
| Outdated / Distorted / Fabricated / Unsupported | 2 / 2 / 1 / 3 |
| Rated "High confidence" by AI but wrong | 3 |
| Perplexity citations that fully supported the claim | 6 of 10 |
| Tool comparison score (Claude vs ChatGPT, /10) | 7.5 vs 8 |

## Worst error I found

The AI claimed that India's digital lending market had no major regulatory restrictions on app-based lenders and that platforms could independently approve and disburse loans without regulated lending partners. However, RBI guidelines establish important requirements around regulated entities, lending arrangements
