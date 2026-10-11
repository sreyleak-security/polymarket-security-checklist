# Polymarket Security Checklist

Security checklists for Polymarket traders — maintained by [Srey Leak](https://github.com/sreyleak-security), security researcher & anti-scam educator (Long Beach, CA).

> **Prevention, not recovery.** Polymarket refunded every victim of the June 25, 2026 frontend hack ($3.1M, 11 accounts). Any third-party "recovery service" asking for seed phrases is fraudulent.
>
> ## Why
>
> After two years building detection systems at Coinbase and tracing stolen funds at Chainalysis, I saw the same pattern in every incident: **the compromise was preventable**. The victim signed one malicious transaction, or stored one key where it shouldn't be.
>
> This repo turns those lessons into checklists you can actually use.
>
> ## Checklists
>
> | File | Purpose |
> |------|---------|
> | [`checklists/pre-trading.md`](checklists/pre-trading.md) | Before you fund an account: wallet hygiene, Session Keys, signer separation |
> | [`checklists/during-trading.md`](checklists/during-trading.md) | Daily discipline: signing discipline, URL checks, session expiry |
> | [`checklists/post-incident.md`](checklists/post-incident.md) | You clicked the link. Now what — first 30 minutes |
>
> ## Multilingual red flags
>
> Scams hit immigrant communities hardest — in their own language:
>
> - [`multilingual/khmer-red-flags.md`](multilingual/khmer-red-flags.md) — ការព្រមាន (Khmer)
> - - [`multilingual/vietnamese-red-flags.md`](multilingual/vietnamese-red-flags.md) — Cảnh báo (Vietnamese)
>   - - [`multilingual/lao-red-flags.md`](multilingual/lao-red-flags.md) — ຄຳເຕືອນ (Lao)
>    
>     - ## Tools
>    
>     - - `tools/session-key-setup.py` — helper for scoped signer setup (coming)
>       - - `tools/address-verifier.py` — verify a market/contract address against official listings (coming)
>        
>         - ## Free workshops
>        
>         - I run free security workshops for Cambodian, Vietnamese and Lao communities in Long Beach, California. If you're local — come. Bring your parents.
>        
>         - ## Disclaimer
>
> Educational content only. Not financial advice. Security is your responsibility.
> I am not affiliated with Polymarket. This is not official documentation.
>
> ## License
>
> MIT
> 
