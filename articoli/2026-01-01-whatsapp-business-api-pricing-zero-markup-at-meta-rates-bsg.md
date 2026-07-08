---
titolo: "WhatsApp Business API Pricing — Zero Markup at Meta Rates | BSG"
url: "https://bsg.world/whatsapp"
fonte: "BSG"
autore: null
data_articolo: "2026-01-01"
recuperato_il: "2026-07-08"
email:
  - "2026-07-06 — dist*ll daily digest <andrew@distll.ai>"
stato: "ok"
---

# WhatsApp Business API Pricing — Zero Markup at Meta Rates | BSG

# WhatsApp Business API

with zero markup —

pay Meta’s rates directly

        Run WhatsApp marketing, abandoned-cart recovery and order updates on the channel customers actually open — **~98%** open WhatsApp vs 20–30% for email. Win back the revenue sitting in your customer database — and with BSG’s WhatsApp Business API you pay **Meta’s rates directly, with zero markup**, while every message falls back to SMS, then voice, if it doesn’t land.

### We don’t just send WhatsApp messages.

We make sure they land.

        Every message goes WhatsApp-first, then automatically falls back to SMS — and to a voice call for high-value sends — so reminders, codes and offers actually arrive. You pay Meta’s price directly, with zero markup, and keep your own volume discounts.

WhatsApp open rate 

vs 20–30% on email

Abandoned carts recovered 

vs 4–10% on email

To deliver a financial 

or login code

Saved on 100k messages 

vs a marked-up provider

## WhatsApp marketing reaches the database that email and SMS can’t

### Why WhatsApp is the channel that gets opened

Most shoppers leave without buying, and email wins back only 4–10% of those carts. Order updates by SMS cost more and get ignored. Customers open WhatsApp about 98% of the time — email 20–30%. The money is sitting in your list; you’re just reaching it on the wrong channel.

## WhatsApp Business API use cases for teams that own the customer database

Pick your world — each one leads with the outcome you’re measured on.

**18–60%**of abandoned carts and save about

**€780/mo**on 100,000 messages — because you pay Meta’s prices directly, zero markup.

#### Abandoned-cart recovery

Cart abandoned → wait 30–60 min → “You left items in your cart” with a one-tap back-to-checkout button. No purchase after 24h? A follow-up with a discount code. Fails on WhatsApp? Auto-resent by SMS.

#### Promotional broadcasts

New drops, sales and launches to your opt-in list — each with a product image and a *Shop now* button. Segment by what people last bought or browsed so first-timers and repeat buyers get different copy.

#### Order updates

Confirmed, shipped, out for delivery, delivered — each with order details and a tap-to-track link, on the channel that actually gets opened.

#### Cash-on-delivery confirm

For COD orders, a *Confirm / Cancel / Switch to prepaid* message within minutes that writes back to your order system. High-value orders can add a voice call as a last-resort confirm.

**45–60%**of abandoned applications and lift enrolment conversion, while saving about

**€390/mo**on 50,000 messages.

#### Acquisition from the ad

A click-to-WhatsApp ad opens a free 72-hour window. Instant welcome — course overview, a testimonial image and an *Enrol now* button.

#### Automated nurture

Day 7: instructor profile and curriculum. Day 14: a last-chance early-bird offer — pre-approved templates delivered on time, every time.

#### Application status

Received → documents due → interview → offer, each with a portal link. The offer letter goes out as a PDF, with SMS fallback so a missed deadline never costs a place.

#### Win-back

Re-engage students who went quiet — “you’re 30% through, continue now” — with a *Resume* button.

**3×**more often than email or phone and deliver financial codes in

**2–3s**, saving about

**€1,465/mo**on 250,000 messages.

#### Policy renewals

Policy summary, renewal price and a *Renew now* button 30 days out, with reminders at 15 / 7 / 3 days. After payment, the policy document as a PDF. SMS fallback on every send.

#### Claims & lending

Status at every step with the claim reference; disbursement confirmations, instalment reminders and a *Pay now* link — plus an overdue notice if nothing lands.

#### Financial codes (add-on)

Login and transaction codes delivered as authentication messages in 2–3 seconds, with copy-code / one-tap autofill. Retry by SMS in ~30s, voice for high-value confirms. Sell it for reliability, not as the headline.

#### Reconcilable audit trail

A `client_message_ref` on every send plus full message history — the evidence trail that matters when a failed delivery carries a cost.

**30–60%**. With BSG your clients pay Meta directly and keep their own volume discounts — you win deals on price and earn on every integration.

#### Learn one API

One base URL, one login. The same payload covers bulk and single sends and mirrors Meta’s component model, so existing automation ports across with minimal change.

#### Build risk-free

Every account ships a `test_` key alongside the `live_` key — realistic responses with no sending or billing. Run full CI against the live API shape, then switch the key.

#### Onboard without rebuilding

Embedded Signup connects a client’s existing WhatsApp account — even one migrated from Twilio or Infobip — so tier, quality rating and approved templates carry over.

#### One platform, every channel

The same credentials reach WhatsApp, SMS, Viber, RCS, Email, OTP and voice — add a fallback or a voice step for a client with no second vendor.

## WhatsApp Business API integration — from abandoned cart to recovered revenue in four steps

#### Connect once, send everything

Authenticate once — one API key returns a JWT — and that single key runs WhatsApp, SMS and voice. Marketing broadcasts and transactional updates share the same auth and template payload. No separate builds, no second vendor.

#### Put cart recovery on autopilot

The reminder and the 24-hour discount follow-up run off one approved template, personalised per shopper — name, cart value, order number and a dynamic back-to-checkout button. You win back 18–60% of carts vs 4–10% on email.

#### Make sure the message lands

If WhatsApp doesn't deliver in time, BSG automatically resends over SMS on the same OneAPI; high-value and COD orders can add a voice-call confirmation. That pushes reach past what email and SMS manage alone.

#### Prove compliance and ROI

BSG keeps your opt-out list in sync, de-duplicates retries with a `client_message_ref`, and returns delivery state (sent / delivered / read / failed) by API or signed webhook — so you can measure recovered revenue.

## Why BSG is the WhatsApp Business API provider, not a marked-up reseller

We're a **Meta Tech Provider**. Clients pay Meta directly for messages; we charge a flat monthly fee — no markup on traffic.

#### No markup on messages

You pay Meta's list price; we add only a flat fee. Most competitors resell Meta traffic with a 30–60% markup.

#### Keep volume discounts

No reseller sits in between, so there are no surprise overage charges on your own Meta discounts.

#### Automatic SMS fallback

If a WhatsApp message fails, we resend by SMS. WhatsApp-only providers don't.

#### Voice fallback

For financial codes or expensive orders, follow up with a phone call — rare among WhatsApp-only providers.

#### Live in 30–40 minutes

Clear pricing, no minimum contract, and a verified green-tick account as standard.

#### One API, every channel

WhatsApp, SMS, Viber, RCS, Email, OTP and voice on a single OneAPI — add a channel without a new integration.

## Ease of Development

```
const axios = require('axios');
axios.post(
  'https://one-api.bsg.world/api/campaigns/whatsapp/send',
  {
    phones: [
      { number: '380661231231', reference_id: 'f2d37bf77f6242daa83f23b0cc84b627' },
    ],
    message: 'This is a sample message',
  },
  {
    headers: {
      Authorization: 'Bearer {your_api_key}',
      'Content-Type': 'application/json',
    },
  }
)
.then(res => console.log('Sent:', res.data))
.catch(err => console.error('Error:', err.response?.data || err.message));
```
### Code it your way

Integrate your customers’ favorite channels and build the experiences they expect — with full control over logic, flow, and delivery.

Explore Docs## WhatsApp Business API pricing

You pay Meta for your messages and a flat monthly fee to us — zero markup on traffic. **No platform fee for the first 3 months.** Savings shown vs a typical reseller markup at a 30% marketing mix.

### Free

### Starter

### Growth

### Scale

### Custom

## WhatsApp Business API FAQ

### What can I send over WhatsApp today?

Outbound marketing, utility and authentication templates are live — promotional broadcasts, order updates and one-time passwords, all from a single account. Today the channel is outbound only; two-way replies, a shared inbox and chatbots are on the roadmap.

### What happens if a WhatsApp message isn’t delivered?

Every send falls back automatically — to SMS if WhatsApp fails, and to a voice call for high-value messages — so reminders, codes and offers still reach the customer.

### How does OTP / authentication work?

The full one-time-password lifecycle — issue, verify, resend and cancel — runs through a single endpoint, with no separate services to stitch together.

### How quickly can I get set up?

Onboarding uses Embedded Signup with a verified green-tick account, and SDKs are available in six languages, so you can integrate fast in your preferred stack.

### Can I track delivery and report on results?

Yes — delivery webhooks and full message history are available, so you can monitor delivery status and pull reporting on every send.

### What should I plan around — timing, volume and restrictions?

Template approval takes 24–48h for utility/auth and 3–7 days for marketing, so plan campaigns accordingly. WhatsApp generally pays off from ~5,000 messages a month. Note: US marketing campaigns are currently paused by Meta, and healthcare and brokerage are out of scope.

## Start free. Pay Meta’s price. Keep the markup.

Get a verified WhatsApp account live in 30–40 minutes — you pay zero platform fee for the first 3 months — only Meta’s rates.
