# Launch plan: builder marketplace (working name not chosen)

**Status: draft. This is not a launch.** Not set: city, country, opening date, money model (escrow or introduction only), fee, builder count. Nothing is priced and no cost is entered. Every cost is a `[PLACEHOLDER]` until a source or quote exists.

**Date basis:** all dates are relative to **D0 = launch decision day**. Opening day is `OPEN = D0 + [W] weeks`, set when the gates in section 1 clear. `OPEN-14` in this file is the same as `D-14` in `marketing.md`, which counts from opening day.

**Inputs read:** `idea.md`, `board.md`, `offer.md`, `marketing.md`, `ops.md`, `panel/results.md`.
**Not read:** `/home/user/Ideas/founder/` (a different business, excluded by instruction). `numbers.json` does not exist in `founder-builders/`, so the CFO step has not run.

---

## 0. Where we stand

- **Panel: 0 of 20 buy** (simulated, seed 975635). 16 of 20 pass on trust, 3 on the unstated fee, 1 on habit. The panel gives an objection list, not a benchmark: no real-world number exists yet to compare against.
- **Board: 3 "fund if".** Open conditions: name one city and one job type (flat renovation is the candidate), decide the money seam, verify builders before listing, set the fee, and check the two Russian references directly.
- **Ops and marketing agree on one rule:** no money claim ("escrow", "held", "protected payment", "pays only after you sign off") in any public material until a lawyer confirms it.

## 1. Gates: all four must pass before OPEN

| # | Gate | Pass when | Owner | Status |
|---|---|---|---|---|
| G1 | Named city and job type | One city and flat renovation are named, with a market size that has a cited source. | Founder | Open |
| G2 | Verified builders | At least `[N]` builders in the city have passed SOP-1 (company register, court records, `[N]` reference calls, one site visit or stage photos). Their checked past work can be shown. `[N]` is set by the founder (board condition). | Ops: onboarding | Open |
| G3 | Published fee | One fee (a number or a formula) is published. It comes from `/founder-pricing`, and the CFO confirms it covers direct cost per job (`numbers.json`, not yet created). | Founder + CFO | Open |
| G4 | Legal check on the money flow | A lawyer confirms: (a) whether the 186-FZ escrow rules (private houses) reach flat renovation (`ops.md` section 6, item 4); (b) the rules for handling customer money (item 5); (c) the platform's status (agent, broker or party). The founder then picks branch A (introduction only, customer pays builder) or B (platform holds money). Until G4 clears, branch A and no money claims. | Founder + lawyer | Open, blocking for branch B |

**Gate rule:** if any gate is open on D0, there is no launch. The first test can run before D0 because it takes no money and makes no money claim.

**Also before any public ad (not launch gates, but required):** personal-data notice and consent for the brief form (`ops.md` item 7); advertising-rule review, including Russian ad marking if the launch market is Russia (`marketing.md`); the offer re-test on the consumer panel (`marketing.md` gate 4).

---

## 2. The first test (before D0)

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

## 3. Countdown: D0 to OPEN

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

## 4. Launch day run sheet (OPEN)

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

## 5. The first 30 days after OPEN

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

## 6. Decisions the founder still owes

1. City and job type (G1).
2. Verified-builder number `[N]` (G2).
3. Fee level and who pays it (G3).
4. Money branch A or B, after the lawyer's answers (G4).
5. Success line numbers `[N]`, `[M]`, `[K]`, `[T]` (section 2).
6. Test budget: zero, or `[TEST BUDGET]` (and that choice affects `marketing.md` gate 4).
7. Opening date `OPEN` (D0 + `[W]` weeks).

## 7. Conflicts and notes

- The skill's file paths are `founder/`; this run used `founder-builders/` as instructed. `founder/numbers.json` in the skill maps to `founder-builders/numbers.json`, which does not exist.
- `marketing.md` counts from opening day; this file counts from D0 (decision day). Translated above.
- `marketing.md` says no paid spend before its gates. The first test therefore uses zero-cost channels.
- `offer.md`'s line "you pay only for stages you have signed off" is a claim, not a fact, until G4 clears. It appears in no public text in this plan.
- Nothing here is legal, tax or accounting advice. Every legal point is for the lawyer named in G4.
