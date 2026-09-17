# Invoice Pulse

**Get paid without the awkward chase.**

A private, browser-based invoice aging and reminder desk for freelancers and solo operators. No account. No monthly fee. No data leaving your machine.

Open the app: [app.html](./app.html) · Landing: [index.html](./index.html)

## Why this exists

Accounting tools create invoices. They do not collect them.

- 85% of freelancers get paid late at least once (Freelancers Union / Plutio 2025)
- 29% of freelance invoices are paid at least a day late (Bonsai)
- The average freelancer is owed about $6,000 at any given time (Freelancers Union)
- 42% have missed a personal bill because a client paid late

Invoice Pulse is the chase layer you run on top of Wave, FreshBooks, a PDF, or a Google Doc. Keep your current invoicing tool. Use this to age balances, generate the next message, drop a calendar hold, apply late-fee math, and print a demand letter when an invoice hits 30 days.

## What it does

- Client and invoice tracker stored in `localStorage`
- Aging dashboard: current · 1–7 · 8–14 · 15–30 · 30+
- Reminder sequences for day −3, 0, +7, +14, +30
- One-click copy + `mailto:` plus `.ics` calendar reminders
- Late-fee calculator (default 1.5%/month)
- Printable invoice and formal demand letter
- JSON export / import so you can back up or move machines

## Who it is for

Freelancers, consultants, photographers, and small operators who already send invoices and still wait two to six weeks to get paid.

## Who it is not for

Teams that need full accounting, payroll, or automatic card charging. Use FreshBooks or Bonsai for that.

## Two ways this makes monthly income

### 1. Sell the toolkit — $29 once

List on [Gumroad](https://gumroad.com) or [Lemon Squeezy](https://lemonsqueezy.com).

- Unlimited clients and invoices
- 5-step reminder sequences
- Calendar reminders, late-fee math, printable invoice, demand letter
- Works offline; data stays in the browser
- Founding price for the first 100 buyers; later list $49

Guarantee you can offer: if one overdue invoice does not get paid after the buyer runs the sequence, refund them. One recovered $1,200 invoice is 41× the price.

Host the public demo on GitHub Pages. Sell the unbranded build as the download.

### 2. Sell Payment Desk — $297 / $497 / $797

Do not wait for toolkit sales. Use the app as the delivery system for a done-for-you recovery service. Full offer, scripts, and guarantees: [OFFER.md](./OFFER.md).

Three retainers at $497/mo is about $1,500/month. That is the faster path to first dollars.

Launch channels and a 14-day first-customers plan: [LAUNCH.md](./LAUNCH.md).

## Pricing vs the suites

| Option | What you pay | What you get |
| --- | --- | --- |
| Wave / Zoho Invoice | $0 | Invoicing. Weak or no chase. |
| Payment Hunter / Invoice Ninja Pro / FreshBooks Lite | $9–19/mo | Reminders tied to their suite |
| Bonsai | ~$25/mo | Proposals + contracts + invoices |
| **Invoice Pulse toolkit** | **$29 once** | Chase layer on top of whatever you already use |

$29 is cheaper than two months of the subscription they already resent.

## Run it locally

No build step.

```bash
git clone https://github.com/evenjay42014-stack/invoice-pulse.git
cd invoice-pulse
# open index.html or app.html in a browser
```

Or enable GitHub Pages on this repo (Settings → Pages → Deploy from main / root).

## Privacy

Everything lives in the browser (`localStorage`). There is no server and no account. Export JSON to your machine if you want a backup. Clearing site data deletes the desk unless you exported first.

## Disclaimer

Templates are operational tools, not legal advice. Late-fee enforceability depends on a prior written agreement and local law. Confirm rates against your jurisdiction before sending a demand letter.
