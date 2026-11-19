# Pricing: builder marketplace (flat renovation first)

Price is **not decided**. This note recommends a range to test and what to test. It does not set a price, and it has no margin or market figures because the CFO step has not run (there is no `numbers.json` in this folder).

## Read this first: what the price answers are

- **The buyers were not shown any price.** The pitch says "Price: not decided yet" (`pitch.md`). Every price answer is the buyer's own guess at what they would expect to pay, not a reaction to an offered price. Treat the range below as **low confidence**. It shows where simulated buyers' expectations sit, not where they would accept an offer.
- **The unit is not defined.** The panel question asks for "the price" with no unit and no basis: a flat platform fee, a fee per job, a monthly fee, or a percentage commission are all possible. The board's working model is a commission on the contracted value (`idea.md`), which is a percentage. A flat-currency answer does not map onto a percentage. Fix the basis before any test.
- **Currency is assumed to be RUB.** The competitor and market sources are Russian, but the answers carry no currency field. The script labels its output "$" because that label is hard-coded; read those numbers as unlabelled units, not dollars.
- **Every simulated buyer passed (0 of 20 buy).** 16 of 20 gave trust as the reason, 3 price, 1 habit. The price answers come from people who distrust the offer, so they may measure how much a buyer would pay to be vetted at all, not the fee itself.
- **Two answers were dropped** (P014 and P017 gave a 0 for "too cheap", which the script treats as incomplete). 18 answers were used.

## 1. Van Westendorp range (from `pricing-curve.md`)

| point | value | meaning |
| --- | ---: | --- |
| PMC | 102 | below this, too many think it is too cheap to be good |
| OPP | 205 | least resistance: as many say too cheap as too expensive |
| IPP | 298 | as many call it a bargain as call it expensive |
| PME | 604 | above this, too many say it is too expensive to buy |

Acceptable range: **about 102 to 604** (unit unconfirmed). Median answers: too cheap 50, a bargain 150, getting expensive 500, too expensive 1,000.

The range is wide (about six-fold). Low confidence for the reasons above.

## 2. What competitors charge (`competitors.md`)

Like-for-like comparison is difficult, because the sources do not give the same kind of price:

- **Platform fee to the contractor:** ПАЗЛ ДОМ publishes 20,000 RUB per object, 1% of each finance tranche, and 3 to 5% per partner lead. This is for new private houses, not flat renovation. It is the only explicit fee schedule found.
- **Customer-side fee:** free on every page that states it (RERATE, Profi). YouDo's safe-deal commission rate was not found.
- **Job prices (not platform fees):** Profi search-result "from" prices for Moscow renovation run about 7,000 RUB per m² for finishing. These are list prices, not completed jobs.

The buyers' range sits far below any platform fee in the sources. That may be because buyers guessed a flat fee, not a percentage. Compare against the commission model once it is chosen.

## 3. What the business needs

Not computed. There is no `numbers.json` and no CFO run, so no unit margin or break-even is given here. Run `/founder-cfo` on the chosen basis before choosing a test price.

## 4. Recommendation

1. **Fix the basis first.** Choose one: flat fee per job, a percentage of the contract, or a fee per stage. Then re-ask the four price questions with the basis stated, and with a price shown, so the next panel answers a real price question.
2. **Test range:** two prices inside the range, roughly **200 and 300** in the chosen unit, which are the OPP and IPP points from the simulated answers. Do not take this as a price.
3. **The ladder (only if the basis supports it).** Options to test, not decided:
   - Good: the standard brief and bid comparison.
   - Better: plus verified builders and stage-by-stage payment release.
   - Best: plus project supervision and a guarantee.
   Each rung needs a reason to step up that answers an objection in section 5.
4. **Opening offer.** Hold off on an intro discount. The buyers' blocker is trust, not price, and a discount trains buyers to wait for it. If an opening offer is needed, make it a guarantee or a payment hold (money released only after sign-off), not a lower fee. Give it an end date.
5. **What to test with real buyers:**
   - First, add the trust elements the buyers asked for (builder checks, past work, stage-by-stage payment). A price test on a page without these measures distrust, not price. All 20 simulated buyers passed on trust.
   - Then two landing pages or pre-sales, one at each test price, with the same trust content, and compare sign-ups or deposits.
   - Count the sign-ups who reach the fee screen and leave there, not only who sign up.

## 5. Top price and trust objections (verbatim, from `panel/answers`)

1. P020: "Who checks that the builder is any good? If the platform does not vet them and stand behind the work, it is just a directory with a payment step." (trust)
2. P003: "Who is really making money here, and why would I pay you on top of the builder's price when I could find and vet a crew myself?" (trust, price)
3. P008: "I'd rather pay the crew directly and avoid the middleman. A platform that takes a cut on top of the builder's bid is one more cost I'd have to justify." (price)

Marketing should answer the first two with vetting and payment-hold facts, and state the fee and who pays it, before any price appears.

## Rules applied

- Simulated price answers pick what to test; they are not proof.
- No price is set below any variable cost, because no cost figures exist yet.
- No "was" price or anchor is used.

## Open items

- Pricing basis (flat, per stage, or percentage): not chosen.
- Currency: assumed RUB, not confirmed.
- CFO unit economics and break-even: not run.
- YouDo commission rate and ПАЗЛ customer-side price: not found.
- Legal check on whether escrow applies to flat renovation (see `competitors.md`).

Sources: `panel/answers/*.json` (20 files, 18 used), `pricing-curve.md`, `competitors.md`, `pitch.md`, `idea.md`, `panel/results.md`.
