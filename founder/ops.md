# Operations: Dabrundi (HoReCa Hub), stage 1, solo founder

How the business actually runs: one founder, building in Lovable, selling and supporting restaurants in Tbilisi. All amounts are in GEL; USD prices are converted at ~2.7 GEL per USD (an estimate; check the current rate).

## 1. The daily and weekly cycle

✱ = something a restaurant or diner sees.

**Every day**
1. **09:00–09:30: health check.** Look at the payment success rate, failed payments and yesterday's QR share at each live venue. Reply to overnight owner messages ✱ (reply within 2 hours in opening hours).
2. **09:30–13:00: build.** Product work in Lovable; one change at a time; test on a phone before publishing.
3. **13:00–15:00: admin.** Partner calls (Keepz, suppliers for the B2B board), contracts, bookkeeping, posting new board listings ✱.
4. **15:00–17:30: sales and setup visits** ✱. This is the quiet window between restaurant lunch and dinner (see `marketing.md`): demos, setup visits, staff training.
5. **18:00–21:00 on Fri/Sat: on call** ✱. Peak dinner service is when QR payments fail most visibly; keep your phone on.

**Every week**
- Monday: the three numbers from `marketing.md` (founding sign-ups, QR share of bills, cost per demo).
- Wednesday: moderate the boards (remove fake or out-of-date supplier, job and property listings) ✱.
- Friday: send each live owner a one-line weekly summary ✱ (bills paid by QR, new and returning guests, the average dish rating).
- Sunday: back-up check and an app update window, outside service hours.

## 2. Suppliers

| Input | Options to contact | Published price / how to get it | Terms / notes |
|---|---|---|---|
| **QR payment partner** | 1. **Keepz**, licensed by the National Bank of Georgia ([Omno summary](https://omno.com/payment-methods/keepz/), [Credo Bank page](https://credobank.ge/en/services/keepz-qr-terminal)) 2. **Bank of Georgia** e-commerce / link payments ([BoG API docs](https://api.bog.ge/docs/en/link-payment/introduction)) 3. **TBC Bank** merchant e-commerce | Keepz: free terminal; one user reports **~2.5%** per payment (not official). Banks: **quote only** | **Get in writing:** fee per payment, tip handling, payout time, refunds, API/webhook access, and **whether you get a revenue share.** No signed deal = don't name the partner in public |
| **App builder** | **Lovable** ([pricing](https://lovable.dev/pricing), [plans](https://docs.lovable.dev/introduction/subscription-plans)) | Pro: **25 USD / 100 credits**, **50 USD / 200 credits** a month; annual billing ~17% cheaper | Plan on 200 credits while building (**~135 GEL**); drop to 100 after launch |
| **Database / backend** | **Supabase** ([pricing](https://supabase.com/pricing)) | Free 0; **Pro 25 USD a month** (~70 GEL): 8 GB database, 100k monthly users, 7-day backups | Move to Pro before the first real payment (the Free plan pauses inactive projects and has no backups) |
| **SMS to guests** | **Messaggio** ([Georgia prices](https://messaggio.com/sms-gateway-api/georgia/)); a local Georgian SMS provider (quote) | ~**0.127 EUR per SMS** (~0.37 GEL) on all Georgian networks | SMS is expensive: a 300-guest message costs ~110 GEL. **Include 8 SMS per restaurant a month** (as in `numbers.json`); the rest go by email, wallet pass or WhatsApp link, plus **paid SMS packs** for owners who want more |
| **Email** | Resend, Brevo or similar (quote / free tier) | Free tiers cover early volume | Use for the owner's weekly summaries and guest offers |
| **Table stands (QR)** | 2–3 Tbilisi print shops (quote) | **~6 GEL each** in `numbers.json` (estimate) | Order samples first; acrylic or laminated card; 2-week lead time; ~450 stands for 30 founding venues |
| **Domains** | A .ge registrar (via nic.ge); any .com/.app registrar | Quote | Register `dabrundi.ge` / `.com` / `.app` before printing anything (`brand.md`) |

**What changed in the CFO numbers** (`numbers.json` updated):
- **Lovable:** 70 → **135 GEL a month**, using the published 200-credit plan.
- **Supabase:** 70 GEL confirmed.
- **SMS:** labelled at its real per-message price, capped at 8 per restaurant.

The CFO re-run gives:

| | Your plan | Lean plan |
|---|---:|---:|
| Break-even (paying restaurants) | **115** | 43 |
| Year 1 operating result | **−11,218 GEL** | +15,782 GEL |
| Cash needed | **~22,600 GEL** | ~11,500 GEL |

(Your plan was 112 / −10,438 GEL / ~22,200 GEL before this change.)

## 3. People

**Stage 1 (now until ~60 paying restaurants): you, alone.** No wages in year 1 (`numbers.json`).

| Your week | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|---|---|---|---|---|---|---|---|
| 09:00–13:00 | Build + numbers | Build | Build + board moderation | Build | Build | — | Back-up / update |
| 13:00–15:00 | Admin / partners | Admin | Admin | Admin | Owner weekly summaries | — | — |
| 15:00–17:30 | Visits / setups | Visits | Visits | Visits | Visits | Pilot check-ins | — |
| 18:00–21:00 | — | — | — | — | On call | On call | — |

**Launch month (Feb 2027):** ~8 visits a day on Tue/Thu, setups on Mon/Wed/Fri. Cut build time to the mornings only.

**When to hire** (the trigger, not a date):
- **More than ~25 live venues, or support taking >1 hour a day:** add a part-time sales/onboarding helper. It's in the CFO's base plan at 1,500 GEL a month; the lean plan leaves it out.
- **Payment-related bugs you can't fix in Lovable:** a freelance developer by the hour.
- **Any employee or contractor:** check payroll tax and contracts with an accountant (Georgian rules apply; this isn't tax advice).

## 4. Routines (one page each)

### A. Setting up a restaurant (one visit, ~60 minutes)
1. Before the visit: create the venue account; load the menu (from their QR menu or a photo); print a stand for each table.
2. Arrive at 15:00. Sign the founding agreement: the private-ratings clause, the data-ownership clause and the payment partner's fee sheet attached.
3. Connect the owner's payout account with the payment partner. Do a **1 GEL live test payment** and refund it.
4. Place the stands. Test-scan from 3 tables with your own phone.
5. Train the staff (30 minutes): how a guest pays; how tips reach the waiter; what to say ("You can pay here, no app needed"); what to do if a payment fails (use the terminal, message you).
6. Turn on the loyalty reward the owner chose. Leave a one-page staff card.
7. Next day: message the owner with the first-day numbers.

### B. A diner pays (what must happen every time)
1. The guest scans → sees the bill in their language → pays with card, Apple Pay, Google Pay or bank → adds a tip if they like.
2. The waiter sees "Paid ✓" on their phone or the venue screen within seconds.
3. The guest gets one-tap dish ratings → the rating goes **privately** to the owner → happy guests get the Google/Tripadvisor link.
4. **If the payment fails:** the guest sees "Pay with the waiter instead". No double charge. The incident is logged for the morning health check.

### C. Handling a complaint (owner or diner)
1. Reply within 2 hours in opening hours: name the problem back to them.
2. Fix the immediate issue (refund through the payment partner; re-train staff; correct the menu).
3. Find the cause. Write one line in the incident log.
4. Tell them what changed, by name and with a date (the template is in `brand.md`, touchpoint 5).
5. If the guarantee applies (fewer than 1 in 5 bills paid by QR in the first paid month), apply it without being asked.

### D. Week closing
1. Reconcile: the payment partner's payout report against bills recorded in Dabrundi, per venue. Flag any differences.
2. Send each owner their weekly summary.
3. Check founding spots left; update the landing page count (the honest number).
4. Back up the database (Supabase Pro includes 7 days; download a weekly copy too).

### E. Monthly
1. Bill subscriptions (from month 4 for founding venues). Chase failed card payments within 3 days.
2. Order stands for new venues.
3. Review the SMS spend per venue against the 8-SMS allowance; offer paid packs where it's over.
4. Bookkeeping to the accountant; tax filings (see §6).

## 5. Tools (smallest stack)

| Job | Tool | Price | Why |
|---|---|---|---|
| Build the app and web pages | Lovable | 50 → 25 USD a month | You build alone; React + Supabase |
| Database, auth, storage | Supabase Pro | 25 USD a month | Backups, no pausing |
| Guest payments | Keepz or a bank (§2) | Fee per payment (quote) | Licensed; no app for guests |
| Collecting subscriptions | The same partner's recurring/link payments, or a bank e-commerce account | % per charge (quote; ~2% assumed in `numbers.json`) | One provider is simpler |
| SMS / email | Messaggio (or a local provider) + a free-tier email service | ~0.37 GEL per SMS | Capped SMS, cheap email |
| Bookkeeping | Your accountant's system / spreadsheet | 300 GEL a month (estimate) | — |
| Support | WhatsApp Business (free) + shared inbox | 0 | Owners already use WhatsApp |
| Planning | Google Calendar + Sheets (free) | 0 | Visit schedule, the weekly numbers |

## 6. Registration, tax, data, contracts (checklist)

Rules differ and change. **Confirm each item with the authority or a professional. This isn't legal or tax advice.**

- [ ] **Business registration** at a Public Service Hall: individual entrepreneur or LLC (National Agency of Public Registry, napr.gov.ge). An LLC separates your personal liability from the platform's; ask an accountant which fits.
- [ ] **Small Business Status (1% turnover tax)**, available to individual entrepreneurs with turnover up to **500,000 GEL** a year ([Andersen Georgia](https://ge.andersen.com/1-tax-regime/), [legally.ge](https://www.legally.ge/incorporate/small-business-status)). Confirm with the Revenue Service (rs.ge).
- [ ] **VAT:** registration is required once turnover passes **100,000 GEL in any 12 months** (18%) ([Andersen Georgia](https://ge.andersen.com/1-tax-regime/)). Year 1 revenue in `cfo.md` is ~37,000 GEL, but **track it monthly**, and decide whether prices include VAT before you reach it.
- [ ] **Personal data:** Georgia's Law on Personal Data Protection has been in force since **1 March 2024**; the regulator is the Personal Data Protection Service ([personaldata.ge](https://personaldata.ge/en); [Andersen summary](https://ge.andersen.com/personal-data-protection-georgia/)).
  - Restaurants are the **controllers** of their guest data and you're the **processor**: sign a data processing agreement with each venue.
  - Give guests a privacy notice and a clear opt-in before any marketing message.
  - Have a breach-notification plan.
  - Ask a lawyer whether you need a data protection officer.
- [ ] **Payments:** you don't hold guest money; the licensed partner does. Keep it that way, or you'd need your own National Bank licence.
- [ ] **Contracts:** the restaurant agreement (subscription, guarantee, private-ratings and data-ownership clauses, termination, exporting data on exit), the board terms (no fake listings, moderation rights), the diner terms and privacy notice.
- [ ] **Advertising and consumer rules** for the guarantee and "free" claims: have a lawyer check them.
- [ ] **Trademark and domains:** `brand.md` §1.
- [ ] **Insurance:** ask a broker about professional liability and cyber cover once payments are live (optional in stage 1; quote).

## 7. Risk register

| # | Risk | Likelihood | Impact | Plan |
|---|---|:-:|:-:|---|
| 1 | **Too few restaurants pay** after the free months (the panel: most "yes" = trial only) | High | High | Run lean (break-even 43); the guarantee and weekly numbers; sell to the best-fit segment first (`marketing.md`) |
| 2 | **No payment partner deal**, or the fee is higher than the venues' terminal | Medium | High | Approach Keepz, BoG and TBC at once; launch reviews and loyalty on the paper bill (a QR on the receipt) if payment is delayed |
| 3 | **A QR payment fails during a Saturday dinner rush** | Medium | High | Fallback to the terminal shown to the guest; on call Fri/Sat; webhook monitoring; refund within 24 hours |
| 4 | **Waiters resist** (tips, extra steps) | Medium | Medium | Tip to the waiter by default; 30-minute training; share the waiters' tip numbers with the owner |
| 5 | **You're the only person** (illness, burnout) | Medium | High | Written routines (§4); a freelancer on standby; a one-page "if I'm off" note for venues |
| 6 | **A data breach or misuse** of guest data | Low | High | Supabase row-level security; least access; data processing agreements; breach plan (§6) |
| 7 | **Wox, Keepz or a bank copies** the loop (`competitors.md` §6) | Medium | Medium | Move fast in a few districts; own the venue relationships and the case studies; integrate rather than fight |
| 8 | **A bad public review of a venue** made through Dabrundi | Low | Medium | Private-by-default ratings; the owner approves what goes public; written in the contract |
| 9 | **Lovable limits** (complex payment logic, performance) | Medium | Medium | Keep payment logic with the partner; plan a freelancer review before 50 venues |
| 10 | **SMS costs run over** | Medium | Low | 8-SMS cap; email and wallet first; paid SMS packs |

## Open questions (quotes needed)
- Payment partner: the fee per payment, payout time, tips, refunds, API access, **revenue share** (Keepz, BoG, TBC).
- A local Georgian SMS provider's price against Messaggio.
- Printing: stand samples and the price per 450.
- An accountant: individual entrepreneur or LLC, VAT, monthly fee.
- A lawyer: contracts, data processing agreement, guarantee wording, data protection officer.
