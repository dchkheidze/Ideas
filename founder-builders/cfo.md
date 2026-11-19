# CFO note: builder marketplace, flat renovation (PLACEHOLDER, no price decided)

**Status: nothing here is a result.** No price, commission, volume, cost or market size is decided or sourced. Every input in `numbers.json` is a labelled placeholder or ASSUMPTION. The script output below the grid uses the base-case placeholders only. Currency is not decided; the script's "$" is a hard-coded label, so read all values as unlabelled units.

## Break-even, as formulas

Per signed job (one renovation contract):

- Fee F = take rate t x contract value V (percentage basis), or a flat fee (flat basis).
- Contribution C = F - d - c_b / r
  - d = payment cost per job (0 if introduction only; branch B adds the payment partner's fee)
  - c_b = cost per brief submitted; r = brief-to-signed-contract rate
- Break-even signed jobs a month: J* = (fixed_monthly + n_v x c_v) / C, where n_v = verified builders a month and c_v = cost per verified builder. J* exists only if C > 0.
- Acquisition is affordable only if c_b < (F - d) x r. This is the marketing max cost per brief (`marketing.md`, Step 5).

## Which scenarios are viable

- Unit level: 15 of 45 grid cells have C > 0. They need a fee that clears the cost per brief at the brief-to-contract rate. A flat 25,000 fee or a 5% take with cost per brief 300 are the cases that clear.
- Monthly level: not proven viable. At the base placeholders (3% take, cost per brief 1,000, r 5%) C is negative and there is no break-even. Example positive cases at fixed costs of 400,000 a month: flat 25,000, cost per brief 300, r 10% gives C = 22,000 and J* about 18 jobs a month. Take 3%, cost per brief 300, r 10% gives C = 7,500 and J* about 53. Whether 18 or 53 signed jobs a month is possible in one city is unknown, because no market size is sourced.

## Inputs the founder must supply

1. Fee basis and level, and who pays it (builder, customer or both). Fee and contract value are the largest drivers.
2. Average contract value V. The 350,000 placeholder is 50 m2 x 7,000 per m2 (Profi "from" list price in `pricing.md`), not a completed-job figure.
3. Branch: introduction only (d = 0) or platform holds money (d set by the payment partner).
4. Cost per brief submitted and brief-to-signed-contract rate. Both come from a pilot test, not from the panel (0 of 20 bought).
5. Cost per verified builder c_v and builders verified a month n_v (`ops.md` SOP-1).
6. Fixed monthly operating cost: staff, tools, legal retainer (`ops.md` sections 3 and 5).
7. Startup spend: legal setup, contract templates, initial builder bench, launch test budget.
8. Signed jobs a month at plan and the year 1 ramp. No market size is sourced.
9. Guarantee cost and claim rate (`offer.md` section 3). Not modelled: the guarantee is undecided and its wording depends on the CFO's figure.

## The line to watch

The brief-to-contract rate. The break-even is most sensitive to r because acquisition cost is c_b / r. At 2% instead of 10%, a cost per brief of 1,000 adds 50,000 per signed job.

## Board conditions (`board.md`)

- "Write a distribution plan with cost per customer for the CFO to test": not met; no cost per brief exists.
- "Cost per verified builder and per customer (the CFO's ceiling)": not met; placeholders only.
- "Confirm the commission level with builders in a test": not met.

## Grid: contribution per signed job

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


## Not financial, tax or legal advice

An accountant should check the structure, the tax on the fee and on pass-through payments, and payroll costs before any money moves. The escrow and payment rules are unconfirmed (`ops.md` section 6, items 4 and 5).

---

Script output for the base placeholders (below) is in the same folder as this note and repeats the base case above; ignore its "$" labels.

---

# Unit economics: Builder marketplace, flat renovation (PLACEHOLDER base case, unit = one signed job)

Every number below comes from the input file. Nothing is looked up or guessed.

## One signed job (one renovation contract)

| line | per signed job (one renovation contract) |
| --- | ---: |
| Price | $10,500.00 |
| Payment processing (ASSUMPTION: 0 in introduction-only branch A; ~1.5% if platform holds money, branch B) | -$0.00 |
| Customer acquisition per signed job = cost per brief 1,000 / brief-to-contract rate 5% (ASSUMPTION both) | -$20,000.00 |
| **Contribution** (what each signed job (one renovation contract) leaves to pay the fixed costs) | **-$9,500.00** (-90%) |

## The margin that matters

Fixed costs: $400,000 a month (Operations base: staff, tools, legal retainer (PLACEHOLDER, no source) $300,000, Builder verification: 10 builders/month x 10,000 per verified builder (ASSUMPTION both) $100,000).

- **Break-even: never (each unit loses money) signed job (one renovation contract)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (0 a day): **-471%** of every sale, after every cost.

## Year 1, month by month

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

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -471% | never | -$5,939,886 |
| Price -10% | -535% | never | -$6,065,873 |
| Volume -20% | -567% | never | -$5,711,909 |
| Unit costs +15% | -500% | never | -$6,299,850 |

## Red flags

- Each unit loses money before rent and salaries: the price is below the variable cost.
- Year 1 loses money on operations (-$5,939,886).
- The startup spend is not earned back within year 1.
