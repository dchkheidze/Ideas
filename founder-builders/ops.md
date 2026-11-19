# Operations: builder marketplace (working name not chosen)

Run date: 2026-11-19. Built from `idea.md`, `pitch.md`, `customer.json`, `board.md`, `board/*.md`, `competitors.md` and `panel/results.md` in this folder. Nothing in `/home/user/Ideas/founder/` was read or written.

**Read this first.** Country, city, job type (flat renovation is the board's candidate), commission and the money model are all still open. So this plan is a set of branches, not one run-sheet. Every price, wage, fee, permit rule and legal point below is marked **VERIFY** and names the source to check. None is a fact yet. Competitor figures come from `competitors.md` and are data points about other firms, not our costs.

---

## 0. The decision the operations depend on: the money seam

The board, the pitch and the panel all point at this choice. The pitch says the platform "handles payment", which is the held-money model. The board's conditions say it must be decided before any design.

| | A. Introduction only | B. Platform holds the money (escrow or partner account) |
|---|---|---|
| What the platform runs | Brief, bids, selection, contract template, stage checklists. Money goes straight from customer to builder. | All of A, plus taking payments, releasing them by stage, refunds, and a dispute process that decides who gets paid. |
| Ops load | Low to medium. Mostly coordination and disputes without money. | High. Needs a finance role and a payment-dispute route on top of the rest. |
| Build load | Forms and documents first (the board's by-hand test). | Adds a payment partner, a milestone engine and refund handling. A much larger build (Product lens). |
| Legal checks | Contract and intermediary terms; consumer rules; data rules. | All of A, plus the payment rules for holding customer money and whether an escrow law applies (see section 6). |
| Panel signal | Trust and price were the main reasons for "pass" (16 and 3 of 20 cited trust and price). | Several "what would flip a no" answers ask for payment held until each stage is signed off. |
| Commission bypass | High risk: after the introduction, buyer and builder can sign off-platform (Offers lens). | Lower: the platform stays in the payment flow. |
| Protection if a builder stops mid-job | Weak. The customer's loss is paid minus done, recovered only by a claim (section 4, SOP-8). | Stronger, if the held money can be frozen and released against verified work. |

**Recommendation for the first test, not a final decision:**

1. Run the first jobs by hand with stage checklists and signed acceptance logged on the platform. Customers pay the builder directly, unless a payment partner is in place by then.
2. Do not use the words "escrow", "held", "protected payment" or "we handle the money" in any customer material until a lawyer and a payment partner have confirmed them for the country chosen. The panel's buyers will read that claim as the guarantee.
3. Make the fee visible and tie it to something the customer gets: verification, the standard brief, the bid comparison, the contract and stage acceptance. A fee for the introduction alone invites bypass.
4. Decide B only when the legal checks in section 6 return. Re-run this table then.

---

## 1. The daily cycle and the job lifecycle

### Platform's daily cycle (once live)

- **Start of day:** new job briefs to check for completeness; new builder applications; disputes and stage-acceptance requests waiting; payments due (only if branch B).
- **Through the day:** coordinator replies within the response time set in the test; bid windows closing; selection and contract steps.
- **End of day:** status update on every active job; change orders logged; list of stuck jobs (no stage report for the set number of days).

### Job lifecycle with an owner for each handoff

The board asks for an owner on each handoff. "Coordinator" means the job coordinator (section 3).

| # | Step | Customer sees it? | Owner | Handoff to next step |
|---|---|---|---|---|
| 1 | Customer posts the job on the standard brief | Yes | Customer, checked by coordinator | Coordinator confirms the brief is complete |
| 2 | Brief sent to verified builders | Partly (sees the list) | Coordinator | Bid window opens |
| 3 | Builders bid on the same template | Yes (sees bids) | Builder | Complete-bid check |
| 4 | Customer compares and picks | Yes | Customer, supported by coordinator | Contract template filled |
| 5 | Contract signed | Yes | Customer and builder; platform holds the signed copy | Payment schedule set (branch-dependent) |
| 6 | Work and stage reports | Yes | Builder reports; coordinator checks | Stage acceptance |
| 7 | Change orders | Yes | Builder proposes; customer approves | Logged; running total updated |
| 8 | Stage acceptance and payment release | Yes | Customer signs off; platform releases (B) or logs (A) | Next stage |
| 9 | Completion and final acceptance | Yes | Customer; coordinator closes | Review and warranty period starts |
| 10 | Dispute at any stage | Yes | Ops lead | Resolved, closed, or escalated (SOP-7) |

Response times, the bid window length, and the stage-report interval are **set in the test**. Nothing is assumed here.

---

## 2. Suppliers: builders and the vendors behind the platform

### 2a. Builders (the supply side)

- **Where to find them:** the board's own list of named firms in `competitors.md`, plus direct outreach. Among the named firms, only ДОМ.РФ and ПАЗЛ ДОМ are verified contractor catalogues, and both are built for new private houses. Renovation firms appear in directories that were last checked in 2020 (unverified). **VERIFY** any builder before contact, and check each one's status in the national company register and any licence or membership register for the chosen country.
- **What builders pay the platform:** unknown. The only explicit schedule in the sources is ПАЗЛ ДОМ's: 20,000 RUB per object, 1% of each finance tranche, and 3-5% per partner lead ([contractor terms](https://lp.pzzl.ru/contractors)). It is one data point, from a different product, in a different country. Use it as a reference for the commission test, not as our price.
- **Commitment before customers:** the board requires a set number of signed builders in the launch city before any customer is promised bids. The number is set by the founder (Monopoly). Not set here.

### 2b. Vendors and services

Prices and lead times are **not checked** in this run. Get quotes.

| Need | Options to quote | Price | Lead time | Note |
|---|---|---|---|---|
| Intake and job tracking | Shared spreadsheet and form for the by-hand test; a CRM later | Not checked | Immediate | The board's test needs no app. |
| Contract templates and signing | Lawyer-drafted template; e-signature service | Not checked | Not checked | Confirm the signature is legally valid for the country (VERIFY). |
| Independent site inspection (for disputes and builder stops) | Licensed inspectors or expert organisations | Not checked | Not checked | Confirm who can give an expert opinion that is accepted in a dispute (VERIFY). |
| Payment partner (branch B only) | Bank or licensed payment provider | Not checked | Not checked | Needs the legal check in section 6 first. |
| Liability insurance for the platform; insurance to require from builders | Insurer or broker | Not checked | Not checked | Confirm what is available and standard (VERIFY). |
| Legal review | Lawyer for the chosen country | Not checked | Not checked | Required before the money claim (section 0). |
| Bookkeeping | Accountant with platform and fee experience | Not checked | Not checked | Confirm the tax treatment of the fee and of pass-through payments (VERIFY). |

**Open:** no supplier was confirmed, so no cost in `founder-builders/` has changed. There is no `numbers.json` in this folder, so nothing was written to the CFO's file.

---

## 3. People

| Role | What they do | When needed | Ratio or trigger (set in test) |
|---|---|---|---|
| Ops lead | Final call on disputes; owns the SOPs; owns builder suspension | From day one | One person. Needs a trained backup. |
| Builder onboarding and verification | Checks builders against registries, calls references, arranges site visits | Before any builder is listed | One person per N applications per week (N to set) |
| Job coordinator | Checks briefs, runs bid windows, chases stage reports, logs change orders | From the first job | One per N active jobs (N to set) |
| Finance (branch B only) | Payment releases, refunds, reconciliation | Only if the platform holds money | Part-time at first; a full role after that |
| External: lawyer, inspector, accountant | Legal review, dispute inspections, tax | As needed | Retainer or per case; not priced |

**Slow first month:** one or two people can cover every role on a few jobs. But disputes and a builder stopping mid-job need a second trained person, so the ops lead must have a backup from the start.

**Wage assumption:** not set. Sources to check: the official minimum wage for the chosen country (VERIFY); typical pay for coordinators and onboarding staff from local job boards and the national statistics office (VERIFY); payroll taxes and contributions from the accountant (VERIFY).

---

## 4. Routines (SOPs)

Each routine is short, numbered, and should fit on one page. Times in brackets are set in the test.

### SOP-1: Builder verification (before listing)

1. Collect: legal entity or sole-trader details and tax number; licence or membership if the work type requires one in the chosen country (VERIFY which work needs what); liability insurance if available; list of at least [N] finished flats or houses with client contacts.
2. Check the company register for status (active, not in liquidation or insolvency) and the owner. Check the licence or membership register where one applies.
3. Check court records for recent disputes against the company (public court record search for the country).
4. Call at least [N] past clients. Record the answers on the same form.
5. Visit one finished job, or see photos and a stage acceptance from it, before listing.
6. Approve or reject within [X] days. Show the verified mark and past work on the profile. Re-verify every [period].

### SOP-2: Posting a job and the standard brief

The customer fills in the **standard job brief**. Required fields:

- Address, flat area, rooms, ceiling height, floor, building type.
- Current state of each room, with photos.
- Scope by room, as a checklist: demolition, screed, electrics, plumbing, walls, floors, ceilings, doors, kitchen, bathroom, and so on.
- Who supplies materials, and the grade or brand range for each finish.
- Drawings, if any, and whether a change to the layout (перепланировка or equivalent) is planned. This may need approval from the local authority (VERIFY).
- Start window, end deadline, and access arrangements.
- Budget range (optional, but it helps builders decide whether to bid).
- Acceptance criteria per stage, written in plain words.

The coordinator checks the brief is complete before any builder sees it. Incomplete briefs go back to the customer.

### SOP-3: Bid process and comparing bids

1. Bid window opens with the brief sent to all verified builders in the city (the number is the founder's; see section 2a).
2. Each builder bids on the **bid template**, which mirrors the brief line by line. Required per line: quantity, unit, unit price, material supplier and grade, and time in days. Also required: total time, exclusions, validity date, change-order unit rates, warranty period, and proposed payment stages.
3. **Complete-bid rule:** a bid with any unpriced line, or with no change-order rates, is marked incomplete and cannot be selected. The coordinator tells the builder what is missing.
4. The comparison sheet puts complete bids side by side. It shows the lowest bid, the spread, and each bid's exclusions. It does not rank by price alone.
5. Customer picks within [X] days after the window closes. The coordinator then fills the contract template with the chosen bid's values.

### SOP-4: Contract and first payment

1. Contract is generated from the template with the chosen bid. Both parties sign.
2. Payment schedule comes from the bid's stages. Branch A: customer pays the builder directly, and the platform records each payment. Branch B: customer pays the platform, which releases by stage after acceptance (SOP-6).
3. Platform keeps the signed contract and every stage record. These are the evidence in any later dispute.

### SOP-5: Change order

1. No work outside the signed scope without a written change order.
2. The builder fills the change order: what changes, why, the cost at the bid's unit rates, days added, and the effect on the deadline.
3. Customer approves before the work starts. The builder may refuse to start unapproved work.
4. The platform logs it and shows the customer a running total of all change orders against the original contract value on every approval.
5. Any change above [threshold, set in test] or above [% of contract] is reviewed by the ops lead before approval.
6. **Gap to close:** if a bid has no unit rates for changes, every later change is open to dispute. The bid template must make this a required field (section SOP-3 step 2).

### SOP-6: Stage acceptance and payment release

1. Builder files a stage report: photos, a short description, and a checklist against the stage's acceptance criteria.
2. Customer accepts or lists defects within [X] days. No reply after [X] days is recorded as accepted only if the contract says so (VERIFY that silence-as-acceptance is valid in the chosen country; do not rely on it until checked).
3. Branch B: payment released on acceptance. Branch A: acceptance recorded; customer pays the builder.
4. Defects are fixed and re-checked before the stage closes.

### SOP-7: Dispute

1. **Level 1 (coordinator, within [X] days):** talk to both parties, separately then together. Record the agreed fix in writing.
2. **Level 2 (ops lead, within [X] days):** review the brief, the bid, the contract, the stage reports, photos and messages. Decide the fix. Branch B: pause releases on the disputed stage only.
3. **Level 3 (independent inspection):** an external inspector checks the disputed work against the acceptance criteria. Cost split between the parties by a rule set in advance (not yet set; the platform must decide and show it in the contract).
4. **Level 4 (outside the platform):** the courts or the chosen country's dispute route. The platform hands over the file.
5. **What the platform cannot do:** force a builder to pay or finish, unless the contract and the country's law give it that power (VERIFY with the lawyer). The platform's job is to keep clean records, run the levels, and show the evidence.
6. Every dispute ends with a builder record update: note, warning or suspension.

### SOP-8: Builder stops mid-job

**Triggers (thresholds set in test):** no site activity or stage report for [N] days; a stage missed by [M] days; the builder says they will not finish; the customer reports abandonment.

1. **Freeze the job (same day):** no new change orders; no new payments to the builder (branch B: release paused; branch A: the platform cannot stop direct payments, so say so to the customer).
2. **Tell both parties the same day,** in writing, with the clause from the contract that applies.
3. **Inventory (within [X] days):** an independent inspector checks each completed stage against the signed acceptance records. Output: what is done, what is not, and what is defective.
4. **Choose the route:**
   - (a) Builder returns and finishes within an agreed window.
   - (b) Mutual termination. Work done is settled at the bid's unit rates.
   - (c) Replace the builder. Re-bid the remaining scope on the same brief, with the completed stages as the starting point. Needs a pre-verified replacement bench in the city (see section 2a).
5. **Money reconciliation:** paid minus the value of verified work done. The difference is the customer's claim against the builder. Branch B: the platform can pay out the verified value and hold the rest for the claim, if the contract and law allow it (VERIFY). Branch A: the customer's loss is recovered only by claim.
6. **Record the builder's status** (suspended or removed) and tell the other builders on the bench only what the rules allow (VERIFY data rules).

**Gap this exposes:** under branch A the customer carries most of the risk of a builder stopping mid-job. This is the strongest operational argument for the held-money model, and the reason the panel's buyers keep asking for it.

### SOP-9 (Weekly, replaces "reorder"): Builder supply check

1. Count verified builders per trade and per district in the launch city, against the number the founder set.
2. Count open bid windows and builders who did not bid on the last [N] briefs. Ask them why.
3. Recruit or verify to fill trades with gaps before the next brief goes out.
4. Review the week's disputes and suspensions by builder. Remove any builder with two or more confirmed disputes in a [period], or as the ops lead decides.

---

## 5. Tools

The smallest stack that runs the test. None is chosen. Published prices were not checked in this run.

| Function | Need | Start with | Later | Why |
|---|---|---|---|---|
| Intake and job tracking | Jobs, builders, stages, change orders, disputes | Spreadsheet plus a form | CRM or a simple job app | The board's test needs no app; build the app after the flow works by hand. |
| Documents | Brief, bid, contract, change order, acceptance | Shared document templates | Document generation from the platform | Templates must be lawyer-checked first. |
| E-signature | Contract signed by both parties | Service whose signature the country accepts (VERIFY) | Built-in signing | Signature validity depends on the country. |
| Messaging | Coordinator and parties talk | Email and one support inbox | In-app messages | Keep records; every message is dispute evidence. |
| Photo and stage reports | Stage evidence with dates | Shared folder or messaging group with a log | Upload form in the app | Date and location of photos matter in disputes. |
| Payments (branch B only) | Hold, release, refund | Bank or licensed partner | Automated milestones | Not chosen; needs the legal check first. |
| Bookkeeping | Fees, payments, tax | Accounting software chosen with the accountant | Integration with payments | Tax treatment differs by structure (VERIFY). |

---

## 6. Licences, permits and insurance (checklist, all VERIFY)

Rules differ by place and change. Each item must be confirmed with the authority named or a professional in the chosen country. **This is not legal advice.**

| # | Item | Why it matters | Confirm with | Status |
|---|---|---|---|---|
| 1 | Legal form and registration of the platform | Needed before any contract or payment | Company registry; accountant | Open |
| 2 | Tax registration and regime; tax on the fee and on pass-through payments | Affects pricing and the fee the CFO models | Tax authority; accountant | Open |
| 3 | Intermediary and contract terms (is the platform an agent, a broker, or a party to the contract?) | Decides the liability and the wording of every document | Lawyer; civil code of the country | Open |
| 4 | Escrow or held-payment rules: does the escrow law for construction contracts cover flat renovation, or only private house construction? | `competitors.md` cites Federal Law 186-FZ of 22.07.2024 (ИЖС, private houses). The sources read tie it to private houses. No equivalent for flat renovation was found. | Full law text on the official legal portal; lawyer | Open, blocking for branch B |
| 5 | Rules for handling customer money (payment agent or licensed provider) | Decides whether the platform can touch the money at all | Central bank or payment regulator; bank partner | Open, blocking for branch B |
| 6 | Consumer protection duties to private customers (who the seller is, the platform's liability, withdrawal rights) | Applies to every customer contract | Consumer protection authority; lawyer | Open |
| 7 | Personal data: collection, storage location, consent, retention | Briefs include addresses and property data | Data protection regulator; lawyer | Open |
| 8 | Builder licences and memberships for the work types offered (including any self-regulatory membership) | The platform should only list builders who hold what the work needs | Regulator's public register | Open |
| 9 | Renovation approvals: whether a layout change needs approval from the local housing authority, and how long it takes | Changes the timeline and the brief | Local housing authority | Open |
| 10 | Advertising rules for claims such as "verified", "guaranteed" or "protected payment" | The claims in section 0 are regulated | Advertising regulator; lawyer | Open |
| 11 | Insurance: platform liability; what builders must carry | Protects against a builder stopping mid-job or causing damage | Insurer or broker | Open |
| 12 | Statute on the dispute route: court and expert-opinion process for construction and renovation disputes | Sets the cost and time of Level 3 and Level 4 in SOP-7 | Lawyer | Open |

---

## 7. Risk register

Likelihood and impact are qualitative (High, Medium, Low). No numbers, because no data exists yet.

| # | Risk | Likelihood | Impact | Plan | Owner |
|---|---|---|---|---|---|
| 1 | A builder stops mid-job | Medium | High | SOP-8; pre-verified replacement bench; stage records from day one | Ops lead |
| 2 | Buyer and builder sign off-platform after the introduction (commission bypass) | High | High | Fee tied to verification, brief, comparison and stage acceptance; test the commission before fixing it | Founder; coordinator |
| 3 | A builder fakes credentials or past work | Medium | High | SOP-1 checks and site visit before listing; re-verify on a schedule | Onboarding |
| 4 | Bids are incomplete or cannot be compared | High | Medium | Bid template; complete-bid rule | Coordinator |
| 5 | Customer keeps changing scope | High | Medium | Change-order rule; running total on every approval | Coordinator |
| 6 | Stage acceptance dispute | High | High | SOP-6 and SOP-7 with records; independent inspection | Ops lead |
| 7 | Too few builders in the launch city | Medium | High | Set number signed before any customer is promised bids | Founder |
| 8 | Money or escrow claim made before legal check | Medium | High | Section 0 rule: no held-money claims until section 6 items 4 and 5 are confirmed | Founder; lawyer |
| 9 | One person holds the ops lead role | Medium | Medium | Trained backup from the start | Founder |
| 10 | Larger player (ДОМ.РФ, ПАЗЛ ДОМ, RERATE, Profi) adds renovation and held payments | Medium | Medium | Speed in one test city; the stage record and comparison become the lock-in | Founder (strategy, not ops) |

Also watch: a breach of customer address and property data (Low to Medium likelihood, High impact). Covered by item 7 in section 6.

---

## 8. Real costs for the CFO

`founder-builders/` has no `numbers.json`, so nothing was updated. These cost lines need a number before the CFO can run:

- Builder verification per builder: staff time, registry and court checks, reference calls, site visit.
- Coordinator time per job and per active job.
- Dispute handling time, and external inspector fees (who pays them is not yet set).
- Legal setup: contract templates and the section 6 checks.
- Payment partner fees (branch B only).
- Insurance: platform and builder requirements.
- E-signature and tools (section 5).
- Acquisition cost per customer (Monopoly lens; not in this file).

Each line needs a quote or a sourced figure. Do not enter an estimate as a fact.

---

## 9. Open questions (blocking first)

**Blocking the plan:**
1. Country and city (the references are Russian-language, but nothing in the brief fixes the market).
2. Money seam: branch A or B (section 0).
3. Legal results for section 6 items 4, 5 and 12.
4. Whether the first job type is flat renovation only (board's candidate).

**Set in the test (not yet known):**
5. Number of builders to sign before customers (founder).
6. Bid window length; response times; stage-report interval; acceptance period.
7. Thresholds for change orders, stuck jobs and builder removal.
8. Who pays for an independent inspection, and how it is split.
9. Commission level and what it is tied to (section 2a, section 0).

**Panel signal to test first:** all 20 simulated buyers passed. The main reasons were trust (verified builders, past work, a checkable track record) and price (a fee that is not stated). These are operations deliverables: the verified mark, the past-work view and the stated fee are needed before the first real test. The panel is simulated; confirm with real people.

---

## Next step

Run `/founder-launch` once the country and city are chosen, the money seam is decided, and the section 6 legal checks are back. Until then, the launch plan can only be a by-hand test: a brief form, a verified shortlist, a bid template, and a record of every handoff.
