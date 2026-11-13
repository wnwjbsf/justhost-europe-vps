# Cheap Europe VPS: Is JustHost's $1.99 Plan Enough, Which Location Should You Pick, and Does the Price Hold on Renewal? (Full Plan Table)

JustHost's tariff page lists a VPS at **$1.99/month**: 1 core, 512 MB RAM, 5 GB NVMe, and a 10 Mbps port. That hardware will run a static site or a tiny VPN endpoint; it won't run a WordPress install with a plugin stack.

For most people searching for a cheap Europe VPS, the plan worth pricing is **New Star at $3.05/month on a 12-month prepay** — 1 core, 1 GB RAM, 10 GB NVMe, 100 Mbps fair-share port. If you need 2 GB for a real site, Double Star is **$5.67/month** on the same term.

What follows: every plan on the tariff page, what the port numbers actually mean for you, which locations are documented, and one question about the operating company that matters more than the data center map.

> **Quick pick:** New Star — 1 GB RAM, 10 GB NVMe, 100 Mbps fair-share port, **$3.05/month when you pay for 12 months**. Good for a small WordPress site, a WireGuard endpoint, or a staging box. 👉 [Check New Star's current price](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)

## All JustHost VPS plans

Prices below are what the tariff page shows today. The monthly column is the shorter-term rate; the prepay column is the per-month rate when you pay 12 months upfront.

| Plan | vCPU / RAM / NVMe | Port (fair-share) | Monthly | 12-month prepay | Order |
| --- | --- | --- | --- | --- | --- |
| VPS Promo | 1 / 512 MB / 5 GB | 10 Mbps (~4+ TB) | $1.99 | — | [Order Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 / 1 GB / 10 GB | 100 Mbps (~31+ TB) | $3.81 | $3.05 | [Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Sirius | 1 / 1 GB / 20 GB | 300 Mbps (~93+ TB) | $4.85 | $3.88 | [Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 / 2 GB / 30 GB | 300 Mbps (~93+ TB) | $6.92 | $5.53 | [Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Double Star | 2 / 2 GB / 20 GB | 200 Mbps (~62+ TB) | $7.08 | $5.67 | [Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Alpha Centauri | 2 / 2 GB / 40 GB | 400 Mbps (~124+ TB) | $8.99 | $7.19 | [Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Bright Star | 4 / 4 GB / 30 GB | 300 Mbps (~93+ TB) | $9.80 | $7.84 | [Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Vega | 2 / 4 GB / 80 GB | 500 Mbps (~155+ TB) | $13.44 | $10.75 | [Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 / 4 GB / 120 GB | 750 Mbps (~232+ TB) | $18.30 | $14.64 | [Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

Two things the table hides. The Promo card's annual figure wasn't rendered on the listing I checked, so I've left it blank rather than guess. And New Star, Double Star and Bright Star carry a **three-month minimum order** — the annual discount only applies on terms of three months or longer.

There's a second price list on the site's main VPS page, badged as special offers, and it prices the same plan names lower: Sirius Special at $2.81, Arcturus Special at $4.01, Vega Special at $7.79, Yildun Special (4 cores / 8 GB / 200 GB) at $16.20, Betelgeuse Special (6 / 12 GB / 400 GB) at $26.40, Altair Special (8 / 24 GB / 600 GB) at $47.40, each with 20% off on annual prepay. Those are worth asking about directly, because the gap between $4.85 for Sirius on the tariff page and $2.81 for Sirius Special is not a rounding difference. If the special isn't available for your term, the tariff page price is what you'll pay.

A configurator also sits on the VPS page for custom builds. Its entry points, at 12-month rates: HDD VPS Start at $2.60 (1 core / 512 MB / 5 GB HDD), SSD VPS Start+ at $3.12, NVMe VPS Start++ at $3.38. IPv6-only configurations start at $1.60. All of these are KVM with full root access.

## The $1.99 plan has a 10 Mbps port, and that's the catch

JustHost labels its ports "unmetered (fair-share)" and prints the monthly equivalent next to each one. Promo's 10 Mbps works out to roughly 4 TB a month. New Star's 100 Mbps is about 31 TB. Capella's 750 Mbps is around 232 TB.

The traffic number is not your limit. The port speed is. A 10 Mbps port caps you near 1.2 MB/s on a single transfer, which is fine for a DNS resolver or a monitoring node and painful for anything serving images or video to more than a couple of people at once. Paying $1.06 more per month for New Star moves you from 10 Mbps to 100 Mbps. That's the best value step on the whole page.

The same asterisk shows up at Contabo, where "Unlimited Traffic" links to a fair-use policy and the real differentiator is the 200 Mbit/s to 1 Gbit/s port. Any host selling unmetered bandwidth is selling a port rate with a policy attached. Read the port column first.

RAM deserves its own warning. 512 MB will not hold a modern WordPress install plus MySQL; you'll be into swap the moment a plugin update runs. 1 GB is workable for a single low-traffic site. 2 GB is where you stop thinking about it.

## Monthly versus annual: where the 20% actually goes

Every JustHost plan shows two prices, and the gap is the annual prepay discount. Running the numbers on the plans people actually buy:

- New Star: $3.81 monthly versus $3.05 on 12 months. $45.72 for a year versus $36.60. You save **$9.12**.
- Double Star: $84.96 versus $68.04. You save **$16.92**.
- Vega: $161.28 versus $129.00. You save **$32.28**.

That's a prepay discount, not a first-term teaser with a jump attached — but only for the term you bought. JustHost's tariff page doesn't publish a renewal rate, so the honest answer to "will it cost more next year" is: the page doesn't say. Ask support for a written renewal quote before you commit to an annual term, and keep the reply.

This is where a provider being explicit helps. VerticHost prints "Renewal at the same price" on all four of its plans. That sentence exists as a marketing feature precisely because the opposite is common. Treat a missing renewal line as an open question, not as a promise.

KVM virtualization, NVMe storage and one-click OS reinstalls are standard across the range. DDoS protection against the main attack types is included on all plans, per JustHost's own VPS page.

👉 [Compare all JustHost VPS tariffs and port speeds on one page](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Which countries are the servers in?

The clearest public evidence comes from third-party reviews rather than the tariff page. Reviewers have documented London (two data centers, LON1 and LON2) and Paris (PAR1, with a second French location). Those reviews also describe one-click switching between data centers and IP switching from the control panel, which is unusual at this price band and genuinely useful if you're testing geo-specific services.

Two caveats worth knowing before you order.

The full country list isn't on the pricing page, so confirm the specific location at checkout rather than assuming it from a blog post.

And a data center in a country doesn't guarantee an IP registered there. A published test of the London LON2 node found a **US-native IP address**, not a UK one — which unlocked UK ChatGPT and Claude but would fail any check expecting a British IP. If your project depends on IP geolocation, ask support which IP range you'll get before paying.

Payment methods listed across those reviews include credit cards, PayPal, Alipay, UnionPay and several cryptocurrencies. Billing is shown in US dollars.

## A server in Europe is not the same as a European company

This is the part of the "cheap Europe VPS" decision that most comparison pages skip. Hetzner's own FAQ puts it plainly: *"If a provider is headquartered in the USA, it remains subject to the US Cloud Act—even if the data is stored in Europe. In such cases, US authorities can still request access to your data."* Their recommended check is headquarters and corporate ownership, not the data center address.

Applying that test: JustHost's pricing pages don't state the operating company's legal jurisdiction or where billing is handled. For a personal project that's a footnote. For client data, an EU-facing SaaS, or anything with GDPR obligations attached, it's the first question to send support — legal entity name, registration country, and where the company is ultimately owned. Get it in writing. If the answer doesn't fit your compliance posture, no price on this page fixes that.

👉 [Open JustHost's VPS page and check the location list at checkout](https://justhost.asia/?ref=196392)

## How JustHost compares on configuration and policy

No prices for Hetzner and Contabo here — their published figures shift with billing term and promotion, and quoting a number I can't confirm would be worse than leaving it out. Configuration and contract terms are the useful comparison anyway.

| Provider | Typical entry config | Bandwidth model | Billing and contract | Worth knowing |
| --- | --- | --- | --- | --- |
| JustHost | 1 core / 1 GB / 10 GB NVMe | Unmetered port at 100 Mbps fair-share | 3-month minimum on some plans; 20% off at 12 months | KVM, DDoS protection, one-click location and IP switching |
| Hetzner (DE) | CPX02: 1 vCPU / 1 GB / 20 GB, 0.5 TB traffic | Traffic allowance per plan | Hourly billing, monthly price cap, no minimum term | GDPR-compliant, DIN ISO/IEC 27001:2022 certified, locations in Germany, Finland plus US and Singapore |
| Contabo (DE) | 4 vCPU / 8 GB / 100 GB SSD, 200 Mbit/s port | "Unlimited" under a fair-use policy | Promotional pricing for the first 24 months | Ports from 200 Mbit/s to 1 Gbit/s, DDoS protection, snapshots |
| VerticHost | BASIC: 1 vCore / 2 GB / 20 GB, €9/month | Unmetered | Renewal at the same price, no contract, 7-day money back | 15 EU locations, 99.9% uptime, KVM. Its headline says NVMe while the plan list says SSD, so confirm storage type |

Read the table by use case. Hetzner suits anyone who needs hourly billing and a documented certification trail. Contabo suits people who want a lot of cores and RAM per euro and can live with a promotional first term. VerticHost suits anyone who wants a fixed, published renewal price and a refund window in writing. JustHost sits at the low end on price, with the smallest entry configurations in this group and the widest port range.

Two comparison habits worth keeping. First, annual prepay versus monthly changes the effective price by around 20% almost everywhere, so compare like with like. Second, tax basis differs: some European price aggregators quote in GBP with VAT included, which can add a fifth to a headline number that looked cheaper.

## Which plan for which job

**A single low-traffic WordPress site, a VPN endpoint, or a bot.** New Star at $3.05 on annual prepay. 1 GB RAM is the floor for WordPress; 10 GB NVMe is tight but workable with a CDN in front.

**Two or three sites, or a site with WooCommerce.** Double Star at $5.67. The 2 GB RAM matters more than the extra core.

**Anything with a database that grows.** Arcturus at $5.53 gives you 2 GB RAM and 30 GB NVMe on a 300 Mbps port for less than Double Star. It's the odd good deal in the middle of the range — one core, more disk, faster port.

**Docker, CI runners, or a mail server.** Vega at $10.75, or Capella at $14.64 if you want 4 cores and 120 GB. Below 4 GB RAM you'll spend more time tuning than building.

**A static page or a monitoring probe.** Promo at $1.99 is genuinely fine, and the 10 Mbps port won't matter. Don't put a database on it.

If your requirement is a guaranteed European corporate structure rather than a cheap European IP, none of the JustHost tiers answer that question until support confirms the legal entity. That's a different purchase.

## Before you pay

- Confirm the **renewal price** in writing, and whether the $3.05 rate survives past month 12.
- Confirm the **refund or cancellation terms**. I found no published money-back window on the pages I checked; don't assume one exists because a competitor offers seven days.
- Confirm the **data center country** for the specific plan you're ordering, not the general list.
- Confirm whether the **IP is registered in that country**, especially for UK or France.
- Check the **minimum term**. Three months applies to New Star, Double Star and Bright Star.
- Ask about the **special-offer pricing** shown on the main VPS page. It undercuts the tariff list on identical plan names.
- Check whether prices include **VAT** for your billing country, and that your card is charged in USD.

## The rule

A static page or a probe: Promo, $1.99, accept the 10 Mbps port. A real site: New Star, $3.05 on annual prepay, no reason to go lower. Anything running a database you care about: 2 GB RAM minimum, which means Arcturus or Double Star. And before any annual prepayment, get the renewal price and the company's registration country in an email you can keep.

👉 [Start with New Star at $3.05/month on a 12-month term](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)
