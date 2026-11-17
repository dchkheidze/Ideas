# Pricing: HoReCa Hub (restaurant side)

Prices are in GEL per month, VAT treatment to be confirmed. Note: the curve tool prints "$", but every panel answer was in GEL. Sources: `founder/pricing-curve.md` (100 simulated owners), `founder/competitors.md`, `founder/panel/results.md`.

## 1. The price: Guest Loop at **39 GEL / month**

**What the buyers said** (100 simulated Tbilisi owners; this picks what to test, it doesn't prove anything):

| Point | GEL | Meaning |
|---|---:|---|
| PMC | 15 | below this, it looks too cheap to be any good |
| OPP | 15 | least resistance |
| **IPP** | **39** | as many call it a bargain as call it expensive |
| PME | 80 | above this, too many won't buy at all |

At each candidate price, the share of owners who say it's getting expensive, and who say it's too expensive:

| Price | "Getting expensive" | "Too expensive" |
|---:|---:|---:|
| 29 | 0% | 0% |
| **39** | **4%** | **0%** |
| 49 | 21% | 0% |
| 59 (first pitch) | 59% | 4% |
| 79 | 76% | 21% |

Median answers by segment:

| Segment | Bargain | Getting expensive | Too expensive |
|---|---:|---:|---:|
| Small cafés | 25 | 50 | 80 |
| Mid-size restaurants | 25 | 50 | 90 |
| Upscale and tourist venues | 39 | 99 | 160 |
| Early tech adopters | 35 | 80 | 120 |

**Against competitors** (from their own price pages, Nov 2026):

| Product | What it includes | GEL / month |
|---|---|---:|
| Wox Loyalty | Wallet stamp cards, SMS/email | 24 / 39 / 59 |
| QRMENUS | QR menu; Business plan adds waiter calls and table orders | 0 / 39 / 79 |
| SQR | QR menu + POS | from 30 |
| Keepz | QR payment | free terminal, ~2.5% per transaction (as one user reported) |

**Why 39:** it's the panel's balance point, only 4% of owners call it "getting expensive", and it equals Wox Loyalty's middle plan and QRMENUS Pro. An owner sees "same price as loyalty alone, but I also get payment, verified feedback and guest profiles". 59 GEL put 59% of owners into "getting expensive"; 39 removes price as an objection, so the sales conversation can focus on the real blockers (trust, POS, tips).

**Margin: not yet known.** There's no `founder/numbers.json` yet, so the CFO tool can't run. The cost of serving one restaurant a month still needs real figures: hosting, SMS and email sends, payment-partner costs if any land on HoReCa Hub, support and onboarding time. **`/founder-cfo` must confirm that 39 GEL covers these** before it's final. Don't take the price below that cost to win customers unless the CFO says how long the business can afford it.

**The payment fee is separate and must be shown.** The panel's biggest single blocker was an unnamed partner with an unknown fee. Publish the Keepz (or bank) rate next to the plan price, and show it against a typical card terminal rate. Never hide it as "fee on top".

## 2. The ladder

| Tier | GEL / month | What's in it | Why step up |
|---|---:|---|---|
| **Free: Listing** | 0 | Diner-app listing; HoReCa boards (suppliers, jobs, premises); QR pay at the table at the partner's fee | Gets the restaurant in, and the boards are useful on day one |
| **Guest Loop** | **39** | Everything in Free + **private** dish feedback (owner sees it first, chooses what goes public) + guest profiles (first visit or regular) + a ready-made loyalty reward + tip button paid to the waiter + guest data export | The owner sees who comes back and gets feedback only from guests who paid |
| **Guest Loop Pro** | **99** | Everything in Guest Loop + campaigns and event messages to the restaurant's own guests + a Google/Tripadvisor review prompt after payment + featured placement in the diner app + POS link (Wox/SQR, once built) + multiple venues and staff accounts | For upscale and tourist venues: their median "getting expensive" is 99 GEL, and they asked for the Google review prompt |

**Annual billing:** pay 10 months, get 12 (Guest Loop 390 GEL a year, Pro 990 GEL a year). This is a real discount, not a fake anchor.

The Free tier includes QR payment on purpose. Every payment creates guest data and verified feedback, which is the content the paid tiers sell and the diner app needs. Making payment free removes the "second fee" objection for owners who never upgrade.

## 3. The opening offer: **Founding Restaurants**

- **For the first 30 restaurants in Tbilisi, until 31 March 2027** (whichever comes first).
- 3 months of Guest Loop free, then **29 GEL a month locked for 12 months** (instead of 39).
- In return: a short case study after 90 days (QR share of bills, repeat-guest rate, tips), with the owner's permission.
- Why this works: it has a hard cap and an end date, so it doesn't teach owners to wait for discounts. It also produces the "proof from a similar Tbilisi venue" that the panel kept asking for.

## 4. What to test with real owners

1. **Guest Loop at 39 vs 49 GEL.** Show half of the restaurant owners you meet in person, or two versions of a landing page, each price, and ask for a written pre-commitment (founding-restaurant sign-up). Pick the price with more sign-ups unless 49 loses fewer than 1 in 5. The 49-GEL arm is worth testing because the IPP comes from simulated buyers.
2. **Pro at 79 vs 99 GEL** with upscale and tourist venues only (Old Tbilisi, Sololaki, Vake).
3. **What to track either way:** sign-ups, the share of bills paid by QR in the first 30 days, and how many owners keep paying after the free months. The real price test is month 4, not the sign-up.

## 5. The panel's price objections, word for word (for marketing)

1. *"I already pay for Wox and a card terminal, and 59 lari a month plus another transaction fee on top is real money for a place my size."* (P001)
2. *"I might scan the free months out of curiosity, but I would not pay 59 lari a month plus another transaction fee on top of what my bank already takes."* (P005)
3. *"Three free months is nice, but after that it's 59 lari plus another fee on every bill, and I don't see it paying for itself."* (P014)

The pattern: owners don't object to the monthly price on its own. They object to **two fees stacked together** and to **no proof it pays back.** Answer with: the fee named and compared, payment included free, and a payback example (e.g. at 39 GEL, how many extra repeat visits cover it; the CFO will supply the number).

## Open items

- [ ] `/founder-cfo`: cost to serve one restaurant per month, margin at 29 / 39 / 99 GEL, break-even number of paying restaurants.
- [ ] Get a written fee quote from Keepz (and one bank) for restaurant QR payments, and check whether HoReCa Hub can earn a revenue share on them.
- [ ] Confirm VAT treatment of the subscription price.
