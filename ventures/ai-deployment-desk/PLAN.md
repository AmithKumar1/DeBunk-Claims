# AI Deployment Desk for Boutique Investment Firms: Thesis and 90-Day Plan

Working name only. Status: v1, 4 Oct 2026. Every number marked **[H]** is a hypothesis to test, not a fact.

Labels used: **[V]** verified from a primary or major source · **[R]** reported by secondary sources · **[H]** our hypothesis · **[O]** opinion

---

## 1. The idea in one line

> **We are the AI engineering team a boutique investment firm can't justify hiring.** We find the 2–3 workflows where AI moves money or time, build them on the firm's own data, run them safely, and own them month after month.

Not "AI consulting." Not a model. Not a hedge fund. We're a small **forward-deployed AI team** for firms too small for OpenAI DeployCo, Ode or the Big 4, and too specialised for the off-the-shelf small-business kits.

---

## 2. Why now (what the market has already proven)

| Fact | Label | What it means for us |
|---|---|---|
| OpenAI launched the **OpenAI Deployment Company** (11 May 2026). It's backed by $4B+ from 19 investors, acquired Tomoro (~150 forward-deployed engineers) and embeds engineers inside clients. | [V] | The biggest lab is paying to solve deployment, not to build models. The thesis is validated at the top. |
| **Ode with Anthropic** launched in July 2026 with Blackstone, H&F, Goldman, Apollo, GIC, Sequoia and others. It's valued at about $1.5B, built on Fractional AI and embeds engineers inside companies. | [V] | The financial firms' contribution is **distribution** (portfolio companies), not AI skill. |
| On 2 Oct 2026 Anthropic launched the **Claude Frontier Academy**: $100M to train 10,000 "Frontier Deployed Engineers" by end-2027. It calls talent "one of the most pressing issues in AI implementation". First cohorts come from Accenture, Bain, Deloitte, McKinsey, Morgan Stanley and others, and entry is by nomination. | [V/R] | The talent shortage is official. The first wave of trained engineers goes to large enterprises. |
| Goldman Sachs 10KSB survey (Mar 2026, 1,256 owners): **76% use AI, only 14% have it fully in core operations, and 73% want more training and resources**. | [V] | Small firms use AI, but they don't run their business on it. That gap is the market. |
| Mercer (Feb–Mar 2026, 131 asset managers): **55%** have AI in at least one investment process, **69%** cite data quality/access, **59%** cite regulatory concerns, and **57%** have only 1–5 dedicated AI staff. | [V] | Even funds lack AI hands, and data plumbing plus compliance are the blockers. That's deployment work. |
| India: the SEBI (Intermediaries) (Amendment) Regulations, 2025 make every SEBI-regulated entity **solely responsible** for data privacy and security, AI outputs, and legal compliance when it uses AI tools, including third-party ones. | [V/R] | Indian funds can't paste client data into chatbots and hope. They need AI built with logs, approvals and data controls. |
| SEBI register (late Sep 2026): about **2,030 AIFs, 537 portfolio managers, 1,045 investment advisers**. | [R]: verify on sebi.gov.in | We have a countable, reachable beachhead of about 3,600 firms in one regulator's list. |

### The correction that changes the plan

Generic "AI implementation for small business" is **no longer an open gap**:
- More than 40,000 firms applied to the Claude Partner Network and more than 10,000 consultants are certified. [R]
- OpenAI's Partner Network ($150M) targets 300,000 certified consultants by end-2026. [R]
- Claude for Small Business (15 workflows at launch; QuickBooks, HubSpot, PayPal and similar) and ChatGPT for Financial Services (LSEG, PitchBook, Daloopa data) already exist. [V]

**So the opening isn't "small firms need AI help." It's: regulated, data-heavy boutique firms need a deployment team that understands their workflows and their regulator.** Domain depth and trust are the only defensible positions for a small player.

On the video's "Goldman head said there's a shortage" claim: I couldn't find that exact quote. The verifiable version is Anthropic's own talent statement plus Goldman's small-business survey. Use those when pitching.

---

## 3. Who we serve first (beachhead)

### Recommendation [O]: India first, then US, UK or Gulf with case studies

| | India: SEBI boutiques | US/UK emerging managers |
|---|---|---|
| Access for us | High (network, language, time zone, in-person Mumbai meetings) | Low (no references, cold outreach only) |
| Ticket size | Lower [H] | 5–10× higher [H] |
| Regulatory pull | Strong and new (SEBI AI responsibility rule) | Strong (SEC/FCA) but a crowded vendor field |
| Competition | Thin for *implementation* (vertical platforms exist: OnFinance, Alltius) | Dense (Partner Network firms, Hebbia, Rogo and others) |
| Learning speed | Fast | Slow |

India is the cheap place to earn the **first 3 references and the playbook**. Expansion abroad sells on those case studies, not on promises.

### Ideal first customer (ICP v1) [H]

- SEBI-registered **PMS, Category III AIF, or RIA**, roughly 5–50 people
- The founder or CIO is the buyer: one decision-maker, no procurement committee
- Pain signals: analysts drowning in filings and concalls, a monthly client-reporting crunch, rising compliance paperwork, a team already copy-pasting into ChatGPT
- No in-house AI engineer

**The tiebreaker is access.** The first segment is whichever one you can get 10 meetings with in two weeks.

---

## 4. What we sell: an offer ladder priced on outcomes, not hours

| Step | What the client gets | Duration | Price hypothesis (India) [H] | Price hypothesis (US) [H] |
|---|---|---|---|---|
| **1. Sprint** | Workflow audit, data map, 3 ranked use cases with hours or ₹ impact, and one working prototype on their data | 2 weeks | ₹75k–1.5L | $5–10k |
| **2. Deploy** | One workflow in production: integrations, human-approval step, audit log, evaluation set and a trained team | 4–6 weeks | ₹3–8L | $15–40k |
| **3. Run** | Managed AI operations: monitoring, accuracy checks, model updates, a new mini-workflow each quarter, and a compliance log pack | Monthly | ₹40k–1.5L/month | $3–10k/month |

Recurring "Run" revenue is the business. The Sprint is the door and Deploy is the proof.

---

## 5. The first three workflows

Pick **one** to lead with. Recommended lead: **#1**, because it's closest to your trading knowledge and the CIO, who's the buyer, sees its value daily.

1. **Research Desk Agent.** Every morning, for the firm's holdings and watchlist: NSE/BSE corporate announcements, results, concall transcripts and news, delivered as a cited brief with flagged anomalies (guidance change, auditor resignation, promoter pledge, related-party items). It also keeps a searchable research memory.
2. **Client Reporting and Communications.** First drafts of monthly commentary, factsheet narratives, investor letters and answers to client queries, generated from the firm's own data. A human approves every word before it goes out.
3. **Compliance and Ops Assistant.** It tracks SEBI circulars and maps them to the firm's obligations, extracts KYC and onboarding documents, and keeps an audit-ready log of every AI action. This is a draft tool, never the final say.

---

## 6. How we deliver (the standard build)

```
Firm's data (holdings, research notes, PDFs, email, CRM, Excel)
  + public data (NSE/BSE filings, concalls, news)
        ↓
Retrieval + orchestration layer (ours, reused across clients)
        ↓
Model: Claude / OpenAI / open-weight, chosen per workflow (model-agnostic)
        ↓
Human approval step  →  Action (brief, draft, alert)
        ↓
Logs + evaluation set + usage/time-saved dashboard
```

Non-negotiables, which are also the sales pitch under the SEBI rule:
- Deploy in the **client's own cloud account or tenant** where possible, with no cross-client data mixing
- Every output is **logged and traceable** to its sources
- **A human approves** anything that reaches a client or a regulator
- A written **AI usage and data policy** for each client, mapped to the SEBI AI-responsibility clause and the SEBI cybersecurity framework (CSCRF), with scope confirmed by their compliance officer
- A per-workflow **evaluation set**, so accuracy is measured rather than claimed

What we keep and reuse across clients becomes the product later: connectors, prompt and eval libraries, the logging and approval layer, and the dashboard.

---

## 7. Kill test: why wouldn't they just…

| Alternative | Their reason | Our answer | Honest risk |
|---|---|---|---|
| Use ChatGPT or Claude directly | "We already pay for it." | Tools aren't systems: nobody connects your data, builds the controls or owns it. | Products keep getting better; simple research summaries may get commoditised. Stay in the **integration + ops** layer. |
| Hire a freelancer | Cheaper | No continuity, no compliance posture, no playbook, gone in 3 months | Price pressure in India |
| Ode, OpenAI DeployCo, Big 4 | Brand | Their economics don't fit a 10–30-person firm. | They may launch mid-market kits later. |
| Vertical AI platforms (OnFinance, Alltius) | Packaged product | They sell one platform. We fit the firm's stack and stay model-agnostic. | Could become partners rather than competitors |
| One of the 40,000 partner firms | Many options | Vertical depth: we speak PMS/AIF and SEBI. | Generic firms will claim finance experience too. Win on **case studies**. |

---

## 8. 90-day plan with go/no-go gates

| Phase | Weeks | Goal | Output | Gate (go / pivot / kill) |
|---|---|---|---|---|
| **0. Discover** | 1–2 | Prove the pain exists and is paid for | 15–20 discovery calls (script in §10), pain log | **Go** if at least 5 firms name the *same* painful workflow and at least 3 agree to a paid Sprint or pilot with data access. **Pivot segment** if pain is real but nobody will pay. **Kill** if fewer than 2 show pain. |
| **1. Demo** | 2–4 | A sales asset that shows rather than tells | Research Desk Agent running on public data for a sample 20-stock portfolio, plus a 3-minute screen recording | Shown to at least 10 prospects; at least 3 ask "can it do this for *our* book?" |
| **2. Design partners** | 4–8 | 2–3 real deployments | Paid (discounted) Sprints turning into Deploys; hours-saved baseline measured *before* go-live | At least 2 workflows live in production, used weekly, with measured time saved |
| **3. Convert** | 8–12 | Recurring revenue plus a repeatable playbook | At least 2 "Run" retainers, 2 written case studies, a standard intake, data checklist, security doc and eval harness | Run gross margin of at least 60% [H]; at least 1 inbound referral |

**At day 90, decide:** go deeper in India, open US/UK/Gulf sales with the case studies, or pivot the segment. Make this call on data, not on mood.

Partner-program milestone: individual Claude/OpenAI certification now. The Claude Partner Network *Select* tier (reported: 10 certified staff, 2 production customers, 1 public story) is a 6–12 month goal, not a starting requirement.

---

## 9. This week

1. **Write down 30 names** of PMS, AIF and RIA founders, CIOs, analysts or COOs you can reach through warm intros, ex-colleagues, trading circles or LinkedIn.
2. **Book 5 calls.** The ask is 20 minutes to learn how they work, not a pitch.
3. **Run the script in §10.** Log every answer in one sheet with these columns: firm, size, workflow, hours/week, tools, has tried AI?, blocker, would pay?, next step.
4. **Start the demo skeleton** (Research Desk Agent on 20 NSE stocks) only *after* the first 3 calls, so the calls shape the demo.
5. **Settle the open decisions in §12.**

---

## 10. Discovery call script (ask about the past; don't pitch)

1. Walk me through the last time you [researched a new stock / prepared the monthly client report / handled a compliance filing]. Who did what, and how long did it take?
2. Which step is the most painful or most repeated?
3. What tools and data do you pay for? (For example: terminal or data feed, Excel models, CRM, ACE Equity/Capitaline/Screener-type sources.)
4. Has anyone on the team tried ChatGPT or Claude for this? What happened?
5. What stops you from putting firm or client data into AI tools today?
6. Who would be blamed if an AI-generated number went to a client wrong?
7. If that task took 1 hour instead of 6, what would the team do with the time?
8. Have you ever paid an outside tech firm or freelancer? How did it go?
9. Who signs off on spending on tools like this?
10. If I built a working version of [their painful step] on your data in 2 weeks, would you pay for that trial?

Rule: if they're only being polite, it's a no. A real "yes" comes with time, data access or money.

---

## 11. Metrics that matter

- Calls held, and the share that confirm the *same* pain
- Paid Sprints signed (money in, not "interested")
- Days from signed to in production
- Hours saved per client per week (measured against the pre-deployment baseline)
- Weekly active users of each deployed workflow
- Retainer retention and gross margin per client

Not progress: decks, logos, a website, or the number of AI tools tried.

---

## 12. Open decisions (our next Q&A)

1. **Beachhead:** India SEBI boutiques first, as recommended, or US/UK/Gulf first? Which segment can you actually get 10 meetings in?
2. **Time budget:** how many hours a week can you give this for the next 4 weeks? Phase 0 is designed to run on about 5–7 hours a week.
3. **Structure:** is this a Bucephus service line, or a separate entity?
4. **Delivery capacity:** will you build the first deployments yourself, or bring in an engineer partner after the first 2 signed clients?
5. **Lead workflow:** Research Desk Agent (recommended), Client Reporting, or Compliance?

---

## 13. Risks

| Risk | Mitigation |
|---|---|
| Model vendors productise the lead workflow | Stay in integration, controls and operations. Productise *our* reusable layer, not the prompt. |
| A data breach or a wrong AI output reaches a client | Client-tenant deployment, human approval, logs, eval sets, a contractual scope limit, and later professional indemnity or cyber cover |
| The services trap (linear revenue, founder-bound) | Fixed-scope packages, a reusable stack, Run retainers, and hiring only when 2 clients are signed |
| Indian willingness to pay is too low | Validate in Phase 0. If it fails, use India for references at low price and sell full price abroad. |
| Founder bandwidth | Gated plan: nothing gets built before the pain is proven |

---

## Sources

- OpenAI, *OpenAI launches the OpenAI Deployment Company*: https://openai.com/index/openai-launches-the-deployment-company/
- HPCwire/AIwire on DeployCo: https://www.hpcwire.com/aiwire/2026/05/11/openai-launches-deployment-company-to-scale-enterprise-ai-adoption/
- BusinessWire, *Introducing Ode with Anthropic*: https://www.businesswire.com/news/home/20260715205134/en/Anthropic-Blackstone-and-Hellman-Friedman-Introduce-Ode-with-Anthropic-an-Enterprise-AI-Services-Firm
- TechCrunch on Ode: https://techcrunch.com/2026/07/15/anthropic-blackstone-bet-the-next-trillion-dollar-ai-business-is-implementation-not-models/
- Benzinga, Claude Frontier Academy: https://www.benzinga.com/markets/tech/26/10/62151067/anthropic-100-million-claude-frontier-academy
- Goldman Sachs 10KSB AI survey: https://www.goldmansachs.com/pressroom/press-releases/2026/small-businesses-embrace-ai-but-need-training-and-support-to-fully-harness-it
- Mercer, *Asset managers' use of AI*: https://www.mercer.com/insights/investments/market-outlook-and-trends/asset-managers-use-of-ai/
- Anthropic, *Claude for Small Business*: https://www.anthropic.com/news/claude-for-small-business
- Anthropic, *Claude Partner Network*: https://anthropic.com/news/claude-partner-network
- Channel Insider, Claude partner services tiers: https://www.channelinsider.com/channel-business/vendor-leadership-and-partner-programs/claude-partner-network-services-track/
- OpenAI, *Introducing the OpenAI Partner Network*: https://openai.com/index/introducing-openai-partner-network/
- Bloomberg, ChatGPT for Financial Services: https://www.bloomberg.com/news/articles/2026-09-10/openai-debuts-chatgpt-for-financial-services-an-investment-banker-tool
- Lexplosion, SEBI AI responsibility amendment: https://lexplosion.in/sebi-issues-guidelines-on-ai-usage-entities-using-ai-ml-tools-responsible-for-data-security-ai-generated-outputs-and-compliance-with-applicable-laws/
- SEBI board agenda on AI responsibility (Dec 2024): https://www.sebi.gov.in/sebi_data/meetingfiles/dec-2024/1735042007618_1.pdf
- SEBI recognised intermediaries list (counts; verify directly): https://www.sebi.gov.in/sebiweb/other/OtherAction.do?doRecognised=yes
- Inc42, Indian AI startup tracker (OnFinance, Alltius): https://inc42.com/startups/indian-ai-startup-tracker/
