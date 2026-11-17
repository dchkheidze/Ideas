> **Update after /founder-ops (17 Nov 2026):** Lovable is now priced from its published plans: 200 credits at 50 USD ≈ 135 GEL a month during the build. Supabase is confirmed at 25 USD. New results: break-even **115** paying restaurants (lean plan: **43**); year 1 **−11,218 GEL** (lean: **+15,782 GEL**); cash needed **~22,600 GEL** (lean: **~11,500 GEL**). The tables below are from the earlier run; re-run the tool for the full current tables.

# CFO's note: HoReCa Hub (all amounts in GEL; the tool prints "$")

The table below counts **paying restaurants per month**, not per day; the tool's "a day" means "that month". Most inputs are **estimates** (see `cfo-sources.md`), because there are no quotes yet. This isn't financial, tax or legal advice: have an accountant check the company structure, VAT on the subscription and tax before money moves.

**The margin.** Each paying restaurant leaves **31.25 GEL a month** after its own costs (84%), at a blended price of 37 GEL: 30 founding restaurants at 29 and the rest at 39. Fixed costs are **3,500 GEL a month**, of which 3,000 is the marketing and sales-helper budget I suggested. **Break-even is 112 paying restaurants.** At your target of 150, the profit margin is **21%**.

**Year 1 on your plan** (0 paying in months 1–3 because of the free months, 100 by month 6, 150 by month 11): an operating loss of **10,438 GEL**, or **17,588 GEL** after the 7,150 GEL startup spend. It turns profitable from **month 7**. **Cash needed before it pays for itself: about 22,200 GEL.**

**The line to watch is how many restaurants pay**, i.e. the ramp. The panel says about 22% of owners would *try* it, and almost all of them mean "the free trial", not "pay". If you reach only half your target (75 paying), year 1 loses **26,219 GEL** and you need **33,369 GEL** of cash. At a third (50 paying), it loses **31,584 GEL** and needs **38,734 GEL**. One hundred and fifty paying restaurants in 6 months also means signing roughly 700 trials if a fifth of them convert. That's a lot of in-person visits for one founder.

**Three ways to improve the margin** (each figure comes from a tool run):
1. **Run lean in year 1:** drop the sales helper and halve ads to 750 GEL. Fixed costs fall to 1,250 GEL, break-even drops to **40 paying restaurants**, year 1 makes **+16,562 GEL**, and cash needed falls to **~11,200 GEL**. The trade-off: you do all the sales yourself, so the ramp is at more risk.
2. **Earn a share of QR payments.** If a Keepz/bank revenue share brought in ~20 GEL per restaurant a month (that's an assumption, not a quote), it works like a 57 GEL price: break-even falls to **69**, year 1 makes **+9,762 GEL**.
3. **Sell Pro (99 GEL) to upscale venues.** If about a fifth of paying restaurants took Pro, the blended price would be ~49 GEL: break-even falls to **81**, year 1 makes **+1,682 GEL**.

Price risk: cutting the price by 10% raises break-even to 128 restaurants. Pricing everyone at the 29 GEL founding price would need 151 restaurants to break even, which is more than your whole target.

**The board's money conditions:**
- [ ] *Payment processing cost and who pays it.* **Open.** Get a written Keepz/bank quote and a revenue-share answer.
- [ ] *Cost to acquire a restaurant and payback.* **Partly open.** At the suggested budget, 3,000 GEL a month of marketing plus sales ÷ new paying restaurants. At ~30 new paying a month, that's ~100 GEL each, paid back in ~3 paying months. Real figures come from the pilot.
- [ ] *Paid pre-commitments at a real price.* **Not yet.** Break-even says you need about 112 paying restaurants at the current costs (40 on the lean budget).
- [ ] *An affordable guarantee.* **Not set yet.** `/founder-offer` can test one. Each paying restaurant earns 31 GEL a month, so "one month free if X" costs about 37 GEL in lost revenue.

---

# Unit economics: HoReCa Hub (Guest Loop subscription, Tbilisi). NOTE: the tool says 'per day'; here days_per_month = 1, so every 'per day' figure means 'paying restaurants in that month'.

Every number below comes from the input file. Nothing is looked up or guessed.

## One paying restaurant-month

| line | per paying restaurant-month |
| --- | ---: |
| Price | $37.00 |
| Hosting/database share per restaurant (estimate) | -$2.00 |
| SMS and email to guests (estimate) | -$3.00 |
| Card fee on collecting the subscription, ~2% of 37 GEL (estimate) | -$0.75 |
| **Contribution** (what each paying restaurant-month leaves to pay the fixed costs) | **$31.25** (84%) |

## The margin that matters

Fixed costs: $3,500 a month (Lovable subscription (estimate, ~25 USD) $70, Supabase / backend hosting base plan (estimate, ~25 USD) $70, Domain, email, SMS gateway base fee (estimate) $60, Accountant, part-time (estimate) $300, Marketing: Instagram/Facebook ads + owner events (suggested budget) $1,500, Part-time sales/onboarding helper, commission-heavy (suggested) $1,500, Founder salary (none in year 1, per founder) $0).

- **Break-even: 112 paying restaurant-months a day.** Below that you lose money every month.
- **Profit margin at your plan** (150 a day): **21%** of every sale, after every cost.

## Year 1, month by month

| month | paying restaurant-months a day | revenue | profit | cumulative (after $7,150 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $0 | -$3,500 | -$10,650 |
| 2 | 0 | $0 | -$3,500 | -$14,150 |
| 3 | 0 | $0 | -$3,500 | -$17,650 |
| 4 | 30 | $1,110 | -$2,562 | -$20,212 |
| 5 | 60 | $2,220 | -$1,625 | -$21,838 |
| 6 | 100 | $3,700 | -$375 | -$22,212 |
| 7 | 115 | $4,255 | $94 | -$22,119 |
| 8 | 125 | $4,625 | $406 | -$21,712 |
| 9 | 135 | $4,995 | $719 | -$20,994 |
| 10 | 145 | $5,365 | $1,031 | -$19,962 |
| 11 | 150 | $5,550 | $1,188 | -$18,775 |
| 12 | 150 | $5,550 | $1,188 | -$17,588 |

- **Year 1 operating profit: -$10,438** on $37,370 of revenue.
- After the $7,150 startup spend: -$17,588.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$22,212**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 21% | 112 | -$10,438 |
| Price -10% | 13% | 128 | -$14,174 |
| Volume -20% | 6% | 112 | -$16,750 |
| Unit costs +15% | 19% | 116 | -$11,309 |

## Red flags

- Year 1 loses money on operations (-$10,438).
- The startup spend is not earned back within year 1.
