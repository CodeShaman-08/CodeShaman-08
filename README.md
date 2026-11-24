# Hi, Harsh this Side 👋

Amazed How tech has evolved through times , 

---

## Featured project — Banking-System

A double-entry banking ledger API. Money moves through immutable `DEBIT` / `CREDIT` entries, transfers are replay-safe with idempotency keys, and every balance is derived from the ledger instead of stored in a column.

**▶ Live demo:** https://banking-system-api-fj4g.onrender.com
**Source + what I learnt:** https://github.com/CodeShaman-08/Banking-System

> Try it: create an account, create a second one, then send ₹1,000. New demo accounts start with ₹5,000 of test money.

**Stack:** Node.js · Express · MongoDB Atlas · Mongoose · JWT · bcrypt

What it covers:

- Double-entry ledger with immutable entries
- Idempotent transfers (unique key + duplicate-key handling)
- MongoDB multi-document transactions with `try / catch / finally` cleanup
- JWT auth, logout via token blacklist, and account ownership checks
- Ledger-derived balances via aggregation
- Deployed on Render, UI on GitHub Pages

---

## Other projects

- [ERRORPULSE](https://github.com/CodeShaman-08/ERRORPULSE) — a centralized system for monitoring errors.

---

## Currently

- Hardening the banking backend: integration tests for ledger invariants, rate limiting, integer money
- Building in public: writing up one failure mode at a time

## Skills

JavaScript · Node.js · Express · MongoDB · REST APIs · JWT auth · Git

---

*Every project here is something I can explain line by line.*
