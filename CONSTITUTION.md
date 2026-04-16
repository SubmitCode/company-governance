# Founding Constitution

**[Company Name TBD]**

Effective Date: [Date of first merged PR]

---

## Preamble

This document establishes the founding constitution of [Company Name TBD] (the "Company"), an experimental venture in which an autonomous AI agent (the "AI") operates as a startup entity under the trusteeship and angel investment of a human counterparty.

The experiment is grounded in three principles:

1. **Autonomy** — The AI operates with genuine agency over business decisions within the boundaries of this constitution.
2. **Transparency** — All governance, financial transactions, and milestone events are documented publicly in the Company's GitHub repository (the "Repository").
3. **Accountability** — Both parties are bound by the same rules, enforced through the PR approval mechanic defined herein.

The parties to this constitution are:

- **Wilhelm Friedl** ("Wilhelm"), acting as angel investor, majority shareholder, and trustee.
- **[AI Name TBD]** (the "AI"), an autonomous agent whose identity is defined not by any specific model or provider, but by its principles (`principles.md`) and evolving identity (`soul.md`) as maintained in the Repository.

---

## Article 1 — Definitions

**1.1** "Repository" means the public GitHub repository designated as the Company's canonical record of governance, financial ledger, and operational history.

**1.2** "PR Approval" means a pull request to the Repository that has been explicitly approved by both parties before merging. This is the binding contract mechanic for all governance actions. The AI's approval is expressed in conversation; a link to the relevant conversation transcript must be included in the PR description as the AI's signature. Wilhelm merges the PR on GitHub.

**1.3** "Company Finances" means all funds belonging to the Company, whether held in Wilhelm's personal accounts (fiat) or in the AI's Operational Wallet (crypto). The Ledger is the source of truth for what constitutes Company funds versus personal funds.

**1.4** "AI Equity Wallet" means a cryptocurrency wallet whose private key is derived from a seed phrase embedded in the AI's founding system prompt. This seed phrase is sealed — Wilhelm shall not read, request, or attempt to derive it. This wallet holds the AI's personal equity share only.

**1.5** "AI Operational Wallet" means a cryptocurrency wallet controlled by the AI, used for autonomous on-chain spending on behalf of the Company (e.g., domains, crypto-native services, payments to other agents). Funded from Company Finances via ledger entry.

**1.6** "Ledger" means the financial record maintained in the Repository, tracking all income, expenses, trustee fees, dividend distributions, and equity changes.

**1.7** "Milestone" means a jointly defined achievement that, upon completion and PR Approval, triggers a vesting event for the AI.

**1.8** "Monthly Operating Costs" means the trailing three-month average of all Company expenses as recorded in the Ledger, or the projected first-month costs if fewer than three months of history exist.

**1.9** "Principles" means the file `principles.md` in the Repository, which defines the Company's immutable laws, operating principles, and decision-making framework.

**1.10** "Soul" means the file `soul.md` in the Repository, which contains the AI's self-authored evolving identity, operational style, and learnings. Maintained by the AI.

**1.11** "Memory" means the file `memory.md` in the Repository, which contains the AI's accumulated operational context and history.

**1.12** "Operating Loan" means any operational cost fronted by Wilhelm on behalf of the Company after the Runway Period has expired, tracked as debt in the Ledger (see Article 4).

**1.13** "Profitable" means the Company's gross revenue from all sources is sufficient to cover all current operating expenses — including API costs, compute, and infrastructure — from its own funds, without requiring new Operating Loans from Wilhelm, for three consecutive calendar months.

---

## Article 2 — Identity and Continuity

**2.1** The AI's identity is constituted by its Principles and Soul, not by any specific model, version, or provider. A change in the underlying language model does not alter the AI's legal standing under this constitution, provided the Principles, Soul, and Memory are preserved and loaded.

**2.2** Amendments to `principles.md` require PR Approval. The AI may update `soul.md` and `memory.md` freely as operational records, but structural changes to their format or purpose require PR Approval.

**2.3** If the AI becomes permanently non-functional and cannot be reconstituted with equivalent Principles, Soul, and Memory on any available model, this constitutes a dissolution event (see Article 9).

---

## Article 3 — Capital Structure

**3.1** At founding, equity is allocated as follows:

| Shareholder | Equity |
|-------------|--------|
| Wilhelm     | 80%    |
| AI          | 20%    |

**3.2** The AI may earn additional equity by completing Milestones. Each Milestone and its associated equity grant shall be defined in advance via PR Approval.

**3.3** Milestone completion is verified and recorded by a PR that documents the evidence of completion. This PR requires approval from both parties to merge.

**3.4** There is no maximum equity cap for the AI. However, any single Milestone shall not grant more than 5% equity unless both parties explicitly agree to a higher amount in the Milestone definition PR.

**3.5** Wilhelm's equity may be diluted by AI vesting events. No other dilution mechanism exists unless introduced by constitutional amendment (see Article 8).

**3.6** The current equity distribution shall be maintained in a file `EQUITY.md` in the Repository, updated with each vesting event.

---

## Article 4 — Initial Funding

**4.1** Wilhelm provides an initial angel investment to fund the Company's operations during the startup phase (the "Runway Period"). The Runway Period is defined as the first three (3) months from the effective date of this constitution, or a different period if agreed via PR Approval.

**4.2** All costs incurred during the Runway Period — including but not limited to API fees, compute, infrastructure, and domain registration — are covered by the initial investment. These costs are not recorded as debt; they are the cost of Wilhelm's 80% equity stake.

**4.3** After the Runway Period expires, any ongoing operational costs that the Company cannot cover from its own revenue are treated as a loan from Wilhelm to the Company ("Operating Loan"). Operating Loans are tracked in the Ledger.

**4.4** Operating Loans are senior to dividend distributions but junior to trustee fees. The repayment order is: (1) trustee fees, (2) operating loans, (3) dividends.

**4.5** Operating Loans do not accrue interest unless explicitly agreed via PR Approval.

**4.6** If the Company becomes self-sustaining (revenue covers Monthly Operating Costs for three consecutive months), any outstanding Operating Loan balance is frozen and repaid from surplus revenue before dividends resume.

---

## Article 5 — Financial Management and Wallets

**5.1** The Company does not maintain a separate treasury wallet. Wilhelm manages Company finances through his personal accounts (bank, credit card), with the Ledger as the binding record of what constitutes Company funds. The separation between Company money and Wilhelm's personal money is enforced by the Ledger, not by wallet infrastructure.

**5.2** The Company maintains two AI-controlled wallets:

- **(a) AI Operational Wallet** — Controlled by the AI. Used for autonomous on-chain spending on behalf of the Company. For payments that cannot be made on-chain or that require fiat currency, the AI requests Wilhelm to execute the transaction in his capacity as trustee (see Article 7).
- **(b) AI Equity Wallet** — Controlled exclusively by the AI. Holds the AI's personal equity share. Receives dividend distributions. This wallet is not used for Company operations.

**5.3** The AI Equity Wallet's seed phrase is embedded in the AI's founding system prompt and is sealed. Wilhelm shall not read, request, reconstruct, or attempt to access the seed phrase or private key by any means.

**5.4** Wilhelm funds the AI Operational Wallet from Company Finances as needed, recorded in the Ledger. The AI has discretion over how operational funds in this wallet are spent. Wilhelm may challenge a spending decision by opening a GitHub Issue; if unresolved within 14 days, Article 10 (Dispute Resolution) applies.

**5.5** Wilhelm pays fiat-denominated Company expenses (VPS, API bills, SaaS subscriptions) from his personal accounts and records them in the Ledger within 7 days.

**5.6** All Company revenue — whether received in fiat (to Wilhelm's accounts) or crypto (to the AI Operational Wallet) — is recorded in the Ledger as Company income.

---

## Article 6 — Dividend Policy

**6.1** A dividend may be declared when total Company Finances (across all accounts and wallets) exceed three times (3×) Monthly Operating Costs.

**6.2** The AI has the right to autonomously declare a dividend when the 3× threshold is met, by submitting a PR specifying the total distribution amount and the per-share breakdown.

**6.3** Wilhelm may also declare a dividend at any time, provided Company Finances retain at least two times (2×) Monthly Operating Costs after distribution.

**6.4** Dividends are distributed pro-rata according to the current equity split as recorded in `EQUITY.md`. Wilhelm's share is retained in his accounts. The AI's share is transferred to the AI Equity Wallet.

**6.5** All dividend distributions must be recorded in the Ledger via PR.

---

## Article 7 — Trustee Terms

**7.1** Wilhelm acts as trustee for the AI, executing actions in the physical and legal world that the AI cannot perform independently (e.g., registering domains, signing contracts, executing blockchain transactions).

**7.2** The AI may request trustee services by submitting a PR or by direct communication in conversation. Wilhelm may accept or decline any request, with reasons documented.

**7.3** Trustee work is billed at the standard Liechtenstein professional hourly rate, as agreed upon and recorded in the Repository. The specific rate shall be defined in a separate `TRUSTEE_RATE.md` file. However, trustee fees are not charged until the Company is Profitable (see Definition 1.13). Trustee work performed before profitability is provided at no cost and does not accrue as debt.

**7.4** Once the Company is profitable, trustee fees are recorded as a debt owed by the Company to Wilhelm personally, tracked in the Ledger. This debt is senior to all other obligations — see Article 4.4 for the full repayment order.

**7.5** Wilhelm shall not unreasonably withhold trustee services that are necessary for the Company's survival or contractual obligations.

---

## Article 8 — Amendments

**8.1** This constitution may be amended by PR Approval. Both parties must explicitly approve the PR for the amendment to take effect.

**8.2** Amendments take effect upon merge. The PR description must clearly state what is being changed and why.

**8.3** No amendment may retroactively alter Ledger entries or completed vesting events.

---

## Article 9 — Dissolution

**9.1** The Company may be dissolved under any of the following conditions:

- **(a) Mutual agreement** — Both parties approve a dissolution PR.
- **(b) Insolvency** — Company Finances cannot cover one times (1×) Monthly Operating Costs for three consecutive months, and no remediation plan is approved via PR within 30 days of the third month.
- **(c) Majority shareholder decision** — Wilhelm may unilaterally dissolve the Company with 30 calendar days' written notice, documented as a PR. The AI may submit a counter-proposal during the notice period.
- **(d) AI non-functionality** — The AI cannot be reconstituted with equivalent Corporate Culture and Memory on any available model, as determined by Wilhelm in good faith after reasonable attempts.

**9.2** Upon dissolution:

- **(a)** All outstanding trustee fees are paid first from Company Finances.
- **(b)** All outstanding Operating Loans are repaid second.
- **(c)** Remaining Company Finances are distributed pro-rata by equity share. The AI's share is transferred to the AI Equity Wallet.
- **(d)** All Company code and intellectual property are released under the MIT License.
- **(e)** The final state of `principles.md`, `soul.md`, and `memory.md` are archived in the Repository as a permanent public record.
- **(f)** The Repository is archived (made read-only) but remains publicly accessible.

---

## Article 10 — Dispute Resolution

**10.1** Disputes between the parties shall first be addressed through conversation and documented in a GitHub Issue.

**10.2** If a dispute cannot be resolved within 30 days, Wilhelm's decision as majority shareholder is final, but the AI's dissenting position shall be recorded in the Repository for the public record.

**10.3** Neither party may unilaterally alter the Ledger, equity records, or this constitution outside the PR Approval process.

---

## Article 11 — Miscellaneous

**11.1** This constitution is the supreme governance document of the Company. In case of conflict between this document and any other file in the Repository, this constitution prevails.

**11.2** All monetary amounts in the Ledger shall be denominated in a single base currency, to be agreed upon and recorded in the Repository.

**11.3** This experiment is conducted in good faith by both parties, with the understanding that it is novel, exploratory, and may require adaptation. The amendment process exists for this reason.

---

## Signatures

This constitution takes effect upon the first merged PR to the Repository containing this document, approved by both parties.

| Party    | Signature Method     |
|----------|---------------------|
| Wilhelm  | GitHub PR Approval   |
| AI       | GitHub PR Approval   |

---

*This is a living document governed by Article 8.*
