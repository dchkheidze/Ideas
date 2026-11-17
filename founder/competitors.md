# Competitors: HoReCa Hub, Tbilisi

Researched 17 November 2026 from public sources only. Every row links to its source; the raw data is in `competitors.csv`. Two sources couldn't be read: the Reddit thread (scraping blocked; only its search snippet is quoted) and Javshani's pricing (not public).

## 1. Who's there (most direct first)

| Name | Type | What it sells | Price | Source |
|---|---|---|---|---|
| **Wox** | Direct | POS + back office + free QR menu + **loyalty** (Apple/Google Wallet stamp cards, SMS/email) | POS 0 / 149 / 249 / 349 GEL a month; Loyalty 24 / 39 / 59 GEL a month | [pricing](https://wox.ge/en/pricing), [loyalty](https://loyalty.wox.ge/en) |
| **Keepz** | Direct (payment layer) | QR payment in the browser, no app: card, Apple Pay, Google Pay, pay-by-bank; tips | Free terminal (Credo); one user cites a 2.5% commission | [Omno](https://omno.com/payment-methods/keepz/), [Credo](https://credobank.ge/en/services/keepz-qr-terminal), [Play](https://play.google.com/store/apps/details?id=com.tipapp) |
| **Rezto** | Direct (booking) | Table booking + menu pre-order; about 126 partner restaurants | Subscription (price not public), "No commission fees"; diners get 10% off when they pre-order | [partners](https://rezto.ge/en/partners), [Play](https://play.google.com/store/apps/details?id=ge.rezto.app) |
| **SQR** | Direct | QR menu + POS + QR table ordering + inventory | From 30 GEL a month + VAT | [sqr.ge](https://sqr.ge/en) |
| **Javshani** | Direct (booking) | Premium restaurant and event booking; 26 restaurants | Not public | [about](https://javshani.com/about) |
| **QRMENUS** | Indirect | QR menu; the Business plan adds waiter calls, bill requests and table orders | 0 / 39 / 79 GEL a month | [pricing](https://qrmenus.ge/en/qr-menu-cost-georgia) |
| **Tripadvisor** | Indirect (directory + reviews) | Rankings + unverified reviews | Free for diners | [Tbilisi](https://www.tripadvisor.com/Restaurants-g294195-Tbilisi.html) |
| **Google Maps** | Substitute | Listings + unverified reviews | Free | — |
| **Bank of Georgia / TBC** | Substitute (payment) | Card POS terminals; QR payment through the mBank app | Bank terms | [expat guide](https://georgiaexpats.com/guides/banking/) |
| **jobs.ge / hr.ge** | Substitute (HR listings) | General job boards, full of waiter, chef and bartender vacancies | Not checked | [jobs.ge](https://jobs.ge/en/168022/?), [hr.ge](https://www.hr.ge/en/jobs/industry/dasveneba-da-mogzauroba?in=%5B%2220%22%5D&os=false&w=false&ef=null&et=null&we=false&ee=false&pg=3) |
| **ss.ge / myhome.ge** | Substitute (property listings) | About 29,244 commercial for-rent ads in Tbilisi (ss.ge); 30,546 commercial rent listings (myhome.ge, all of Georgia) | Free and paid listings | [ss.ge](https://home.ss.ge/en/real-estate/l/Commercial-Real-Estate/For-Rent?cityIdList=95&page=361), [myhome.ge](https://www.myhome.ge/en/real-estate/rent/commercial-area/) |
| **Instagram / phone / WhatsApp** | Substitute | How most restaurants take bookings and promote events today | Free | [Reddit snippet](https://www.reddit.com/r/tbilisi/comments/1wgaajq/whats_up_with_restaurant_reservations_in_tbilisi/) |

**Market size:** Tripadvisor lists **2,562 restaurants in Tbilisi**, with 78,737 reviews ([source](https://www.tripadvisor.com/Restaurants-g294195-Tbilisi.html)). This is a rough count of venues, not an official one, and it includes chains. Geostat puts Georgia's hotel and restaurant turnover at **3,988.7 million GEL in 2025**, up from 3,442.0 million in 2024 ([Geostat](https://www.geostat.ge/en/modules/categories/391/hotels-and-restaurants305)). The number of independent restaurants in Tbilisi is still unknown. Geostat's business register is the place to check.

## 2. Price range (what a restaurant pays per month for comparable software)

| Comparable item | Lowest | Median | Highest |
|---|---|---|---|
| QR menu | 0 GEL (Wox, QRMENUS Free) | 39 GEL | 79 GEL (QRMENUS Business) |
| Loyalty | 24 GEL (Wox Starter) | 39 GEL | 59 GEL (Wox Unlimited) |
| POS + QR | 30 GEL (SQR, from) | 149 GEL (Wox Starter) | 349 GEL (Wox Enterprise) |
| QR payment | 0 GEL terminal + ~2.5% per transaction (Keepz, as one user reports) | — | — |

**What this means for your 100 GEL entry tier:** a restaurant can already buy Wox Loyalty (39 GEL) plus a free QR menu, or QRMENUS Business (79 GEL), for less than 100 GEL. So 100 GEL has to buy something these don't offer, which is the payment-to-review-to-profile loop.

## 3. Positioning map

The two axes are how much of the guest journey a product covers (discovery → booking → ordering → **payment** → review → **repeat visit**), and who it serves (the restaurant's operations, or the diner).

```
                     DINER-FACING
                          │
   Tripadvisor ●          │          ● Rezto (book + pre-order)
   Google Maps ●          │          ● Javshani (premium booking)
   (discover + review)    │
 ─────────────────────────┼───────────────────────────────────
  Covers one step         │                  Covers many steps
                          │
   QRMENUS ●  Keepz ●     │     ● SQR (menu + order + POS)
   (menu)     (payment)   │     ● Wox (POS + menu + loyalty)
                          │
                   RESTAURANT OPERATIONS
```

Nobody sits in the top-right corner: a product the diner uses that runs all the way from paying the bill to a verified review and back to a repeat visit.

## 4. What their customers complain about

Public reviews of these local tools are scarce. Every theme below is **thin** (fewer than three reviews) and needs confirming with real restaurant owners and diners.

1. **Booking in Tbilisi is hard (diner side, thin).** *"I'm honestly struggling to understand how you're supposed to book a restaurant here. Online reservations are almost nonexistent (apart from rezto…"* ([Reddit, r/tbilisi](https://www.reddit.com/r/tbilisi/comments/1wgaajq/whats_up_with_restaurant_reservations_in_tbilisi/), search snippet only).
2. **Payment accounts blocked without explanation (Keepz, thin: 2 reviews).** *"They blocked my account twice for no reason!!!"* ([Play](https://play.google.com/store/apps/details?id=com.tipapp&reviewId=c93a17b5-c597-4a73-9ea0-ddbeee76c593)). A second review (in Georgian) reports a sudden block, gives no reason, and calls the 2.5% commission "unfair and expensive" ([Play](https://play.google.com/store/apps/details?id=com.tipapp&reviewId=dc121544-ccaf-471e-b104-1d6fbbb5fee3)).
3. **Registration friction (Keepz, thin: 1 review).** *"forcing registration with mandatory IBAN. Your app doesn't support my bank, and I can't register."* ([Play](https://play.google.com/store/apps/details?id=com.tipapp&reviewId=d91d3999-e7f9-4880-a71d-9b45dba79bfe)).
4. **Review sites accept unverified reviews (general, not Tbilisi-specific).** A restaurant owner on Google's own help forum asks for proof of purchase: *"If Google and Yelp had something in place where the person wanting to post a review HAD to take a photo of their receipt to prove they were actually in the restaurant then things like this wouldn't happen."* ([Google Business forum](https://support.google.com/business/thread/414288482/fake-reviews-dragging-down-business)). This is direct evidence of demand for review-on-order, but it doesn't come from Georgia.

## 5. The gap

**The parts are all available in Tbilisi, but nobody connects them.**

- Payment in the browser with no app install is **already solved and licensed** (Keepz). Building your own payments would be fighting a solved problem. Partner with Keepz, or with a bank, instead.
- Loyalty for independent venues **already exists and is cheap** (Wox, 24–59 GEL). "Loyalty without developing" is not a gap on its own.
- Online booking **is still thin.** Rezto has about 126 partners and Javshani 26, out of roughly 2,562 restaurants on Tripadvisor. Most bookings still go through phone, Instagram or WhatsApp.
- **Nobody ties the payment to the review and the guest profile.** SQR explicitly says *"Can guests pay from their phone? No."* Wox Loyalty is a stamp card a waiter stamps by hand, not linked to what the guest paid for. Tripadvisor and Google reviews are unverified. No one offers dish-level reviews that only come from a real payment.

**So the gap you can own:** one QR code on the table → pay (through Keepz or a bank) → automatic dish-level review + guest record + loyalty points, with no app and no stamping by hand. Sell it as a layer that works alongside the POS a restaurant already has (Wox, SQR, others), not as a replacement for it. **Evidence strength:** the "nobody connects them" part comes from the vendors' own pages and is strong. Restaurant demand for it is not proven yet; that's for `/founder-consumer`.

**Your B2B hook is weak where incumbents are big.** Property listings face ss.ge and myhome.ge, with tens of thousands of listings. Jobs face jobs.ge and hr.ge, which are full of HoReCa vacancies. A HoReCa-only niche can still attract owners (it's filtered and relevant), but don't expect listings to win on volume. A supplier directory has no clear local incumbent in this research and may be the strongest B2B hook. That's a lead to check, not a confirmed finding.

## 6. The threat: who could copy this fastest

1. **Wox.** It already has POS, QR menu and loyalty, and the restaurant relationships. Adding "pay at table via Keepz → review" is a short step for it. This is the main threat.
2. **Keepz.** It owns the payment and already offers tipping. Adding a review prompt and a guest history after payment is a small feature for it.
3. **Bank of Georgia / TBC.** They have the diners (Bank of Georgia reports more than 1.8 million digital monthly users, per [Omno](https://omno.com/payment-methods/keepz/)) and the merchant terminals. If either bank adds receipt-based reviews and loyalty to its app, it reaches every diner on day one.
4. **Rezto.** It has the diner-side booking app and restaurant partners, and could add payment and reviews.

**Defence:** move faster into a single neighbourhood, own the dish-level review data and the diner-facing brand, and integrate with Wox, SQR and Keepz instead of competing with them. Consider a partnership with Keepz from day one.

## Board conditions this step answers

- [x] Competitor map: who already does booking, QR payment, loyalty and reviews in Tbilisi, and whether the wedge is taken. **Answer:** the parts exist; the connected loop doesn't.
- [~] Count independent restaurants in Tbilisi. **Partly answered:** 2,562 restaurants on Tripadvisor (includes chains); confirm with Geostat.
- [~] Payment processing and licensing. **Partly answered:** Keepz is licensed by the National Bank of Georgia (open banking provider since July 2024, payment system operator since December 2025). Partnering avoids building payments yourself. Fees still need a quote (one user reports 2.5%).
- [ ] What stops a copycat in month six. **Open.** Wox and Keepz are each one feature away.
