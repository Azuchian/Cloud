# $10K CAD in One Day — The "Fixed-Price AI Sprint" Playbook

**Bottom line:** Nothing legal turns $0 into $10,000 in 24 hours without someone choosing to pay you. So this plan isn't about hoping something goes viral. You **sell a high-value, fixed-price service the same day, and get paid up front.**
The math: **4 clients × $2,500 CAD**, or **2 × $5,000**. To close 4 you need roughly 40 real conversations, which means about 150–200 targeted messages. That volume is hard but possible in one long day.

Every tool used here is free: Claude, GitHub Pages, Google Sheets, Google Meet, Cal.com, Stripe Payment Links (no monthly fee; you pay a per-charge fee) or Interac e-Transfer (free at most Canadian banks).

---

## The offer (pick ONE and don't change it during the day)

**"I'll automate your most annoying weekly task in 72 hours, or you don't pay the balance."**

| Package | Price (CAD) | What they get |
|---|---|---|
| Sprint | **$2,500** | 1 workflow automated (e.g. lead intake → CRM → auto-reply, invoice chasing, quote generation, review requests), set up in *their* tools, plus a Loom walkthrough |
| Sprint+ | **$5,000** | 3 workflows + AI customer-reply assistant trained on their FAQs + 30 days of fixes |

**Payment:** 100% up front, or 60% today and 40% when delivered. *The money has to arrive today for this to count.*
**Guarantee:** if the workflow doesn't save them 5+ hours a month, you refund in full. This takes away their risk, and you'll close far more deals with it.

Why this works: you can actually deliver it using Claude, Zapier/Make free tiers, Google Apps Script, and n8n (free, self-hosted). Owners already spend $2,500+ a month on staff time for these tasks, and "fixed price, 72 hours, guaranteed" is easy to say yes to.

> Not technical? Swap the offer for something you *can* deliver at a similar ticket size: a 1-day website rebuild, a Google Business Profile + review system overhaul, a bookkeeping catch-up, a sales-script and CRM setup, or a done-for-you hiring post and screening. The playbook stays the same.

---

## Who to target (in this order)

1. **Your warm network first.** Former employers, clients, friends who own businesses, and LinkedIn connections. Close rates are 5–10× higher than cold.
2. **Local service businesses with obvious pain** and a typical job value above $2K: HVAC, plumbing, roofing, renovation, dental and physio clinics, real estate teams, mortgage brokers, law firms, property managers, auto shops.
3. **Signs a business is a good fit:** reviews that say "never called back"; no online booking; a "call for a quote" contact form; job postings for receptionists or admin staff.

Track every lead in `lead-tracker.csv`. Import it into Google Sheets.

---

## Hour-by-hour plan

| Time | Action | Target |
|---|---|---|
| 6:00–7:00 | Deploy `index.html` to GitHub Pages (Settings → Pages). Create 2 Stripe Payment Links ($2,500 and $5,000) and a Cal.com 15-min booking link. Paste them into the page. | Live in 60 min |
| 7:00–8:00 | Build a list of 100 warm and 100 local leads (Google Maps, LinkedIn, your contacts) in the tracker | 200 leads |
| 8:00–11:00 | **Warm outreach:** personal DM, text or call to every warm contact (scripts in `outreach-scripts.md`). Ask for the deal *or* a referral. | 100 messages |
| 9:00–17:00 | **Phone local businesses.** Owners pick up between 9 and 5. Calls convert far better than email. | 80+ dials |
| All day | 15-min discovery calls → close on the call → send payment link while still on the line | 15–40 calls |
| 12:00 | Post the public offer on LinkedIn, local Facebook business groups and r/smallbusiness (where rules allow): *"Taking 4 automation clients this week…"* | 3–5 posts |
| 17:00–20:00 | Follow up with everyone who said "maybe." Deadline: *"I'm only taking 4 at this price, and the spots close tonight."* (Only say this if it's true. Cap it and stick to the cap.) | Close |
| 20:00–22:00 | Kick off delivery for paid clients so they see progress tonight | Retention / referrals |

**Close on the call:** "Sounds like the quote follow-up is costing you about 6 hours a week. I can have it running by Friday for $2,500, with a full refund if it doesn't save you 5 hours a month. Want me to send the payment link now so I can start tonight?"

---

## Stacking smaller wins to fill a gap

If by 3 pm it looks like you'll fall short, add these. All are same-day, legal, and use free tools:

- **Referral bounty:** offer people in your network $500 for every client they send you who pays.
- **Productized mini-offer at $497:** "AI FAQ reply assistant for your website." Sell it to the businesses that said "too expensive."
- **Sell what you own:** list idle gear on Facebook Marketplace or Kijiji (cameras, bikes, tools, electronics). This is often good for $500–$2,000 the same day.

---

## What NOT to do (it's how people lose money chasing "$10K in a day")

- Gambling, sports betting, options or crypto "day trades." That's speculation, not income, and it's the fastest way to lose money.
- "Free money" schemes, reselling gift cards, accepting payments for strangers, or anyone who sends you a cheque and asks for money back. These are scams or money-mule fraud.
- Promising results you can't deliver. Offer the refund guarantee and honour it.
- Spamming. Personalise every message, follow each platform's rules, and comply with CASL (Canada's anti-spam law) for commercial email: identify yourself, include an unsubscribe option, and only email addresses that are publicly posted for business use without a "no solicitation" note, or people you have a relationship with.

**Tax:** this counts as self-employment income. Set aside about 25–30%. If your revenue goes over $30K in 4 quarters, you'll need to register for GST/HST.

---

## Files

- `index.html`: one-page sales site (deploy free on GitHub Pages)
- `outreach-scripts.md`: warm DM, cold call, voicemail, email and follow-up scripts
- `lead-tracker.csv`: import into Google Sheets
- `delivery-checklist.md`: how to deliver a Sprint in 72 hours
