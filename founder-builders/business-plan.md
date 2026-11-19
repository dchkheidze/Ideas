# Builder marketplace (working name: not chosen) · Business plan

**Verdict: Incomplete.** The compiler's checks below fail on the placeholder inputs (Not yet), but `numbers.json` is marked as placeholders and says not to read its output as a result, so the result is not clear. Missing inputs: fee level and payer, real average contract value, escrow or introduction-only branch, cost per brief and brief-to-contract rate from a pilot, cost per verified builder, sourced market size and signed jobs per month, fixed costs and startup quotes, guarantee cost.

- ✗ Each signed job (one renovation contract) LOSES $9500.00 before fixed costs.
- ✗ Year 1 operating LOSS: $5,939,886.
- ✗ 0 of 20 simulated buyers buy (0%, the bar is 25%).

| key number | |
| --- | ---: |
| Price | $10500.00 a signed job (one renovation contract) |
| Profit margin at plan | -471% per signed job (one renovation contract) |
| Break-even | never signed job (one renovation contract)s a day |
| Year 1 operating profit | $-5,939,886 |
| Startup spend | $450,000 |
| Cash needed before it pays for itself | $6,389,886 |
| Startup money earned back | not in year 1 |
| Buyer panel | 0 buy · 20 pass |

## The idea

- What it is: an online platform that connects private customers who want a house built or an apartment renovated with home-builder and renovation companies, and mediates the deal: the customer describes the job, builders bid, the platform helps select and contract, and payment is handled through the platform. Reference models named by the founder: pzzl.ru and stroim.dom.rf (Russian-language platforms in the same space).
- Scope: not only new houses. Flat (apartment) renovation works are in scope from the start.
- Who it is for: private customers commissioning construction or renovation work (homeowners and apartment owners). Builders and renovation companies are the supply side. Market and city are not yet specified.
- What it sells, at what price: not decided. The likely model is a commission or fee on the contracted value, paid by the builder or the customer. Not yet priced; no revenue assumption has been set.
- Where and how: country, city and language are not yet specified (the founder's references are Russian-language, so Russia or CIS is possible but unconfirmed). Delivered as a web platform and mobile app. Customer acquisition channels are not yet specified.
- Budget and constraints: not specified (budget, team, skills, timeline, existing industry relationships all open).

### Open items the board should treat as unknown
- Name, city/country, commission model and level, how customers and builders are acquired, and whether the platform holds money in escrow or only introduces the parties.

## What the board said

**Vote: 3 fund if · Average score: 3.7 / 10**

| Lens | Score | Vote |
|---|---|---|
| Offers | 4 | FUND IF |
| Monopoly | 3 | FUND IF |
| Product | 4 | FUND IF |

Memos: `board/offers.md`, `board/monopoly.md`, `board/product.md`.

### Risks more than one member raised

1. **Too many products at once.** New builds and flat renovation have different buyers, ticket sizes and timelines. Offers and Product both say launching both spreads builder supply and acquisition spend too thin. Monopoly says no small market is chosen yet.
2. **The money seam is undecided.** Escrow (the platform holds payment) or introduction only (the platform hands off the parties). Product and Offers both flag it as the place the experience breaks. Escrow means milestones, disputes and refunds, a much larger build. Introduction-only lets the customer and builder sign off-platform and skip the commission.
3. **No proof of outcome and no distribution plan.** Builders are not yet verified, past work is not shown, and acquisition channels and cost per customer are unknown. A house or renovation is a large, infrequent purchase, so the cost of the first 100 customers may exceed one commission (Monopoly).
4. **Bids are not comparable.** Each builder scopes a job differently, so bids are just prices and the customer falls back to price or referral (Product).
5. **Closest references are unverified.** The board did not check pzzl.ru or stroim.dom.rf. Their size, reach and offer are open, and the wedge against them is not stated.

### Where they disagree

- **Strength of the case.** Offers sees a real, costly pain that an offer can sell into. Monopoly sees demand for this kind of platform but no moat yet; a trust layer only forms after density in one local market.
- **Renovation first?** Product and Monopoly both suggest flat renovation may be the smaller, faster first market to learn from. Offers wants one segment proven before any second one.

### Conditions checklist (merged)

Focus
- [ ] Name ONE city and ONE job type for launch (renovation is the candidate) with a sourced market size. *(all three)*
- [ ] Write a one-sentence promise: the one job the first customer finishes on the platform. *(Product, Offers)*

Money
- [ ] Decide escrow or introduction-only before any design; draw the money flow on one page. *(all three)*
- [ ] Write the guarantee in one sentence and confirm with the CFO it is affordable. *(Offers)*

Value and journey
- [ ] Set target numbers: time from request to signed contract, and effort for the customer, both better than today. *(Offers)*
- [ ] Map the full journey (bid, contract, payment, change orders, completion, disputes) with an owner for each handoff. *(Product)*
- [ ] Create a standard job brief and bid template so bids compare on the same scope. *(Product)*

Supply and demand
- [ ] Verify builders before listing them; show past work to customers. *(Offers)*
- [ ] Sign a set number of builders in the chosen city before promising bids. *(Monopoly, Offers)*
- [ ] Confirm the commission level with builders in a test before locking it in. *(Offers)*

Distribution and differentiation
- [ ] Write a distribution plan with cost per customer for the CFO to test. *(Monopoly)*
- [ ] Check pzzl.ru and stroim.dom.rf directly and state the wedge against them. *(Monopoly, Offers)*

Validation
- [ ] Test the flow by hand on a few real jobs (form, spreadsheet, phone calls) before building the app. *(Product)*

### The strongest version the board can see

A flat-renovation marketplace in one city, starting with a standard job brief and a verified shortlist of renovation firms. The platform owns the bid-to-contract step, and the money flow is decided up front. It proves the customer saves time and avoids a bad bid, then expands to new builds. The pitch as written (both new houses and renovation, from day one, with a builder marketplace on top) is the version the board would not fund.

### Notes

- One of the sub-agents made a stray attempt to create a Claude Code Remote session that was not needed for this task. It was denied, and nothing was created.
- This pack is kept separate from `founder/`, which holds the earlier HoReCa Hub pack, so neither overwrites the other.

## The competition

Run date: 2026-11-19. Sources: public pages, search excerpts and public reviews, each linked below. Market not yet fixed: Russian-speaking markets first, then the UK as a reference. Rows are in `competitors.csv` in this folder.

### Two corrections to the brief

1. **Both founder references are new-house platforms, not renovation.** pzzl.ru (ПАЗЛ ДОМ) sells estimates, builder checks and project finance for a private house (ИЖС). stroim.dom.rf (ДОМ.РФ) is a state catalogue of house projects and verified contractors with escrow. Neither page read advertises apartment renovation. The board's "renovation first" idea is therefore not covered by either reference.
2. **Escrow for ИЖС is a legal framework, not a product choice.** The bank reply quoted in the July 2026 review cites Federal Law 186-FZ of 22.07.2024 on construction contracts with escrow accounts ([banki.ru review and bank reply](https://www.banki.ru/services/responses/bank/response/13255988/)). The sources read tie the escrow rule to private-house contracts. I did not find an equivalent for flat renovation. This needs a legal check before the money-flow decision.

### 1. The table (sorted by how directly each competes)

| # | Name | Type | What it sells | Price to customer / to pros | Link |
|---|---|---|---|---|---|
| 1 | RERATE matching (Moscow) | Direct, renovation | Free quote and match to rated renovation firms | Customer free; firms pay nothing shown | [rerate.ru/calculator](https://rerate.ru/calculator/) |
| 2 | Profi.ru | Direct, renovation | Lead board for masters and brigades; exam-certified masters | Customer free; masters pay fees (see complaints) | [profi.ru/remont](https://profi.ru/remont/) |
| 3 | YouDo | Direct, renovation | Task board; 'Сделка без риска' holds the card payment until confirmed | Customer pays commission on the safe deal (rate not found); performers pay for paid responses | [youdo.com brigades](https://youdo.com/bytovoj-remont/repair/flat/overhaul/brigadi), [youdo.com/sbr](https://youdo.com/sbr), [help](https://help.youdo.com/articles/chto-takoe-platnye-otkliki-k-zadaniyam/) |
| 4 | ПАЗЛ ДОМ | Direct, new houses | AI estimate, builder check, project finance, digital control | Contractor: 20,000 RUB per object, 1% of each finance tranche, 3-5% per partner lead; customer price not found | [pzzl.ru](https://pzzl.ru/), [contractor terms](https://lp.pzzl.ru/contractors) |
| 5 | ДОМ.РФ stroim.dom.rf | Direct, new houses | Verified catalogue, escrow contracts, mortgage | No fee found (not verified) | [stroim.dom.rf](https://stroim.dom.rf/) |
| 6 | Ремонт-квартиры.ру | Direct, renovation | Free request; masters send offers | Not found | [remont-kvartiri.ru](https://www.remont-kvartiri.ru/) (listed in [Praktika 2020](https://praktika.plus/blog/sovety-pokupatelyam/obzor-onlayn-servisov-poiska-stroiteley/)) |
| 7 | Ремонтник.ру | Direct, renovation | Request and offers, or direct contact | Not found | [remontnik.ru](https://www.remontnik.ru/) (listed in [Praktika 2020](https://praktika.plus/blog/sovety-pokupatelyam/obzor-onlayn-servisov-poiska-stroiteley/)) |
| 8 | Мастер Дел | Direct, Moscow | Order built in chat (scope, photos, time); reviews | Not found | [masterdel.ru](https://masterdel.ru/) (listed in [Praktika 2020](https://praktika.plus/blog/sovety-pokupatelyam/obzor-onlayn-servisov-poiska-stroiteley/)) |
| 9 | ForumHouse биржа | Direct, bid board | Build orders; also sells materials | Not found | [forumhouse.ru](https://www.forumhouse.ru/) |
| 10 | Биржа Петровича | Indirect, directory | 18,956 masters and firms with ratings | Not found | [pro.petrovich.ru](https://pro.petrovich.ru/) |
| 11 | СтроителиРФ | Indirect, exchange | 5,600 private brigades, 1,900 firms; SRO licence shown | Not found | [stroitelirf.ru](https://stroitelirf.ru/) |
| 12 | Smartremont.kz | Indirect, Kazakhstan | Fixed-price flat renovation firm (not a marketplace) | Fixed price per m2 (number not captured) | [smartremont.kz](https://smartremont.kz/) |
| 13 | MyBuilder (UK) | Reference, outside Russia | Free job posting; quotes from tradespeople | Customer free; tradespeople pay per lead | [mybuilder.com](https://www.mybuilder.com/) |
| S | Referral from friends | Substitute | Word of mouth | Free to customer; cost is a bad crew | [RBC excerpt](https://realty.rbc.ru/news/68a8330d9a79475de9f4d47b) |

Rows 6 to 9 and 10 to 11 come from a 2020 review article, not from live checks; treat them as unverified today.

### 2. Price range

- **Platform fee to the customer:** free on every page that states it (RERATE, Profi via RERATE, YouDo's safe deal excepted). No median can be computed; the only numbers are free and one undisclosed commission.
- **Platform fee to the pro:** the only explicit schedule is ПАЗЛ's: 20,000 RUB per object, 1% of each tranche, 3-5% per partner lead ([source](https://lp.pzzl.ru/contractors)). It is a single data point, lowest = highest.
- **Job price (the comparable item):** Profi search-result 'from' prices for Moscow: 7,000 RUB per m2 for renovation and finishing; 14,000 RUB per m2 for design renovation ([Profi Moscow](https://profi.ru/remont/remont-kvartiry-s-materialami/)). Profi Pskov lists capital renovation at 4,150 to 13,900 RUB per m2 and cosmetic at 1,620 to 6,920 RUB per m2 ([Profi Pskov](https://profi.ru/geo-pskov/registration/remont/remont-kvartir/)). These are list prices from search excerpts, not checked against completed jobs. RERATE's sample estimate of about 135,300 RUB for three tiers is identical across tiers, so I treat it as a placeholder.

### 3. Positioning map (text)

Axis X, scope: new private house (left) to apartment renovation (right).
Axis Y, trust and money: open board with no vetting (bottom) to verified contractors with money held (top).

- Top-left: ДОМ.РФ and ПАЗЛ ДОМ. Verified, bank-linked, for houses.
- Top-middle: YouDo 'Сделка без риска'. Money held, but only for its own task board.
- Middle-right: RERATE. Rated firms and free matching; no money held.
- Bottom-right: Profi, Ремонтник, Ремонт-квартиры.ру, Мастер Дел, ForumHouse. Bids or leads for renovation, little verification shown.
- **Empty: top-right.** Apartment renovation with verified contractors and money held. No page read sells this.

### 4. Complaints, ranked (all themes thin: under three reviews each)

1. **Commissions on pros.** Profi, 2021: "берут комиссию в размере полного занятия" ([RERATE review 93176](https://rerate.ru/review/93176/)). Profi, 2025: "Огромные комиссии" ([RERATE review 126125](https://rerate.ru/review/126125/)). Two reviews, thin.
2. **Support does not resolve disputes.** Profi, 2022: "Три недели потратил на переписку со службой поддержки" ([RERATE review 108035](https://rerate.ru/review/108035/)). Profi, 2023: a master kept pressing to be chosen, and support did not respond ([RERATE review 108813](https://rerate.ru/review/108813/)). Two reviews, thin.
3. **Escrow does not stop a bad contractor.** ИЖС escrow, July 2026: the contractor used fake stage acts to draw escrow money; the bank will not approve a change of contractor without a price agreement or a court decision that sets the sum ([banki.ru review 13255988](https://www.banki.ru/services/responses/bank/response/13255988/)). One review, thin, but high-stakes. A comment on the stroim.dom.rf instructions page describes the same risk ([instructions](https://xn--h1alcedd.xn--d1aqf.xn--p1ai/instructions/stroitelstvo-chastnogo-doma-s-ispolzovanie-ekrou-scheta/)), undated.
4. **Bid quality is hard to compare.** Each firm scopes a job differently. Stated in [Praktika 2020](https://praktika.plus/blog/sovety-pokupatelyam/obzor-onlayn-servisov-poiska-stroiteley/) and in the board memo. One source, thin.
5. **UK: pay per lead, no guaranteed work.** Reddit: "You pay a lot and aren't guaranteed to get the work!" ([r/DIYUK](https://www.reddit.com/r/DIYUK/comments/1bt2yp5/does_anyone_use_mybuilder_to_find_tradesmen/)). One comment, thin.

### 5. The gap

Apartment renovation in the sources read has three kinds of option, and none combines them:
- **Free bid boards** (Ремонтник, Ремонт-квартиры.ру, Мастер Дел, ForumHouse): offers with no common scope and, per the 2020 review, no published past work.
- **Lead marketplaces** (Profi, YouDo): pros pay, reviewers say the fees are high, and support is weak.
- **Rated firms with free matching** (RERATE): good trust signal, but no held money and no common brief.
- **Escrow and verification** (ДОМ.РФ, ПАЗЛ): real, but built for new private houses. The escrow framework cited is ИЖС-specific.

The gap the sources point to: a renovation-first marketplace that uses one standard job brief, makes bids comparable, verifies firms, and holds money by milestone where the law allows. The July 2026 escrow complaint shows that holding money is not enough without evidence of work and a clear way to change contractor. That is a design requirement, not a reason to skip the gap.

Confidence: moderate. About 20 pages and reviews were read; the directory is not exhaustive and several items are from 2020.

### 6. The threat

- **ДОМ.РФ and ПАЗЛ** already have verified contractors, bank partners (ПАЗЛ names T-Bank, VTB, Gazprombank and Ingosstrakh; self-reported) and escrow flow. Extending to renovation is the fastest copy path, if the escrow rule allows.
- **RERATE** already gives free matching with ratings in Moscow and claims 10,000 reviews. It can add a brief and a payment hold.
- **Profi and YouDo** have traffic (Profi claims 1.5 million specialists and 15,000 new orders a day; self-reported). Copying the bid step is easy; copying held payment needs a bank or payment partner.

### Unverified

- ПАЗЛ's customer-side price and whether its 'builder search' is free.
- Whether stroim.dom.rf charges anyone; no fee found, not confirmed.
- YouDo's commission rate on 'Сделка без риска'.
- Profi's current master fee; only 2021 and 2025 reviews read.
- Current status of the 2020 directories (Ремонт-квартиры.ру, Ремонтник, Мастер Дел, ForumHouse, Petrovich, СтроителиРФ, Houzz).
- Meaning of stroim.dom.rf's unlabelled homepage counters (6,413 and 7.5 were not explained).
- Market size: no sourced figure found in this run. The board's condition on market size is still open.
- Kazakhstan and Uzbekistan: no matching platform found. smartremont.kz is a firm, and one Uzbek article gives advice only. Ukraine not searched.
- Yandex services: named once in a 2021 review as free; not checked.
- Profi.ru's own headline was not captured (page too large to read in full), so the positioning line is blank.

## The buyer panel

**0 buy · 20 pass** (0% buy) out of 20 simulated buyers. Seed 975635, so the same cards can be dealt again.

These are simulated buyers, not customers. Use this to find objections and weak spots, then confirm the big ones with real people before you spend.

### By segment

| group | buyers | buy rate |
| --- | ---: | ---: |
| Owner-occupier, higher income | 7 | 0%  (thin) |
| Owner-occupier, budget-aware | 9 | 0% |
| Landlord renovating a rental flat | 4 | 0%  (thin) |

### By buying behaviour

| group | buyers | buy rate |
| --- | ---: | ---: |
| Already has a crew | 2 | 0%  (thin) |
| Referral-led | 3 | 0%  (thin) |
| Reads reviews, slow to trust | 3 | 0%  (thin) |
| Hands-off | 2 | 0%  (thin) |
| Gets three quotes before choosing | 4 | 0%  (thin) |
| Price-first | 3 | 0%  (thin) |
| Burned before | 3 | 0%  (thin) |

### By income

| group | buyers | buy rate |
| --- | ---: | ---: |
| $2,938,000 and up | 7 | 0%  (thin) |
| $2,011,000 to $2,938,000 | 7 | 0%  (thin) |
| under $2,011,000 | 6 | 0%  (thin) |

### Why they pass

| reason | buyers | in their words |
| --- | ---: | --- |
| trust | 16 | "I already have a crew I trust, or at least someone in mind, so I only need the paperwork and payment done. Paying a platform to do that is not worth it unless it also tells me the builder is good, and this offer does not say that." (P001) · "I have only ever hired builders through people I know, and I would still ask my friends for a crew before I pay a platform to pick one for me. A standard brief sounds useful, but I do not know who runs this or what happens to my money if the work goes wrong." (P002) |
| price | 3 | "The idea fits what I need, because I don't want to spend my evenings chasing a crew. But I can't tell whether the platform's fee is worth paying on top of the builder's price when no fee is stated." (P006) · "I'd rather pay the crew directly and avoid the middleman. A platform that takes a cut on top of the builder's bid is one more cost I'd have to justify, and I'm not convinced the contract and payment handling are worth it." (P008) |
| habit | 1 | "I have only ever hired builders through word of mouth, and I get three quotes before choosing. A platform fee on top of the builder's price has to give me something I cannot get myself, and nothing I have read so far shows that it does." (P017) |

### Why they buy

| reason | buyers | in their words |
| --- | ---: | --- |

### What would flip a no

- Proof that the platform vets builders properly, with checked references and past finished jobs I can look at, plus payment held back until each stage of work is signed off.
- A builder I already trust, or a friend who has used it, recommends the platform and shows me a finished flat it handled, with the payment held until I sign off the work.
- Verified builders with independent, checkable reviews from past private clients in my city, a fixed fee I can see before I sign, and a payment arrangement where my money is released only as the agreed work is signed off.
- A friend or neighbour who has used it for a flat renovation and vouches for it, plus a clear breakdown showing the platform fee is small and the builder's price is not inflated.
- A published, flat fee that is clearly small next to the job, plus proof the payment holds back money until each stage is signed off.
- A clear, fixed fee stated up front, and confirmation that the service runs in my city.
- Verified past work and reviews for each builder, plus payment held in escrow and released only when each stage of the job is signed off.
- Seeing real builder bids on the same brief that come in at or below what I'd pay going direct, with a fixed, clearly stated fee and proof the payment is held until the work is signed off.
- A stated price up front, plus proof that the builders are vetted and that the escrow payment protects me if the work goes wrong.
- A standard written scope that every bid must price line by line, plus payment held by the platform and released only stage by stage after I sign off each stage, with builders I can check against past clients.
- A stated fee that is clearly smaller than what the platform saves me on the bids, shown with a sample of real builder quotes for a flat like mine.
- Verified references from people I know, plus a payment hold that releases only when the work is signed off and a clear, fixed fee I can see before I commit.

20 buyers gave all four price answers. Run founder-pricing's van_westendorp.py on the answers folder.

## Pricing

Price is **not decided**. This note recommends a range to test and what to test. It does not set a price, and it has no margin or market figures because the CFO step has not run (there is no `numbers.json` in this folder).

### Read this first: what the price answers are

- **The buyers were not shown any price.** The pitch says "Price: not decided yet" (`pitch.md`). Every price answer is the buyer's own guess at what they would expect to pay, not a reaction to an offered price. Treat the range below as **low confidence**. It shows where simulated buyers' expectations sit, not where they would accept an offer.
- **The unit is not defined.** The panel question asks for "the price" with no unit and no basis: a flat platform fee, a fee per job, a monthly fee, or a percentage commission are all possible. The board's working model is a commission on the contracted value (`idea.md`), which is a percentage. A flat-currency answer does not map onto a percentage. Fix the basis before any test.
- **Currency is assumed to be RUB.** The competitor and market sources are Russian, but the answers carry no currency field. The script labels its output "$" because that label is hard-coded; read those numbers as unlabelled units, not dollars.
- **Every simulated buyer passed (0 of 20 buy).** 16 of 20 gave trust as the reason, 3 price, 1 habit. The price answers come from people who distrust the offer, so they may measure how much a buyer would pay to be vetted at all, not the fee itself.
- **Two answers were dropped** (P014 and P017 gave a 0 for "too cheap", which the script treats as incomplete). 18 answers were used.

### 1. Van Westendorp range (from `pricing-curve.md`)

| point | value | meaning |
| --- | ---: | --- |
| PMC | 102 | below this, too many think it is too cheap to be good |
| OPP | 205 | least resistance: as many say too cheap as too expensive |
| IPP | 298 | as many call it a bargain as call it expensive |
| PME | 604 | above this, too many say it is too expensive to buy |

Acceptable range: **about 102 to 604** (unit unconfirmed). Median answers: too cheap 50, a bargain 150, getting expensive 500, too expensive 1,000.

The range is wide (about six-fold). Low confidence for the reasons above.

### 2. What competitors charge (`competitors.md`)

Like-for-like comparison is difficult, because the sources do not give the same kind of price:

- **Platform fee to the contractor:** ПАЗЛ ДОМ publishes 20,000 RUB per object, 1% of each finance tranche, and 3 to 5% per partner lead. This is for new private houses, not flat renovation. It is the only explicit fee schedule found.
- **Customer-side fee:** free on every page that states it (RERATE, Profi). YouDo's safe-deal commission rate was not found.
- **Job prices (not platform fees):** Profi search-result "from" prices for Moscow renovation run about 7,000 RUB per m² for finishing. These are list prices, not completed jobs.

The buyers' range sits far below any platform fee in the sources. That may be because buyers guessed a flat fee, not a percentage. Compare against the commission model once it is chosen.

### 3. What the business needs

Not computed. There is no `numbers.json` and no CFO run, so no unit margin or break-even is given here. Run `/founder-cfo` on the chosen basis before choosing a test price.

### 4. Recommendation

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

### 5. Top price and trust objections (verbatim, from `panel/answers`)

1. P020: "Who checks that the builder is any good? If the platform does not vet them and stand behind the work, it is just a directory with a payment step." (trust)
2. P003: "Who is really making money here, and why would I pay you on top of the builder's price when I could find and vet a crew myself?" (trust, price)
3. P008: "I'd rather pay the crew directly and avoid the middleman. A platform that takes a cut on top of the builder's bid is one more cost I'd have to justify." (price)

Marketing should answer the first two with vetting and payment-hold facts, and state the fee and who pays it, before any price appears.

### Rules applied

- Simulated price answers pick what to test; they are not proof.
- No price is set below any variable cost, because no cost figures exist yet.
- No "was" price or anchor is used.

### Open items

- Pricing basis (flat, per stage, or percentage): not chosen.
- Currency: assumed RUB, not confirmed.
- CFO unit economics and break-even: not run.
- YouDo commission rate and ПАЗЛ customer-side price: not found.
- Legal check on whether escrow applies to flat renovation (see `competitors.md`).

Sources: `panel/answers/*.json` (20 files, 18 used), `pricing-curve.md`, `competitors.md`, `pitch.md`, `idea.md`, `panel/results.md`.

## The offer

Built from: `idea.md`, `board.md`, `board/offers.md`, `competitors.md`, `pitch.md` (now kept as `pitch-v1.md`), `panel/results.md` and `panel/results.json` (20 simulated buyers, seed 975635, 0 buy, 20 pass). No `numbers.json` exists yet, so every cost below is a qualitative estimate, not a CFO figure. No market size, fee, price or guarantee cost is assumed here.

### The offer in one sentence

Renovate your flat on one written scope: verified builders bid on the same brief, the contract is set up for you, and you pay only for stages you have signed off.

### 1. Who has the pain (basis)

Panel passes: trust 16 of 20, price 3, habit 1. Every objection is one of three: "who checks the builder", "why pay a platform on top", "bids do not compare". The offer has to answer those three before anything else. Segments: budget-aware owners (9), higher-income owners (7), landlords (4). Per the panel, the "already has a crew" and "burned before" buyers are the hardest to move.

### 2. The problem list (23 obstacles, in buyer words)

Value is 1 to 5 for the buyer. Cost is a provisional 1 to 5 estimate for us to deliver, to be replaced by the CFO's figure.

Before buying
1. "Who checks that the builder is any good?" (value 5, cost 4)
2. "Why pay a platform on top of what the builder charges?" (value 5, cost 1)
3. "I don't know whether the fee is worth it, since no fee is stated." (value 4, cost 1)
4. "I would rather pay the crew directly." (value 4, cost 2)
5. "Bids never describe the same work, so I can't compare them." (value 5, cost 2)
6. "I get three quotes before choosing." (value 3, cost 1)
7. "I only trust people who come through friends." (value 4, cost 3)
8. "I read reviews and I am slow to trust anything that looks like an ad." (value 3, cost 2)
9. "I'm busy and can't spend evenings chasing a crew." (value 4, cost 3)
10. "I already have a crew; I only need paperwork and payment." (value 3, cost 2)
11. "I buy on price." (value 2, cost n/a: not solved, see section 6)

During the job
12. "The builder stops or drops out halfway." (value 5, cost 4)
13. "I paid up front and lose the money if the work goes wrong." (value 5, cost 3, depends on legal check)
14. "Who decides whether a stage is really finished?" (value 4, cost 3)
15. "Changes add cost and nobody agreed them." (value 4, cost 2)
16. "A friend's job ran over budget and dragged on for months." (value 4, cost 3)
17. "Support does not resolve the dispute." (value 4, cost 3)

After the job
18. "Defects show up after handover, and who fixes them?" (value 3, cost 3)
19. "The builder asks for more after I have signed." (value 4, cost 2)
20. "I can't tell if the final price was fair." (value 3, cost 2)

Also noted from the competitor complaints and the board: 21. "The fee is a cut on top of the bid" (same as 2, handled by a published fee); 22. "No common brief means no common scope" (same as 5); 23. "Start date and programme are vague" (value 3, cost 2).

### 3. Solutions, trimmed and stacked

Kept (high value, low or acceptable cost): problems 2, 3, 5, 6, 14, 15, 19, 1 (limited), 9, 12, 13 (conditional), 17, 20.
Dropped or deferred: problem 11 (price-first; the offer does not compete on price); problem 10 (already has a crew; a separate, lower-priced paperwork-only product, to test later); problem 8 only through real reviews, never invented ones.

**The core**
Flat renovation, one fixed brief. You describe the flat once in a standard brief (floors, kitchen, bathroom, and the rest of the scope). Shortlisted, checked builders price that same brief line by line. The platform sets up the contract on the agreed scope and the agreed fee. Work is paid in stages, each released only after you sign it off.

**Bonuses (each kills one named objection)**
- **Bid comparison sheet** (kills 5 and 6): all bids side by side, line by line, on the same brief, so "three quotes" becomes one comparable table. Cost: low, mostly template work.
- **Pre-signing check pack** (kills 1 and 7): a reference call script for each builder, plus a checklist for visiting a finished job, so the buyer can check before signing. Cost depends on how many past clients the builders can give us. Only real clients, never invented ones.
- **Stage sign-off and change log** (kills 14, 15 and 16): one form per stage, with photos, and a change-order form priced against the same brief and signed before work starts. Cost: low to medium.

**The guarantee (decision for the founder with the CFO)**
Draft wording, with the terms left open: "If the verified builder stops before a signed stage is finished, we [option A: replace the builder from the shortlist at no extra platform fee / option B: refund the platform fee for that job], and you pay only for stages you have signed off."
- Not promised yet. The claim rate, the replacement cost and the refund amount are unknown. The CFO must model them at a realistic claim rate before any wording goes public.
- Consumer-protection and advertising rules for guarantees apply in the launch market. Not legal advice.

**Urgency and scarcity (only if true)**
Allowed: "first cohort of builders is capped at the number we have verified before launch", if that cap is real. Not allowed: any countdown or "only N left" that is not true.

**The name**
Working name: "Flat Renovation, One Brief". The company name is still open and is not decided here.

### 4. The money line: a decision, not a detail

The offer's claim "you pay only for stages you have signed off" depends on the escrow decision. The sources read tie escrow to Federal Law 186-FZ (22.07.2024), which covers construction contracts for private houses (ИЖС). No equivalent rule for flat renovation was found (`competitors.md`, section 2). Until a lawyer confirms the route for flat renovation, this claim stays a decision, not a promise. The July 2026 escrow complaint also shows holding money is not enough without evidence of work and a clear way to change builder.

### 5. Value equation (1 to 10; 10 is best for the buyer, so time and effort are scored high when small)

| Element | Before (word of mouth, three quotes) | After, if the stack is built and proved | Today's pitch (no proof yet) |
|---|---|---|---|
| Dream outcome: finished flat, fair price, on a contract | 5 | 7 | 7 |
| Perceived likelihood of getting it | 3 | 6 (only once verified builders and past jobs exist) | 3 (wording does not add proof) |
| Time to result (request to signed contract) | 4 (no target) | 5 (target to be set, see below) | 4 |
| Effort and sacrifice on the buyer | 3 (buyer chases crews) | 7 (one brief, one comparison, stage sign-off) | 5 |

What moves which score:
- Likelihood: pre-signing check pack and verified shortlist. Without them the score stays at 3, whatever the wording says. This is why the panel's 0 of 20 is a trust result, not a copy result.
- Effort: standard brief and bid comparison sheet.
- Outcome: stage release and the guarantee, which lower the downside.
- Time: unchanged until targets are set.

Targets still to be set with the founder: the time from request to signed contract, and the number of hours the customer spends.

### 6. What the offer does not solve

- The "platform fee on top of the bid" objection is answered only by a published fee. The fee level, and who pays it, is a decision. The panel's price answers exist (`panel/answers`), but their unit is not stated in the results, so they are not used here to set any price. `founder-pricing` should set it after the unit is confirmed.
- The "bypass the platform" risk stays. The offer reduces it by making the contract and staged payment run through the platform, but a buyer can still sign off-platform.
- Price-first buyers are not the target.

### 7. Re-test (not run yet)

The skill's re-test step (`founder-consumer --quick`, same seed 975635) is not run in this pass. Reasons:
- Three decisions are still open (fee, escrow route, guarantee), so the new pitch in `pitch.md` still has placeholders. Testing it now would test a draft.
- The baseline to beat is 0 of 20 buys with `pitch-v1.md` (seed 975635).

Run it once the decisions are made. A rise from 0 is expected only if the proof items exist to show. If the buy rate stays flat, the problem is likely trust or market, not the wording.

### 8. Decisions for the founder (with the CFO to test)

1. Fee level and who pays it (builder, customer, or both). CFO: model at the panel's price range once the unit is confirmed.
2. Escrow or stage release. Legal check on flat renovation first (186-FZ covers private houses).
3. Guarantee: option A or B, its cap, and its cost at a realistic claim rate.
4. Launch city and the number of verified builders needed before the first bid.
5. Cost per verified builder and per customer (the CFO's ceiling; the board asked for it).
6. Time and effort targets for the value equation.
7. Defect period and response time for disputes (both invented today).

### Checks

- No fake reviews, testimonials, scarcity, discounts or "as seen on". Verified-builder and past-job claims wait until real checks exist.
- No market size, fee, price, guarantee cost or conversion number is stated here. Each is a decision.
- Next: `/founder-cfo` with the stack (needs the cost per builder, per customer and per claim), then `/founder-marketing`. Re-test after the decisions above.

## The numbers

**Status: nothing here is a result.** No price, commission, volume, cost or market size is decided or sourced. Every input in `numbers.json` is a labelled placeholder or ASSUMPTION. The script output below the grid uses the base-case placeholders only. Currency is not decided; the script's "$" is a hard-coded label, so read all values as unlabelled units.

### Break-even, as formulas

Per signed job (one renovation contract):

- Fee F = take rate t x contract value V (percentage basis), or a flat fee (flat basis).
- Contribution C = F - d - c_b / r
  - d = payment cost per job (0 if introduction only; branch B adds the payment partner's fee)
  - c_b = cost per brief submitted; r = brief-to-signed-contract rate
- Break-even signed jobs a month: J* = (fixed_monthly + n_v x c_v) / C, where n_v = verified builders a month and c_v = cost per verified builder. J* exists only if C > 0.
- Acquisition is affordable only if c_b < (F - d) x r. This is the marketing max cost per brief (`marketing.md`, Step 5).

### Which scenarios are viable

- Unit level: 15 of 45 grid cells have C > 0. They need a fee that clears the cost per brief at the brief-to-contract rate. A flat 25,000 fee or a 5% take with cost per brief 300 are the cases that clear.
- Monthly level: not proven viable. At the base placeholders (3% take, cost per brief 1,000, r 5%) C is negative and there is no break-even. Example positive cases at fixed costs of 400,000 a month: flat 25,000, cost per brief 300, r 10% gives C = 22,000 and J* about 18 jobs a month. Take 3%, cost per brief 300, r 10% gives C = 7,500 and J* about 53. Whether 18 or 53 signed jobs a month is possible in one city is unknown, because no market size is sourced.

### Inputs the founder must supply

1. Fee basis and level, and who pays it (builder, customer or both). Fee and contract value are the largest drivers.
2. Average contract value V. The 350,000 placeholder is 50 m2 x 7,000 per m2 (Profi "from" list price in `pricing.md`), not a completed-job figure.
3. Branch: introduction only (d = 0) or platform holds money (d set by the payment partner).
4. Cost per brief submitted and brief-to-signed-contract rate. Both come from a pilot test, not from the panel (0 of 20 bought).
5. Cost per verified builder c_v and builders verified a month n_v (`ops.md` SOP-1).
6. Fixed monthly operating cost: staff, tools, legal retainer (`ops.md` sections 3 and 5).
7. Startup spend: legal setup, contract templates, initial builder bench, launch test budget.
8. Signed jobs a month at plan and the year 1 ramp. No market size is sourced.
9. Guarantee cost and claim rate (`offer.md` section 3). Not modelled: the guarantee is undecided and its wording depends on the CFO's figure.

### The line to watch

The brief-to-contract rate. The break-even is most sensitive to r because acquisition cost is c_b / r. At 2% instead of 10%, a cost per brief of 1,000 adds 50,000 per signed job.

### Board conditions (`board.md`)

- "Write a distribution plan with cost per customer for the CFO to test": not met; no cost per brief exists.
- "Cost per verified builder and per customer (the CFO's ceiling)": not met; placeholders only.
- "Confirm the commission level with builders in a test": not met.

### Grid: contribution per signed job

Rows are fee options, columns are brief-to-contract rates r. Values are C = F - cost_per_brief / r, in unlabelled units.

| fee basis | fee per job | cost per brief | contr r=2% | contr r=5% | contr r=10% |
|---|---:|---:|---:|---:|---:|
| take 1% of contract | 3,500 | 300 | -11,500 | -2,500 | 500 |
| take 1% of contract | 3,500 | 1,000 | -46,500 | -16,500 | -6,500 |
| take 1% of contract | 3,500 | 3,000 | -146,500 | -56,500 | -26,500 |
| take 3% of contract | 10,500 | 300 | -4,500 | 4,500 | 7,500 |
| take 3% of contract | 10,500 | 1,000 | -39,500 | -9,500 | 500 |
| take 3% of contract | 10,500 | 3,000 | -139,500 | -49,500 | -19,500 |
| take 5% of contract | 17,500 | 300 | 2,500 | 11,500 | 14,500 |
| take 5% of contract | 17,500 | 1,000 | -32,500 | -2,500 | 7,500 |
| take 5% of contract | 17,500 | 3,000 | -132,500 | -42,500 | -12,500 |
| flat 10,000 | 10,000 | 300 | -5,000 | 4,000 | 7,000 |
| flat 10,000 | 10,000 | 1,000 | -40,000 | -10,000 | 0 |
| flat 10,000 | 10,000 | 3,000 | -140,000 | -50,000 | -20,000 |
| flat 25,000 | 25,000 | 300 | 10,000 | 19,000 | 22,000 |
| flat 25,000 | 25,000 | 1,000 | -25,000 | 5,000 | 15,000 |
| flat 25,000 | 25,000 | 3,000 | -125,000 | -35,000 | -5,000 |

Max cost per brief = fee x r (d=0):
take 1% of contract [70, 175, 350]
take 3% of contract [210, 525, 1050]
take 5% of contract [350, 875, 1750]
flat 10,000 [200, 500, 1000]
flat 25,000 [500, 1250, 2500]
fixed_total 400000
Viable cells (contr>0): 15 of 45


### Not financial, tax or legal advice

An accountant should check the structure, the tax on the fee and on pass-through payments, and payroll costs before any money moves. The escrow and payment rules are unconfirmed (`ops.md` section 6, items 4 and 5).

---

Script output for the base placeholders (below) is in the same folder as this note and repeats the base case above; ignore its "$" labels.

---

## Unit economics: Builder marketplace, flat renovation (PLACEHOLDER base case, unit = one signed job)

Every number below comes from the input file. Nothing is looked up or guessed.

### One signed job (one renovation contract)

| line | per signed job (one renovation contract) |
| --- | ---: |
| Price | $10,500.00 |
| Payment processing (ASSUMPTION: 0 in introduction-only branch A; ~1.5% if platform holds money, branch B) | -$0.00 |
| Customer acquisition per signed job = cost per brief 1,000 / brief-to-contract rate 5% (ASSUMPTION both) | -$20,000.00 |
| **Contribution** (what each signed job (one renovation contract) leaves to pay the fixed costs) | **-$9,500.00** (-90%) |

### The margin that matters

Fixed costs: $400,000 a month (Operations base: staff, tools, legal retainer (PLACEHOLDER, no source) $300,000, Builder verification: 10 builders/month x 10,000 per verified builder (ASSUMPTION both) $100,000).

- **Break-even: never (each unit loses money) signed job (one renovation contract)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (0 a day): **-471%** of every sale, after every cost.

### Year 1, month by month

| month | signed job (one renovation contract)s a day | revenue | profit | cumulative (after $450,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | $104,989 | -$494,990 | -$944,990 |
| 2 | 0 | $104,989 | -$494,990 | -$1,439,981 |
| 3 | 0 | $104,989 | -$494,990 | -$1,934,972 |
| 4 | 0 | $104,989 | -$494,990 | -$2,429,962 |
| 5 | 0 | $104,989 | -$494,990 | -$2,924,952 |
| 6 | 0 | $104,989 | -$494,990 | -$3,419,943 |
| 7 | 0 | $104,989 | -$494,990 | -$3,914,934 |
| 8 | 0 | $104,989 | -$494,990 | -$4,409,924 |
| 9 | 0 | $104,989 | -$494,990 | -$4,904,914 |
| 10 | 0 | $104,989 | -$494,990 | -$5,399,905 |
| 11 | 0 | $104,989 | -$494,990 | -$5,894,896 |
| 12 | 0 | $104,989 | -$494,990 | -$6,389,886 |

- **Year 1 operating profit: -$5,939,886** on $1,259,874 of revenue.
- After the $450,000 startup spend: -$6,389,886.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$6,389,886**.

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -471% | never | -$5,939,886 |
| Price -10% | -535% | never | -$6,065,873 |
| Volume -20% | -567% | never | -$5,711,909 |
| Unit costs +15% | -500% | never | -$6,299,850 |

### Red flags

- Each unit loses money before rent and salaries: the price is below the variable cost.
- Year 1 loses money on operations (-$5,939,886).
- The startup spend is not earned back within year 1.

## Marketing

Market assumed for this plan: private owners of an apartment in a large Russian-speaking city who want a flat renovation done. City, country and launch date are not set in `idea.md`. Channels below assume Russia; if the city is elsewhere, re-check every channel.

Inputs read: `idea.md`, `board.md`, `competitors.md`, `panel/results.md`, `panel/results.json`, `customer.json`, `pitch.md`.

Missing inputs (the skill expects these; none exist in this folder): `offer.md`, `pricing.md`, `numbers.json` (founder-offer, founder-pricing, founder-cfo not run). Consequences are marked where they bite. Budget, CPC, conversion and audience size are not sourced anywhere here and are not invented.

### Gate: do not spend on ads yet

The panel result is **0 buys out of 20** (seed 975635). Every segment, behaviour and income band scored 0%. Sixteen of the 20 passes cite trust; three cite the price (fee not stated); one cites habit. Founder-marketing needs a segment with a buy rate to pick the first audience. None exists, so the audience below is chosen by the frequency of the objections, not by buying.

Spend starts only when all of these are true:

1. One city and one job type are named, with a market size that has a source (board condition, still open).
2. The fee is published as a number, and the money-flow decision (escrow or introduction only) is made. Escrow is not confirmed legal for flat renovation: `competitors.md` finds the escrow rule (186-FZ) tied to private-house contracts. Get a legal check first.
3. The verification process exists and a set number of builders in the city have passed it (the board's number, not yet set). Verified past work is shown to customers.
4. The revised offer is re-tested on a panel (founder-consumer) and gets buys. The current pitch gets none.

If gate 4 fails, marketing will not fix it. The panel's "what would flip a no" answers are the product brief, not ad copy.

### Step 2: positioning

The verdict on evidence: trust is the dominant pass reason (16 of 20), and the competitor map leaves one empty corner, verified contractors with money held for apartment renovation (`competitors.md`, section 3). Free bid boards (Ремонтник, Ремонт-квартиры.ру, Мастер Дел, ForumHouse) give offers with no common scope. Lead marketplaces (Profi, YouDo) are criticised for fees and weak support. RERATE gives rated firms with no money held.

Three versions, in the skill's format:

- **A (trust, recommended):** For apartment owners who do not want to hire an unknown crew, X is the renovation marketplace that checks each builder's finished work before listing it and pays by stage only when you sign off, unlike bid boards that send unchecked offers.
- **B (comparable bids):** For owners who get three quotes and cannot compare them, X is the way to compare: one standard brief, and every builder prices the same scope, unlike bid boards where each firm describes the job differently.
- **C (hands-off):** For owners who do not want to chase builders, X writes the brief, collects bids and holds the contract, unlike RERATE or Profi, where you still do the chasing.

**Recommend A.** The panel's largest objection is trust, and no page read in `competitors.md` owns verified apartment renovation. Use B as the second message, at the bid step. Do not use A's "pays by stage" wording until the legal check (gate 2) clears; until then say "verified builders" only.

Panel evidence is research. It is not proof the positioning sells (0 of 20 bought).

### Step 3: channels

Target buyers from the panel (the skill's audience rule): the "Reads reviews, slow to trust", "Burned before" and "Gets three quotes" behaviours carry the largest share of trust and comparison objections. They search, read reviews and ask for referrals. Channels follow from that.

**Start with two, plus one zero-cost channel:**

1. **Yandex Search (Yandex Direct), renovation intent queries, one city.** Fits a buyer who searches "ремонт квартиры под ключ + city" and reads reviews. Cost: Yandex auction; CPC not sourced here, measure it. Works if: cost per brief submitted is at or under the max in Step 5.
2. **Telegram and VK: renovation content and the free brief template.** The standard brief (one page, what to price, what to include) answers the "how do I compare bids" objection on its own and gets people to submit a brief. Paid reach via Telegram Ads and VK Ads, marked as test budget. Cost: not sourced, measure. Works if: a brief is submitted and then gets bids.
3. **Pilot jobs recruited through direct outreach (zero media cost).** The first 5 to 10 real renovations are found by asking apartment owners and renovation firms directly, then done by hand (board condition: test the flow by hand first). Their finished, checked work is the only proof that makes referrals work. Cost: staff time, costed by founder-cfo (not run).

**Not doing, and why:**
- **Instagram and Facebook paid, TikTok:** Meta products have been restricted in Russia since 2022; check the current status before any plan relies on them. Not a channel to build on here.
- **Influencers and "as seen on":** breaks the no-fake-testimonials rule and the panel's trust objection.
- **Outdoor, print, radio:** no city is set; cost per buyer cannot be estimated.
- **Marketplace listings on Profi or YouDo:** that means paying their lead fees, which buyers call the problem.

### Step 4: 30-day campaign

Launch day is not set. Days below are relative to **D0 = opening day**. Campaign opens only after the gate above.

| Days | Channel | What goes out |
|---|---|---|
| D-14 to D-10 | Outreach | Build the list of 30 apartment owners and renovation firms in the city. Send pilot-job invitations. |
| D-14 to D-10 | Telegram and VK | Publish the standard brief template (free). One post a day: what a brief must include. |
| D-9 to D-5 | Telegram and VK | "How to compare three bids" posts, using the brief as the frame. Show how one scope makes prices comparable. |
| D-9 to D-5 | Yandex Direct | Set up renovation-intent ad groups, landing page with the brief form, conversion tracking. Ads not yet live. |
| D-4 to D-1 | Yandex Direct | Go live at low test budget (see Step 5). Answer every brief within one working day. |
| D-4 to D-1 | Telegram and VK | Behind-the-scenes: the pilot job being done, checked, signed off. Use only real work, with the owner's consent. |
| D0 | All | Opening: the verified builder list in the city, the published fee, the brief form. |
| D1 to D3 | Telegram and VK | Explain the fee and what the platform does for it, with the figure. |
| D1 to D3 | Yandex Direct | Keep the two best-performing ad groups; pause the rest by Step 5 rule. |
| D4 to D7 | Telegram and VK | "Check the builder" post: what is verified, what is not. |
| D8 to D11 | All | Pilot-job write-up with the owner's permission (scope, stages, sign-off). No invented results. |
| D12 to D16 | Review | Read the three numbers in Step 5. Decide: keep, change channel, or stop. |

**Ten hooks** (Russian, English gloss). Each answers a panel objection. Format given per hook. Fee and price figures are placeholders until the pricing is set.

1. "Ремонт квартиры без «наверное»: каждый мастер с проверенными работами." (Flat renovation without guessing: every builder has checked past work.) Answers "Who checks the builder?" Format: ad headline. Only after the verification process exists.
2. "Три сметы — одно техзадание. Сравниваем цену, а не обещания." (Three bids, one brief. Compare prices, not promises.) Answers "Bids never describe the same work." Format: 3-second video opening line.
3. "Деньги уходят по этапам — только после вашей приёмки." (Money goes out by stage, only after you sign off.) Answers "What if it goes wrong halfway?" Format: window sign or ad headline. Gate 2 must clear first.
4. "Срыв сроков и бюджета — это условие договора, а не надежда." (Missed deadlines and budgets are written into the contract, not left to hope.) Answers "Burned before." Format: ad headline.
5. "Не берите три сметы наугад. Опишите ремонт один раз." (Don't take three quotes at random. Describe the job once.) Answers "Gets three quotes." Format: 3-second video opening line.
6. "Вы занимаетесь жизнью, а не поиском мастера. Бриф, сметы и договор — на нас." (You get on with your life, not with finding a builder. Brief, bids and contract are on us.) Answers "Hands-off." Format: ad headline.
7. "Уже есть бригада? Оформим договор и этапы оплаты за фиксированную плату [ФИКС]." (Already have a crew? We'll set up the contract and stage payments for a fixed fee [FIXED FEE].) Answers "Already has a crew." Format: ad headline. Fee placeholder.
8. "Самая низкая цена не всегда самая дешёвая: смотрите, что входит в смету." (The lowest price is not always the cheapest: look at what the bid includes.) Answers "Price-first." Format: carousel slide.
9. "Почему мы не берём деньги с мастера за лид: [ПРАВИЛО КОМИССИИ]." (Why we do not charge the builder per lead: [COMMISSION RULE].) Answers "Why pay a platform on top?" Format: explainer video. Commission rule placeholder.
10. "Спросите соседей, кто делал ремонт, потом проверьте его работы здесь." (Ask your neighbours who did their renovation, then check that builder's work here.) Answers "Referral-led": uses referral, does not claim a referral. Format: Telegram post.

Rules for every hook: no invented reviews, follower counts or before/afters; no panel quote as customer quote; disclose any paid partnership. Russian online advertising carries a mandatory ad-marking requirement (ERID tokens via the ORD system); check with a lawyer before the first ad goes live. Not legal advice.

**Launch-week offer:** not set. `pricing.md` does not exist. Do not run an offer until the fee is published.

**When there is nothing new to say:** the pilot job (with the owner's permission), the builder check process, the brief template updated from real bids.

### Step 5: budget and numbers

**Budget:** not set in any input. The split below is a starting ratio for the test phase, not a benchmark. Replace with measured cost per brief after D12.

- Yandex Direct: 50 per cent of test budget
- Telegram and VK ads: 30 per cent
- Reserve for pilot-job costs and content: 20 per cent

**Max you can pay to win one customer** (formula; inputs not yet computed):

- Contribution per signed job = platform fee on the contract − direct costs per job (payment fees, verification cost allocated per builder, support time). Founder-cfo has not run; this number does not exist yet.
- Max cost per signed job = contribution per signed job (CFO).
- **Max cost per brief submitted = Max cost per signed job × brief-to-signed-contract rate.**

The brief-to-contract rate is not in the panel (0 buys means the panel gives no rate). Measure it in the pilot. Until it is measured, no channel has a max. Example, with placeholders only: fee F, direct cost D, rate r. Max cost per brief = (F − D) × r. Fill in the three when known.

**Three numbers to watch weekly:**

1. **Cost per brief submitted, per channel.** Change something if it is above the max cost per brief for two weeks running. Stop a channel that is above max for four weeks.
2. **Comparable bids per brief.** Target: at least three bids per brief. Below three, supply is not ready. Pause paid traffic; do not add spend.
3. **Brief-to-signed-contract rate.** Change something if it falls below the rate at which Step 5's max equals actual cost per brief.

### Verdict for the board

No paid spend until the Step 1 gates clear. The current pitch scored 0 of 20. Next steps, in order: fix the offer and pricing (founder-offer, founder-pricing), run the CFO (founder-cfo) to get the contribution figure, re-run the panel on the revised pitch, then this plan.

Next: `/founder-brand`, then `/founder-launch`.

## Brand

Working name: none chosen. Three shortlisted candidates below. Nothing here is checked for availability, and nothing is registered.

### Inputs and gaps

- Read: `idea.md`, `board.md`, `competitors.md`, `pitch.md`, `panel/results.md`.
- **Gap: `marketing.md` does not exist** in this folder, so there is no signed-off positioning line. The promise and voice below are derived from the panel's "what would flip a no" answers and the gap in `competitors.md` (apartment renovation with verified firms and stage-by-stage payment). Run `/founder-marketing` and check these against its positioning before locking anything.
- **Gap: market not fixed.** No city or country is set. Names are tested for Russian and Latin script, since the founder's references are Russian-language. Confirm the market before the trademark search.

### Step 2: name candidates

Ten candidates, then three shortlisted.

| # | Candidate | Style | What it says | Sounds out loud | On a sign or 32px icon | Risk |
|---|---|---|---|---|---|---|
| 1 | Etap (Этап) | Descriptive | "Stage": pay per stage | Easy, two syllables | Strong short mark | Common Russian word; many firms use it |
| 2 | Vekhi (Вехи) | Evocative | "Milestones": the sign-off points | Medium | Needs a simple mark | Less common; spelling varies in Latin script |
| 3 | Krepko (Крепко) | Evocative | "Solid, firmly built" | Easy | Good with a strong glyph | Common adverb; weak link to renovation on its own |
| 4 | Smeta (Смета) | Descriptive | "Estimate" | Easy | Reads well | Very common word; likely crowded in class 37 |
| 5 | Akt (Акт) | Descriptive | "Sign-off act" | Very short | Good icon | Too generic; hard to search |
| 6 | Ryadom (Рядом) | Evocative | "Nearby" | Easy | Fair | Suggests local search, not a marketplace |
| 7 | Brif (Бриф) | Descriptive | "Standard job brief" | Easy | Fair | Generic in marketing |
| 8 | Fixa | Invented | Fix plus "fixed" | Easy | Strong | Likely used by many firms in English |
| 9 | Stagely | Invented | Stage plus "-ly" | Medium | Good | Latin only; no Cyrillic form yet |
| 10 | Dom Vdvoem (Дом вдвое) | Place/phrase | Playful | Hard | Weak | Too long for a sign |

Shortlist: **Etap**, **Vekhi**, **Krepko**. Reasons: each ties to the promise (paid by stage, milestones, solid work), and none is close to a name in `competitors.md` (RERATE, Profi, YouDo, ПАЗЛ ДОМ, ДОМ.РФ, Петрович, Smartremont, MyBuilder).

#### Checks the founder must finish (public searches only)

- **Trademark**: search each market's official register for the name in Nice classes **35** (online marketplace and business services), **36** (payment and escrow services), **37** (construction and renovation) and **42** (software). Registers:
  - Russia: Rospatent, https://www1.fips.ru
  - US: USPTO, https://tmsearch.uspto.gov
  - EU: EUIPO, https://euipo.europa.eu/eSearch
  - UK: UKIPO, https://www.trademarks.ukipo.gov.uk
  - Canada: CIPO, https://ised-isde.canada.ca/cipo/trademark-search
- **Domain**: check the .ru, .com and local domain for each name. Do not assume any is free. Alternatives if taken: add a city or the word "dom" or "remont" in front (for example, "EtapRemont"), but check each one.
- **Handles**: Instagram, TikTok, X, YouTube, Telegram. Check each name, including Cyrillic and Latin spellings.
- **Confusion**: no name close to a competitor in `competitors.md`. Re-check after the market is chosen.
- I can only run public searches. A trademark lawyer confirms registrability. Nothing is registered until the founder registers it.

### Step 3: voice and promise

**One-line promise** (derived; confirm against marketing): *Your money is released only when each stage of your renovation is signed off.*

Why this line: the panel's most common "what would flip a no" was held payment released per stage, plus verified builders. The competitor gap is that no page read sells both for apartments.

**Tagline options (three)**
1. Describe the job once. Pay as the work is signed off.
2. Every bid on the same brief. Every stage on the same record.
3. Renovation, in stages you can check.

**Voice in three adjectives**

| Adjective | Do | Don't |
|---|---|---|
| Plain | Say what happens to the money and the bid, in short sentences. | Use industry jargon such as "escrow solution" or "ecosystem". |
| Checkable | Give a number, a date or a named step. "Stage 2 is released after you sign the bathroom." | Promise "the best builders" with no evidence. |
| Calm | Admit what is not known yet, such as the fee before launch. | Use urgency or pressure ("Only 3 spots left!"). |

**Before and after (from `pitch.md`)**
- Before: *"A platform for private customers who want a flat renovation done."*
- After: *"Describe your flat job once. Builders bid on the same brief, and you pay in stages as you sign off each one."*

### Step 4: the look (brief)

**Colour** (contrast checked against WCAG AA for normal text, 4.5:1)

| Role | Hex | Job | Contrast |
|---|---|---|---|
| Primary: deep navy | #1F3A5F | Headings, the logo, primary buttons | 11.5:1 on white; 10.5:1 on off-white |
| Accent: terracotta | #A8452A | Stage markers, one call to action per screen | 5.9:1 on white; 5.4:1 on off-white |
| Neutral: off-white | #F7F4EE | Page background | Text #1B1B1B on it: 15.7:1 |

Green #2E6B4F (6.3:1 on white) is a reserve colour for "signed off" states only. Never use colour alone to show a status; pair it with a word.

**Type** (both free, open-licence Google Fonts, with Cyrillic support; confirm the Cyrillic glyphs on the chosen font before use)
- Display: Source Serif 4 (SIL Open Font License). Get it at fonts.google.com.
- Text: Inter (SIL Open Font License). Get it at fonts.google.com.

**Logo brief**
- Must say: a stage or milestone, and a solid build. One mark, not a picture of a house.
- Must work: a sign on a van, a 32px app icon, a black-and-white invoice stamp.
- Avoid: roofs and house silhouettes (common in every builder listing), hard hats, trowels, and any shape close to ДОМ.РФ or ПАЗЛ.
- Generated concepts: if the founder has an image tool, ask for concepts in a single colour first. Mark every output as a concept, not a finished logo.

**The first five touchpoints**
1. **Homepage or sign-up**: the promise line, one button ("Describe your job"), and the stage-payment explanation above the fold.
2. **Standard job brief**: the form itself, with the same fields for every bid, so the customer sees the scope is shared.
3. **Payment confirmation**: the amount held, when each stage is released, and who signs off.
4. **First social post**: a real finished flat, with the stages shown. No stock photos of builders.
5. **Reply to the first complaint**: name the stage, say what is held, and give the next step and a date.

### Rules

- Never copy a competitor's name, logo, colours or tagline.
- Fonts above are open-licence. Check the licence of any image or icon before use.
- This is not legal advice on trademarks or on escrow. The escrow rule cited in `competitors.md` (Federal Law 186-FZ) is tied to private-house contracts; a legal check is needed before the promise is published.

### Next

`/founder-ops` and `/founder-launch`. Before those: run `/founder-marketing` to create `marketing.md`, then re-check the promise line against it.

## Operations

Run date: 2026-11-19. Built from `idea.md`, `pitch.md`, `customer.json`, `board.md`, `board/*.md`, `competitors.md` and `panel/results.md` in this folder. Nothing in `/home/user/Ideas/founder/` was read or written.

**Read this first.** Country, city, job type (flat renovation is the board's candidate), commission and the money model are all still open. So this plan is a set of branches, not one run-sheet. Every price, wage, fee, permit rule and legal point below is marked **VERIFY** and names the source to check. None is a fact yet. Competitor figures come from `competitors.md` and are data points about other firms, not our costs.

---

### 0. The decision the operations depend on: the money seam

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

### 1. The daily cycle and the job lifecycle

#### Platform's daily cycle (once live)

- **Start of day:** new job briefs to check for completeness; new builder applications; disputes and stage-acceptance requests waiting; payments due (only if branch B).
- **Through the day:** coordinator replies within the response time set in the test; bid windows closing; selection and contract steps.
- **End of day:** status update on every active job; change orders logged; list of stuck jobs (no stage report for the set number of days).

#### Job lifecycle with an owner for each handoff

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

### 2. Suppliers: builders and the vendors behind the platform

#### 2a. Builders (the supply side)

- **Where to find them:** the board's own list of named firms in `competitors.md`, plus direct outreach. Among the named firms, only ДОМ.РФ and ПАЗЛ ДОМ are verified contractor catalogues, and both are built for new private houses. Renovation firms appear in directories that were last checked in 2020 (unverified). **VERIFY** any builder before contact, and check each one's status in the national company register and any licence or membership register for the chosen country.
- **What builders pay the platform:** unknown. The only explicit schedule in the sources is ПАЗЛ ДОМ's: 20,000 RUB per object, 1% of each finance tranche, and 3-5% per partner lead ([contractor terms](https://lp.pzzl.ru/contractors)). It is one data point, from a different product, in a different country. Use it as a reference for the commission test, not as our price.
- **Commitment before customers:** the board requires a set number of signed builders in the launch city before any customer is promised bids. The number is set by the founder (Monopoly). Not set here.

#### 2b. Vendors and services

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

### 3. People

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

### 4. Routines (SOPs)

Each routine is short, numbered, and should fit on one page. Times in brackets are set in the test.

#### SOP-1: Builder verification (before listing)

1. Collect: legal entity or sole-trader details and tax number; licence or membership if the work type requires one in the chosen country (VERIFY which work needs what); liability insurance if available; list of at least [N] finished flats or houses with client contacts.
2. Check the company register for status (active, not in liquidation or insolvency) and the owner. Check the licence or membership register where one applies.
3. Check court records for recent disputes against the company (public court record search for the country).
4. Call at least [N] past clients. Record the answers on the same form.
5. Visit one finished job, or see photos and a stage acceptance from it, before listing.
6. Approve or reject within [X] days. Show the verified mark and past work on the profile. Re-verify every [period].

#### SOP-2: Posting a job and the standard brief

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

#### SOP-3: Bid process and comparing bids

1. Bid window opens with the brief sent to all verified builders in the city (the number is the founder's; see section 2a).
2. Each builder bids on the **bid template**, which mirrors the brief line by line. Required per line: quantity, unit, unit price, material supplier and grade, and time in days. Also required: total time, exclusions, validity date, change-order unit rates, warranty period, and proposed payment stages.
3. **Complete-bid rule:** a bid with any unpriced line, or with no change-order rates, is marked incomplete and cannot be selected. The coordinator tells the builder what is missing.
4. The comparison sheet puts complete bids side by side. It shows the lowest bid, the spread, and each bid's exclusions. It does not rank by price alone.
5. Customer picks within [X] days after the window closes. The coordinator then fills the contract template with the chosen bid's values.

#### SOP-4: Contract and first payment

1. Contract is generated from the template with the chosen bid. Both parties sign.
2. Payment schedule comes from the bid's stages. Branch A: customer pays the builder directly, and the platform records each payment. Branch B: customer pays the platform, which releases by stage after acceptance (SOP-6).
3. Platform keeps the signed contract and every stage record. These are the evidence in any later dispute.

#### SOP-5: Change order

1. No work outside the signed scope without a written change order.
2. The builder fills the change order: what changes, why, the cost at the bid's unit rates, days added, and the effect on the deadline.
3. Customer approves before the work starts. The builder may refuse to start unapproved work.
4. The platform logs it and shows the customer a running total of all change orders against the original contract value on every approval.
5. Any change above [threshold, set in test] or above [% of contract] is reviewed by the ops lead before approval.
6. **Gap to close:** if a bid has no unit rates for changes, every later change is open to dispute. The bid template must make this a required field (section SOP-3 step 2).

#### SOP-6: Stage acceptance and payment release

1. Builder files a stage report: photos, a short description, and a checklist against the stage's acceptance criteria.
2. Customer accepts or lists defects within [X] days. No reply after [X] days is recorded as accepted only if the contract says so (VERIFY that silence-as-acceptance is valid in the chosen country; do not rely on it until checked).
3. Branch B: payment released on acceptance. Branch A: acceptance recorded; customer pays the builder.
4. Defects are fixed and re-checked before the stage closes.

#### SOP-7: Dispute

1. **Level 1 (coordinator, within [X] days):** talk to both parties, separately then together. Record the agreed fix in writing.
2. **Level 2 (ops lead, within [X] days):** review the brief, the bid, the contract, the stage reports, photos and messages. Decide the fix. Branch B: pause releases on the disputed stage only.
3. **Level 3 (independent inspection):** an external inspector checks the disputed work against the acceptance criteria. Cost split between the parties by a rule set in advance (not yet set; the platform must decide and show it in the contract).
4. **Level 4 (outside the platform):** the courts or the chosen country's dispute route. The platform hands over the file.
5. **What the platform cannot do:** force a builder to pay or finish, unless the contract and the country's law give it that power (VERIFY with the lawyer). The platform's job is to keep clean records, run the levels, and show the evidence.
6. Every dispute ends with a builder record update: note, warning or suspension.

#### SOP-8: Builder stops mid-job

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

#### SOP-9 (Weekly, replaces "reorder"): Builder supply check

1. Count verified builders per trade and per district in the launch city, against the number the founder set.
2. Count open bid windows and builders who did not bid on the last [N] briefs. Ask them why.
3. Recruit or verify to fill trades with gaps before the next brief goes out.
4. Review the week's disputes and suspensions by builder. Remove any builder with two or more confirmed disputes in a [period], or as the ops lead decides.

---

### 5. Tools

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

### 6. Licences, permits and insurance (checklist, all VERIFY)

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

### 7. Risk register

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

### 8. Real costs for the CFO

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

### 9. Open questions (blocking first)

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

### Next step

Run `/founder-launch` once the country and city are chosen, the money seam is decided, and the section 6 legal checks are back. Until then, the launch plan can only be a by-hand test: a brief form, a verified shortlist, a bid template, and a record of every handoff.

## Launch plan

**Status: draft. This is not a launch.** Not set: city, country, opening date, money model (escrow or introduction only), fee, builder count. Nothing is priced and no cost is entered. Every cost is a `[PLACEHOLDER]` until a source or quote exists.

**Date basis:** all dates are relative to **D0 = launch decision day**. Opening day is `OPEN = D0 + [W] weeks`, set when the gates in section 1 clear. `OPEN-14` in this file is the same as `D-14` in `marketing.md`, which counts from opening day.

**Inputs read:** `idea.md`, `board.md`, `offer.md`, `marketing.md`, `ops.md`, `panel/results.md`.
**Not read:** `/home/user/Ideas/founder/` (a different business, excluded by instruction). `numbers.json` does not exist in `founder-builders/`, so the CFO step has not run.

---

### 0. Where we stand

- **Panel: 0 of 20 buy** (simulated, seed 975635). 16 of 20 pass on trust, 3 on the unstated fee, 1 on habit. The panel gives an objection list, not a benchmark: no real-world number exists yet to compare against.
- **Board: 3 "fund if".** Open conditions: name one city and one job type (flat renovation is the candidate), decide the money seam, verify builders before listing, set the fee, and check the two Russian references directly.
- **Ops and marketing agree on one rule:** no money claim ("escrow", "held", "protected payment", "pays only after you sign off") in any public material until a lawyer confirms it.

### 1. Gates: all four must pass before OPEN

| # | Gate | Pass when | Owner | Status |
|---|---|---|---|---|
| G1 | Named city and job type | One city and flat renovation are named, with a market size that has a cited source. | Founder | Open |
| G2 | Verified builders | At least `[N]` builders in the city have passed SOP-1 (company register, court records, `[N]` reference calls, one site visit or stage photos). Their checked past work can be shown. `[N]` is set by the founder (board condition). | Ops: onboarding | Open |
| G3 | Published fee | One fee (a number or a formula) is published. It comes from `/founder-pricing`, and the CFO confirms it covers direct cost per job (`numbers.json`, not yet created). | Founder + CFO | Open |
| G4 | Legal check on the money flow | A lawyer confirms: (a) whether the 186-FZ escrow rules (private houses) reach flat renovation (`ops.md` section 6, item 4); (b) the rules for handling customer money (item 5); (c) the platform's status (agent, broker or party). The founder then picks branch A (introduction only, customer pays builder) or B (platform holds money). Until G4 clears, branch A and no money claims. | Founder + lawyer | Open, blocking for branch B |

**Gate rule:** if any gate is open on D0, there is no launch. The first test can run before D0 because it takes no money and makes no money claim.

**Also before any public ad (not launch gates, but required):** personal-data notice and consent for the brief form (`ops.md` item 7); advertising-rule review, including Russian ad marking if the launch market is Russia (`marketing.md`); the offer re-test on the consumer panel (`marketing.md` gate 4).

---

### 2. The first test (before D0)

**What it tests:** whether real owners in one city will describe a job in the standard brief and join the waitlist. This is the cheapest real signal, and it tests the trust objection the panel found most often.

**Phase 1a: brief form and waitlist page**

- One landing page for one city. It has the standard brief form (the fields from `ops.md` SOP-2, shortened for the first version) and a waitlist ("tell me when bids open in [CITY]").
- **No payment, no deposit, no pre-order.** The money gate (G4) is still open.
- **Price:** version A shows no price, because none is published. When G3 gives a fee, version B is added: two planned fees, `[FEE A]` and `[FEE B]`, split 50/50 between visitors. Each price is labelled as a planned fee for a service not yet running. Nothing is charged.
- **Page claims must be true today.** Say "we check builders in [CITY] before listing them" only once G2 work has started. Do not say "verified", "guaranteed", "protected", or "pay by stage".
- **Channels: zero media cost.** (a) Direct outreach to the 30 owners and renovation firms listed in `marketing.md` D-14 to D-10. (b) One free Telegram or VK post a day. **No paid ads** in this test: `marketing.md` says no ad spend until the offer re-test shows buys. If the founder wants a paid test anyway, that is a decision to make first, with a `[TEST BUDGET]` placeholder.

**Phase 1b: by-hand pilot (board condition)**

- `[3]` real renovation jobs run by hand in the test city: brief, bid template, comparison sheet, stage sign-off log (all on forms or a spreadsheet).
- Customers pay the builder directly (branch A). The platform takes no fee during the pilot until G3 and G4 clear. The pilot contract form is checked by the lawyer.

**Success line (founder sets the numbers before the test starts):**
`[N] completed briefs and [M] waitlist sign-ups from [CITY] within [T] days of the page going live, with at least [K] from people outside the team's network, and at least 3 comparable bids per brief for the pilot jobs.`

The panel's 0 of 20 cannot set this line. It is simulated, and a real rate above zero would already be new information. If real owners submit briefs but do not sign up or do not bid, go back to `/founder-offer` or `/founder-pricing` and do not launch.

**Read the result on D-1. Decide on D0.**

---

### 3. Countdown: D0 to OPEN

The lawyer's turnaround (G4) and the verification pace (G2) set the length. Neither is known, so OPEN is not dated. Weekly blocks run from D0. Critical path items are marked **CP**: if they slip, OPEN slips.

| Block | Task | Owner | Deadline | |
|---|---|---|---|---|
| Week 0 | Choose city, job type, branch (A or B), and fee approach | Founder | D0+7 | **CP** |
| Week 0 | Brief the lawyer on G4 items (a) to (c), consumer duties, personal data, ad rules | Founder | D0+7 | **CP** |
| Week 0 | Start SOP-1 checks on builder candidates in the city | Ops: onboarding | D0+7, then weekly | **CP (G2)** |
| Week 0 | Create `founder-builders/numbers.json` by running `/founder-cfo`: cost per builder, per customer, per job | Founder + CFO | D0+14 | **CP (G3)** |
| Week 1 to 2 | Lawyer's answers on G4; contract template drafted for the chosen branch | Lawyer | `[date from lawyer]` | **CP (G4)** |
| Week 1 to 2 | Brief form, bid template, comparison sheet, stage sign-off and change-order forms (`ops.md` SOP-2, 3, 5, 6) | Ops lead | D0+21 | |
| Week 1 to 2 | Publish the fee (G3) | Founder | After CFO | **CP (G3)** |
| Week 2 | Name and brand check (trademark, domain, handle) before any public page carries the name | Founder | Before Phase 1 | |
| Week 2 | Phase 1a page and waitlist live; Phase 1b pilot jobs start | Founder + coordinator | Before D-40 (see section 2) | |
| Weekly | Count verified builders per trade against `[N]`; count bids per brief | Ops: onboarding | Every week | |
| OPEN-14 | Marketing calendar starts, per `marketing.md` (paid ads only if its gates pass) | Founder | OPEN-14 | |
| OPEN-7 | Coordinator hired and trained; ops lead has a trained backup | Founder | OPEN-7 | |
| OPEN-3 | Soft open: pilot clients and waitlist, one day, no public post | Coordinator | OPEN-3 | |
| OPEN-1 | Go/no-go: all four gates ticked and dated | Founder | OPEN-1 | **CP** |

---

### 4. Launch day run sheet (OPEN)

Times are offsets from opening. Clock times are set once `OPEN` is dated.

| Time | Who | Action |
|---|---|---|
| OPEN-2h | Founder | Re-check the four gates. If any fails, stop and move OPEN. |
| OPEN-2h | Ops: onboarding | Check the builder list is live and each entry has its checked past work. |
| OPEN-1h | Coordinator | Submit a test brief from outside the team. Confirm it reaches the inbox and the response clock starts. |
| OPEN-1h | Founder | Confirm the fee page and the consent text are live and match the approved wording. |
| OPEN | Founder | Post the opening message in Telegram and VK, per `marketing.md` D0 (the verified builder list, the published fee, the brief form). No offer until the fee is published. |
| OPEN to OPEN+4h | Coordinator | Answer every brief within the response time set in the test. Log each brief. |
| OPEN+4h | Ops lead | Check bids per brief. Fewer than 3 complete bids: pause paid traffic (none planned), do not add supply promises. |
| OPEN+8h | Founder | Read the first numbers: briefs, waitlist, bids. Write one line in the log. |
| End of day | Coordinator | List stuck jobs and open disputes. Ops lead reviews any dispute. |

**If something breaks** (from `ops.md` section 7):

- **Form or inbox down:** switch to the published email address; the coordinator logs the briefs by hand.
- **Builder drops out before contract:** remove from the list; replace from the bench; the brief stays open.
- **A customer or builder asks about held money:** answer with the branch-A wording only. Do not confirm escrow until G4 clears.
- **A wording problem found after publishing:** take the page down, fix, republish; log it.

---

### 5. The first 30 days after OPEN

**Weekly numbers (from the other skills):**

1. Cost per brief submitted, per channel. Max cost per brief = (platform fee − direct cost per job) × brief-to-contract rate. The CFO has not run, so the max is `[PLACEHOLDER]`.
2. Complete bids per brief. Target: 3. Below 3, supply is not ready.
3. Brief-to-signed-contract rate. Measured from the pilot and the first jobs; no benchmark exists.
4. Stage reports on time and stage sign-offs, plus the count of disputes and builder stops.

**Triggers (from `marketing.md`):**

- Cost per brief above the max for 2 weeks running: change something.
- Above the max for 4 weeks: stop that channel.
- Fewer than 3 bids per brief: pause paid traffic and fix supply.
- Brief-to-contract rate below the level at which the max equals actual cost per brief: change the offer or the price.

**Reviews:**

- **OPEN+7:** Supply and response times. Are bids complete? Is the response time met? Any stage report late?
- **OPEN+14:** Channel numbers and the first brief-to-contract rate. Keep, change channel, or stop.
- **OPEN+30:** Keep, change, or stop. Question to answer: has flat renovation in this one city been proven well enough to consider the second segment? Board says prove one segment first, so a second city or job type is not decided here.

---

### 6. Decisions the founder still owes

1. City and job type (G1).
2. Verified-builder number `[N]` (G2).
3. Fee level and who pays it (G3).
4. Money branch A or B, after the lawyer's answers (G4).
5. Success line numbers `[N]`, `[M]`, `[K]`, `[T]` (section 2).
6. Test budget: zero, or `[TEST BUDGET]` (and that choice affects `marketing.md` gate 4).
7. Opening date `OPEN` (D0 + `[W]` weeks).

### 7. Conflicts and notes

- The skill's file paths are `founder/`; this run used `founder-builders/` as instructed. `founder/numbers.json` in the skill maps to `founder-builders/numbers.json`, which does not exist.
- `marketing.md` counts from opening day; this file counts from D0 (decision day). Translated above.
- `marketing.md` says no paid spend before its gates. The first test therefore uses zero-cost channels.
- `offer.md`'s line "you pay only for stages you have signed off" is a claim, not a fact, until G4 clears. It appears in no public text in this plan.
- Nothing here is legal, tax or accounting advice. Every legal point is for the lawyer named in G4.

## Not done yet

- Summary: see executive-summary.md in this folder

_The panel is simulated buyers and the numbers are projections from your inputs. Confirm demand with real customers and costs with real quotes before you spend. Not financial, legal or tax advice._
