# The Studio Workflow

**Practical automation for small business — booking, follow-ups, invoices, reviews.**

We help small businesses stop losing time (and jobs) to repetitive work. Two ways in:

1. **DIY automation kits** — teachable PDFs and Excel workbooks you buy once and use yourself.
2. **Done-for-you automation** — we build and run the automation for local shops: missed calls answered, booking, follow-ups, invoices, reviews, and reporting.

🌐 Website: https://www.thestudioworkflow.com
🛍️ Etsy shop: https://www.etsy.com/shop/TheStudioWorkflow
📘 Facebook: https://www.facebook.com/profile.php?id=61596683811750
📸 Instagram: [@thestudioworkflow](https://www.instagram.com/thestudioworkflow)
📍 Virginia Beach, VA

---

## What we do

A missed call is a lost job. What a shop actually needs is the lead captured, the job booked or queued, and the owner told about it in minutes.

So that's what we built: the AI answers, pulls out name, service, and urgency, captures the lead, and texts the owner right away — with a transcript they can check.

The phone call is the easy part. Knowing what happens after it — that's the product.

### The 8 automation areas

1. **Calls & messages** — missed calls answered, texts replied to
2. **Booking & scheduling** — jobs booked or queued, confirmations sent
3. **Lead follow-up** — no lead left sitting in a voicemail
4. **Quotes, invoices & payments** — quotes out, invoices paid, less chasing
5. **Reviews & reputation** — review asks after the job, handled simply
6. **Customer intake & forms** — the right details captured first time
7. **Admin & data entry** — the repetitive typing, done for you
8. **Reporting** — a Revenue Ledger: recovered jobs in the shop's own numbers, before and after

## Done-for-you service

| Plan | Monthly | Setup | What it covers |
| --- | --- | --- | --- |
| **Tune-Up** | $299/mo | $499 | 1 automation |
| **Streamline** | $999/mo | $1,999 | Up to 3 connected automations |
| **Autopilot** | $3,499/mo | $4,999 | Up to 6 automations, AI call answering included if wanted |
| **Custom** | Quoted | Quoted | Built around the shop |

Start here: https://www.thestudioworkflow.com/services

## DIY kits (Etsy)

Digital downloads, sold and fulfilled on Etsy. Every buy button on our site links to its Etsy listing.

- **Small Business AI Automation Blueprint** — $39.95 — Find what to automate, prove it's worth it, and turn the winner into a build-ready plan.
- **10 Automations Every Etsy Shop Needs** — $19.95
- **Etsy SEO Title & Tag Builder Kit** — $14.95
- **60 Quick-Reply Templates for Etsy Sellers** — $9.95
- **100 Review Response Swipe Kit for Etsy Sellers** — $7.95
- **Etsy Shop Audit & Fix-It Kit** — $19.95
- **Etsy Holiday Sales Sprint Kit** — $14.95
- **Etsy Pricing & Profit Calculator** — $14.95
- **The Etsy Listing Image System** — $19.95

Bundles:

- **Etsy Seller Essentials** — $39.95 — Shop Audit, SEO Title & Tag Builder, Listing Image System.
- **The Complete Etsy Seller System** — $79.95 — All 8 Etsy seller kits.

## Code in this org

This org holds small, teachable code snippets — proof we actually build this stuff, without giving away the production system.

- Snippets are **teaching examples, not the production Engine**. They show the pattern, in the smallest form that still makes sense.
- No secrets, no API keys, no client data, no real phone numbers. Anything that needs a credential uses an environment variable.
- Each snippet links back to https://www.thestudioworkflow.com and, where it fits, to the matching Etsy kit.

The production Engine itself stays private. It is a live, multi-tenant voice + SMS system (Twilio, ElevenLabs) that answers calls, captures leads, and alerts the owner.

### Snippets so far

- **Missed-call text-back (Python, Twilio)** — a shop misses a call; the customer gets a text in seconds: "Sorry we missed you — what do you need?"
- **Day-before confirmation text** — a scheduled reminder with name, date, and job placeholders. Confirmation texts cut no-shows.
- **Lead-capture API pattern** — POST a lead (name, phone, service, source) to one endpoint, store it, alert the owner. The shape our Services form already uses.

## How we build

- **The phone call is the easy part.** The product is what happens after it: lead captured, job booked or queued, owner told in minutes.
- **Learning is manual-first.** We read transcripts and apply changes by hand, so nothing the AI heard becomes a fact without a person approving it.
- **Guardrails are the product.** Hard caps on call length and turns, per-tenant daily budgets, alerts before the limit — so a caller who realises they're talking to an AI can't chat endlessly and run up a bill.
- **Sales calls get a polite no.** If someone calls trying to sell *to* the business, the agent thanks them, says we're not interested, and ends the call. A caller buying the shop's service is a lead — direction matters.
- **Before / after, in the shop's own numbers.** We don't defend a monthly price; we show recovered jobs in a Revenue Ledger.

## Who this is for

- Local owner-operator shops — plumbers, HVAC, salons, and other small trades and services — where a missed call is a lost booking and a no-show is an empty chair.
- Etsy sellers who want their shop to run itself a little more, and their making time back.

## Contact

- Website: https://www.thestudioworkflow.com
- Public email: hello@thestudioworkflow.com
- Services / start a conversation: https://www.thestudioworkflow.com/services/start
