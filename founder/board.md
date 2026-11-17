# Board verdict: HoReCa Hub (working name)

**Vote: 2 pass, 1 fund if · Average score: 3.0 / 10**

| Lens | Score | Vote |
|---|---|---|
| Offers | 3 | PASS |
| Monopoly | 3 | PASS |
| Product | 3 | FUND IF |

Memos: `board/offers.md`, `board/monopoly.md`, `board/product.md`.

## Risks every member raised

1. **Too many products at once.** All three counted 7 to 10 separate products (sourcing, HR, property, directory, booking, payments, reviews, profiles, loyalty, campaigns), serving at least four kinds of buyer. Each product has its own incumbents, so every one is a fight, every one comes out mediocre, and there is no single result for anyone to pay for.
2. **Cold start on every side.** The valuable part (diner profiles, repeat-visit data, loyalty) needs many diners, and diners need many restaurants. Suppliers need restaurants. A free MVP postpones this problem but doesn't solve it. There's no plan yet for how the first 100 restaurants or the first diners arrive.
3. **QR payment carries all the risk.** Verified reviews, profiles and loyalty only exist if diners actually pay through the product. Two risks sit on this one step: an app-install prompt at the end of the meal (Product), and the work of processing payments and getting licensed for it (Monopoly, Offers).
4. **Willingness to pay, and market size, are unknown.** Nobody knows yet whether independent Georgian restaurants feel this pain enough to pay 100 GEL or more a month, or how many there are in the starting city (still not named).

## Where they disagree

- **Product votes FUND IF; Offers and Monopoly vote PASS.** Product sees one clean, buildable loop and would back a pilot. The other two say that even the narrowed version still has to prove distribution, willingness to pay and defensibility before anyone funds it.
- **The moat.** Monopoly sees payment-linked, dish-level data as the one real moat, but one that only forms after scale. Offers treats it as proof that makes the outcome believable, not as a moat. Product treats it as the core of the product experience.
- **Free MVP.** Offers wants paid pre-commitments at a real price now. The other two focus on proving usage first (tables paid, guests returning).

## Conditions checklist (merged)

Focus
- [ ] Cut to ONE wedge: QR pay-at-table → verified dish-level review → repeat-guest recognition and loyalty for the restaurant. Park B2B sourcing, HR, property and campaigns, and keep the directory minimal. *(all three)*
- [ ] Name ONE starting city, and count its independent restaurants. *(all three → /founder-competitors)*

Product
- [ ] Payment works as a web checkout with no app install required; the app is optional. *(Product)*
- [ ] Script the diner's first five minutes, from sitting down to leaving. *(Product)*
- [ ] Map every handoff (POS, waiter, acquirer, receipt, split bill, tips, refunds, failures), with an owner and a failure path for each. *(Product → /founder-ops)*
- [ ] Show the restaurant gets value in week one from its own guests, before any network effects. *(Offers)*

Market and distribution
- [ ] Competitor map: who in Georgia already does booking, QR payment, loyalty and reviews, and why the wedge isn't already taken. *(Monopoly, Offers → /founder-competitors)*
- [ ] A named path to the first 100 restaurants, with a cost per restaurant. *(Monopoly → /founder-cfo)*
- [ ] Test whether diners will pay by QR and leave per-dish reviews, and what share would. *(Monopoly, Product → /founder-consumer)*
- [ ] Find what owners would pay for the one outcome (is 100 GEL realistic, and could the price be higher?). *(Offers → /founder-consumer, /founder-pricing)*

Money
- [ ] Payment processing cost per transaction, who pays it, and Georgian licensing needs: integrate with an existing provider, or become a payments company? *(all three → /founder-cfo, /founder-ops)*
- [ ] Cost to acquire a restaurant and a diner, and how long it takes to earn that back on the subscription. *(Offers, Monopoly → /founder-cfo)*
- [ ] Paid pre-commitments from a set of restaurants at a real price; the CFO's break-even sets how many. *(Offers)*
- [ ] A guarantee the business can afford, e.g. "X repeat visits in 90 days or the month is free". *(Offers → /founder-cfo, /founder-offer)*

Proof and team
- [ ] Pilot in a handful of restaurants in one city: tables paid through the product, and the share of guests who return. *(Product → /founder-launch)*
- [ ] A named team that can build payments-grade software, and an answer to "what stops a copycat in month six?" *(Monopoly)*

## The strongest version the board can see

This is **not** the ecosystem as pitched. It's a single product for independent restaurants in one Georgian city: the guest scans a QR code at the table and pays in the browser, with no app needed. That payment automatically creates a verified, dish-level review and a guest record, so the owner sees "Nino, third visit, always orders khinkali" and can switch on a ready-made loyalty reward with one tap. It's sold to owners on one promise: more repeat guests, measured. The payment-linked data is the one asset none of the members thinks a listing site can easily copy. Once that loop dominates one city, the diner directory grows out of the reviews it creates, and the B2B modules (suppliers, hiring, property) become upsells to restaurants that already trust the platform. Those modules come later; they aren't the starting point.

## Chair's note after the founder's clarification (not re-scored)

The founder clarified that the B2B side is a **listings marketplace**: it connects restaurants with suppliers, job seekers and property owners or brokers, and doesn't run the deals itself.

**What this changes**
- Building and running it gets much lighter. Listings plus contact is a far smaller build than procurement, recruitment or brokerage software, so the "ten products" critique is partly answered for the B2B side.
- It could solve the week-one value problem the Offers lens raised. A restaurant gets something useful (staff, suppliers, premises) before any diner has the app. That makes B2B listings a possible free hook to sign up restaurants, not just a later upsell.

**What it doesn't change**
- Every listing board is still its own two-sided market. It needs supply (suppliers, job seekers, property listings) and demand (restaurants), and each side has its own cold start.
- Listings are easy to copy, and both sides can switch away cheaply, because people post in several places at once. Listings alone don't build a moat. The payment-linked guest data is still the only moat the board identified.
- Subscription revenue from listings depends on getting results, such as hires made or supplier deals closed. Willingness to pay is still unknown (→ /founder-consumer, /founder-pricing).

**New condition**
- [x] **Decided: (a), B2B listings are a free hook for restaurants.** Choose a role for the B2B listings: either (a) a free hook to bring restaurants onto the QR/loyalty product, or (b) a separate paid product. If (b), name the one listing category to launch first and how its supply side gets filled. *(→ /founder-competitors: who already lists HoReCa jobs, suppliers and properties in Georgia)*
