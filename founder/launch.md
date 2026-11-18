# Launch plan: Dabrundi (HoReCa Hub), Tbilisi

- **Launch day: Monday 1 February 2027** (as in `marketing.md`). It's the earliest realistic date: about 10 weeks of building in Lovable, a payment-partner agreement, and 3 pilot venues live before launch.
- **The founding offer** runs until **31 March 2027** or 30 restaurants, whichever comes first (`pricing.md`).
- Owner: **you** for every task, unless a professional is named.

## 1. Test before you spend: "Founding pre-sign-up"

**What:** in December, before building the full product, sell the Founding Restaurants offer (`pitch.md`) face to face, using:
- a clickable prototype made in Lovable (the table QR → pay → private rating → owner dashboard)
- the one-page agreement
- a **refundable 29 GEL deposit** (the first founding month's price), paid by bank transfer. It's credited to month 4, or refunded in full if you don't launch by 1 March 2027.

**Why this test:** a deposit is the cheapest **real money** signal for a subscription where the first 3 months are free. A "yes" with no money is what the panel already gave you.

**Success line, written before the test:**
- **≥ 10 signed pre-sign-ups with a deposit from 60 owner conversations in 3 weeks (14 Dec 2026 – 3 Jan 2027)**, i.e. ≥ 17%.
- The panel's 22% sign-up rate is an upper bound, and most of those were trial-only. So **10 of 60 = go**; **5–9 = go, but fix the offer first**; **fewer than 5 = stop and go back to `/founder-offer` or `/founder-pricing`** before building more.
- Also record: the most common reason for "no" (compare with the panel's top three: trust, habit, need), and which segment says yes (the panel predicts early adopters and upscale or tourist venues).

**Cost of the test:** printing ~50 GEL plus your time. No big spending (stands, ads, Supabase Pro) until the test passes.

## 2. The countdown (weekly blocks)

**Critical path (★):** these tasks move the launch date if they slip.
★ payment-partner agreement → ★ payment integration → ★ pilot venues live → launch.

| Week | Legal and money | Build | Partners and suppliers | Brand and marketing |
|---|---|---|---|---|
| **23–29 Nov 2026** | Meet an accountant: individual entrepreneur or LLC, VAT, fee (`ops.md` §6) | Lovable plan to 200 credits; data model (venues, bills, guests, ratings) | ★ **Email Keepz, Bank of Georgia and TBC** for merchant terms, tips, payouts, API and revenue share | Check the trademark and domains for **Dabrundi** (`brand.md` §1); register domains and handles |
| **30 Nov – 6 Dec** | **Register the business** (Public Service Hall); open a business bank account | Clickable prototype for the test | ★ Partner meetings; ask for sandbox/test API access | One-page agreement + leaflet in Georgian, English and Russian |
| **7–13 Dec** | A lawyer drafts the restaurant agreement, data processing agreement and guarantee wording | Prototype done; landing page draft | Contact 2 wholesalers for the supplier board | List of 80 table-service venues in Sololaki and Old Tbilisi |
| **14 Dec – 3 Jan** | Deposits go into the business account | Build the payment flow on the partner's sandbox | ★ **Pick the partner and sign** (target 31 Dec) | **Run the pre-sign-up test** (§1): 60 conversations at 15:00–17:30 |
| **4–10 Jan 2027** | **Go / fix / stop decision** on the test result | ★ Live payments; tips; failure fallback | Order 30 sample stands (2-week lead) | If go: brand designer for the logo (`brand.md` §3) |
| **11–17 Jan** | Privacy notice and diner terms published | Private ratings, guest profiles, loyalty reward, owner dashboard | Supabase to Pro before the first real payment | Instagram @dabrundi set up (no posts yet) |
| **18–24 Jan** (L−14) | Sign agreements with the 3 pilot venues | ★ **Soft open:** 3 pilot venues set up (routine A in `ops.md`) | Stands for the pilots arrive | Marketing calendar starts (`marketing.md` §4): first post, discovery chats |
| **25–31 Jan** (L−7) | — | Fix whatever the pilot weekends break | Wholesalers' listings on the supplier board | Landing page live with the fee printed; Meta ads on (750 GEL a month) |
| **Mon 1 Feb 2027** | **LAUNCH**: Founding Restaurants open | | | |

**Soft open = the 3 pilot venues** (friendly owners from the December test), running real bills for 1–2 weekends before launch.

**If the critical path slips:**
- **No signed payment partner by 10 Jan:** move launch to 15 February, or launch "reviews and loyalty only", with the QR printed on the paper bill and no payment (`ops.md`, risk 2).
- **Integration not stable on the pilot weekends:** launch with the pilots only, and hold the public opening a week.

## 3. Launch day run sheet: Monday 1 February 2027

| Time | Where | What |
|---|---|---|
| 08:30 | Home | Health check: payments working at all 3 pilots (a 1 GEL test payment + refund); founding spots counter on the landing page shows 27 of 30 left (the 3 pilots are counted) |
| 09:30 | Instagram, landing page | **Launch post**, hook 9: *"30 Founding Restaurants. 3 months free, then 29 GEL locked for a year. Until 31 March."* (Georgian/English) |
| 10:00 | WhatsApp | Personal message to every owner from the December test who said "maybe" or paid a deposit: "We're live. Your setup slot: [date]." |
| 10:30 | Meta ads | Switch the ad sets to the launch creative (hooks 1, 3) |
| 11:00 | Partners | Message the 2 wholesalers and the payment partner: "Live today. Here's the link to share." |
| 12:00–14:30 | Build | Watch for errors; no new features today |
| **15:00–17:30** | **Sololaki** | **8 visits** (hook 6 as the opening line); book setup slots for the week |
| 18:00–21:00 | On call | Pilot venues' dinner service; phone on |
| 21:30 | Home | Note sign-ups, demos booked, problems; the plan for Tuesday |

**If something breaks** (from the `ops.md` risk register):
- **A payment fails at a pilot:** guests pay through the terminal; refund any double charge the same evening; message the owner before they notice.
- **The landing page or app is down:** post "back shortly" on Instagram; take sign-ups by WhatsApp.
- **A bad public post or review:** reply within 2 hours, by name, with what changed (`brand.md` touchpoint 5).

## 4. The first 30 days (1 Feb – 3 Mar 2027)

No founding restaurant pays in the first 30 days (they get 3 months free). The money test is **May 2027**, when the first founding venues start paying 29 GEL. For the first 30 days, track the steps that lead to paying.

| Number (weekly) | Target | Triggers a change if… | Source |
|---|---|---|---|
| Founding sign-ups (total) | 10 by 14 Feb · 20 by 1 Mar · 30 by 31 Mar | Fewer than 2 a week for 2 weeks | `marketing.md` §7 |
| Live venues (set up, taking QR bills) | Sign-ups set up within 7 days | A setup backlog of more than 5 | `ops.md` routine A |
| Share of bills paid by QR at live venues | ≥ 1 in 5 (the guarantee level) | Below 1 in 10 after 2 weeks at a venue | `offer.md` guarantee |
| Ad cost per demo booked | ≤ 60 GEL | Above 94 GEL (the most per trial) | `marketing.md` §6 |
| Path to paying restaurants | 43 paying = lean break-even; 115 = break-even with the helper and full ads | Founding sign-ups on track for fewer than 30 by 31 March | `cfo.md` (updated after ops) |

**Reviews:**
- **Day 7 (8 Feb):**
  - Are pilots and new venues getting at least 1 in 10 bills by QR?
  - What's the #1 reason owners say no in visits? Is it the same as the panel's (trust)?
  - Is setup taking more than 60 minutes?
- **Day 14 (15 Feb):**
  - Are we at 10 sign-ups?
  - Which district and hook bring the most demos?
  - Are ads under 94 GEL per trial? If not, move the money to partners and visits.
  - Has any venue's tips gone down? (The waiters' risk.)
- **Day 30 (3 Mar):**
  - Are we on track for 30 founding venues by 31 March?
  - The QR share and repeat-guest rate at the first venues: real numbers for the case studies.
  - Do owners use the private ratings and the loyalty reward, or only payment? That decides what to sell at 39 GEL in May.
  - Re-run `/founder-cfo` with real sign-up and setup numbers.

**After day 30:**
- **May 2027:** the first founding venues start paying. **Watch trial→paid**; the marketing plan assumed 1 in 2.
- **When 30+ venues take QR payments:** start diner-side marketing (`marketing.md`).
