# evoxt promo code: EVOXT595 vs AFF1129-hostspot vs BHW595 — which one works, which plans can't use them, and what the 40% recurring discount actually saves (full plan table)

Three codes circulate for Evoxt: **EVOXT595**, **AFF1129-hostspot** and **BHW595**. Each takes 40% off, each is recurring rather than first-month-only, and each applies to VM-1 and above. On VM-1 that turns $5.99/month into roughly **$3.59/month**, on every invoice, with no 24-month prepay required. What follows covers the full plan list with the discounted price next to each one, the plans where a code does nothing at all, where the checkout field hides, and the arithmetic on what a recurring 40% is worth next to a host that discounts the first term and doubles the price at renewal.

## If you only want the short answer

> Most readers end up on **VM-1**: 1 vCore, 2 GB RAM, 20 GB SSD, 1 TB transfer, **$5.99 down to about $3.59/month** with EVOXT595, and the discount repeats every billing cycle. 👉 [Open Evoxt's deploy page and enter EVOXT595 at checkout](https://bit.ly/EvoXt)
>
> Running a Discord bot, a VPN endpoint or one small page on 512 MB? Take **VM-0.5 at $2.99** and skip the coupon hunt. Percentage codes don't apply to it.

## Every Evoxt plan, with and without the code

These are the plans on Evoxt's pricing page, at list price and at 40% off. Prices are USD, monthly billing, every plan on a 1 Gbps port with weekly offsite backup included.

| Plan | vCPU / RAM / SSD | Transfer | List price | With EVOXT595 | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 / 512 MB / 5 GB | 500 GB | $2.99 | not eligible | [Deploy VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 / 1 GB / 10 GB | 750 GB | $4.99 | not eligible | [Deploy VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 / 2 GB / 20 GB | 1,000 GB | $5.99 | **about $3.59** | [Deploy VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 / 2 GB / 20 GB | 1,500 GB | $6.95 | about $4.17 | [Deploy VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 / 4 GB / 30 GB | 2,000 GB | $11.99 | about $7.19 | [Deploy VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 / 4 GB / 30 GB | 3,000 GB | $14.99 | about $8.99 | [Deploy VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 / 8 GB / 60 GB | 4,000 GB | $23.99 | about $14.39 | [Deploy VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 / 8 GB / 60 GB | 5,000 GB | $29.99 | about $17.99 | [Deploy VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 / 16 GB / 80 GB | 6,000 GB | $47.99 | about $28.79 | [Deploy VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 / 16 GB / 80 GB | 8,000 GB | $60.95 | about $36.57 | [Deploy VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 / 32 GB / 100 GB | 10 TB | $95.99 | about $57.59 | [Deploy VM-16](https://bit.ly/EvoXt) |

One thing the table hides: Evoxt sells the same plans on three network tiers (Standard, Premium, Premium Plus). The monthly price doesn't change between them, the transfer allowance does. On the pricing page, the Premium table lists VM-1 with 500 GB instead of 1,000 GB. If you're picking Hong Kong to get CN2 routing into mainland China, budget for roughly half the bandwidth of the Standard tier.

## The three codes side by side

| Code | Discount | Works on | Type | Notes |
| --- | --- | --- | --- | --- |
| **EVOXT595** | 40% | VM-1 and above | Recurring | Most widely listed of the three |
| **AFF1129-hostspot** | 40% | VM-1 and above | Recurring | Same terms, different referring community |
| **BHW595** | 40% | VM-1 and above | Recurring | Also associated with a $5.95 entry-plan mention in some listings |

None of the three appears on an Evoxt page. Evoxt doesn't run a public coupon page, so these circulate through hosting forums and affiliate write-ups that list them as working. That's a weaker claim than "officially confirmed", and you should treat it that way. The practical part is that the checkout field tells you the truth before you pay: enter a code, hit Apply, and either the total drops by 40% or it doesn't. Testing costs nothing and takes ten seconds.

There's a competing claim worth dismissing. One coupon aggregator advertises a sitewide 40% that covers all hosting plans and attaches an expiry date to it, without publishing any actual code string. Every source that names a code restricts it to VM-1 and above. The narrower, more specific version is the one to plan around.

## Why "recurring" is the whole point

Evoxt bills VM-1 at $5.99 monthly, which is $71.88 a year. At the discounted rate it's $3.59, or $43.08 a year. Stretch that over three years and the difference is $86.40, and none of it requires paying for 24 months up front.

Hostinger's entry KVM plan is the usual comparison. It runs $4.99/month, but that rate depends on a 24-month commitment, and the plan renews at $9.99/month after it. Two years at the promo rate is $119.76; the following twelve months cost $119.88; three years lands near $239.64. Evoxt on plain monthly billing at the discounted rate comes to about $129.24 over the same period. The hardware isn't identical, so read that as the shape of the price curve rather than a spec-for-spec benchmark. The curve is the part that matters, because a first-term discount with a doubled renewal is how budget hosting normally works. A code that keeps applying after renewal is rare enough to be the main reason to pick Evoxt over a competitor with a lower headline number.

## Applying the code: steps, and the three places it goes wrong

1. Open the deploy page and pick your plan. VM-1 or higher if you want the 40%.
2. Choose the region and operating system. Linux images, Windows RDP and one-click app installs are all offered at this step.
3. Pick a billing cycle. Monthly is fine. The discount doesn't depend on committing to a year.
4. Continue to checkout.
5. Find the field labelled **"Promotional Code"**. Not "Promo Code", not "Coupon", not "Discount Code". People give up here because they're scanning for the wrong label.
6. Paste EVOXT595 (or AFF1129-hostspot, or BHW595) and click Apply. The order total updates immediately.
7. Pay with a card, PayPal, Bitcoin or USDt on Tron.

The three failure modes:

- **The label.** Already covered, and it accounts for most of the "the code doesn't work" complaints you'll find in comment sections.
- **One code per order.** A second code gets rejected; whichever you entered first is the one that sticks. A code can sit on top of a plan's existing promotional price, so this isn't the same thing as banning stacked discounts.
- **The plan tier.** VM-0.5 and VM-0.75 are below the threshold. The field will accept the code and the total won't move. If you want the discount, VM-1 is the floor.

Apply the code before paying rather than after. Fixing it on an issued invoice means opening a ticket, and tickets run 4 to 8 hours.

## Which plan actually fits

The discount reshuffles the lineup in one non-obvious way. **VM-0.75 at $4.99 is more expensive than VM-1 at $3.59**, and VM-1 doubles the RAM and the transfer. There's no reason to buy the 1 GB tier unless you have a hard reason to stay under five dollars without touching a coupon.

- **A bot, a VPN endpoint, one static page** → VM-0.5, $2.99. It's the cheapest thing Evoxt sells and the code wouldn't help anyway.
- **WordPress, a Laravel or Node app, a staging box** → VM-1. 2 GB is the realistic floor for a database-backed site, and $3.59/month is below most hosts' 512 MB pricing.
- **You want a second core without jumping to 4 GB** → VM-1.5 at about $4.17. You pay 58 cents more than VM-1 for the extra vCore.
- **Client sites or several databases** → VM-2 at $7.19 (4 GB, 2 vCores) or VM-3 at $8.99 (4 vCores, 3 TB). VM-3 is the better value of the two if you need parallelism rather than memory.
- **Traffic from Asia** → Hong Kong Premium for CN2, Tokyo or Osaka for Japan, Malaysia Premium Plus for local ISP peering. Same plan price, smaller transfer allowance, so size the plan with bandwidth in mind rather than RAM.
- **Bare metal** → Evoxt runs dedicated servers from $169/month on Ryzen and Intel hardware, Malaysia only.

Third-party testing backs the CPU claim at least partly: VPSBenchmarks measured VM-1 in February 2026 and found single-core performance in line with the advertised clocks, and ranked Evoxt second in its 2025 list of best VPS under $25. The 3.5 GHz base with turbo up to 6.0 GHz is the pitch, and single-threaded work is where it shows.

## Where Evoxt is weaker

Ticket support runs 4 to 8 hours. Discord and Telegram are faster, usually within a few hours, and for a $3.59 server that's a reasonable trade.

Some users have reported billing inconsistencies around renewals. Nothing dramatic, but on a provider whose main selling point is a price that doesn't change, it's worth checking the renewal line on your first invoice rather than assuming. Evoxt has operated since 2020, which is a shorter track record than Hostinger or IONOS, and dedicated servers are only available in Malaysia.

The refund window is 24 hours. Deploy the server, run your actual workload against it, and if the performance or the network doesn't hold up, ask for a full refund inside that window. It's a short window, so don't sit on it. 👉 [Start a VM-1 deployment and test it before committing further](https://bit.ly/EvoXt)

## How it compares to Hostinger, RackNerd and IONOS

|  | Evoxt | Hostinger | RackNerd | IONOS |
| --- | --- | --- | --- | --- |
| Entry price | $2.99/mo | $4.99/mo (24-month term) | $2.99/mo (promo) | $2.00/mo |
| Renewal | Unchanged | Rises to about $9.99/mo on most plans | Locked during promo term | Stable |
| CPU clock | Up to 6.0 GHz turbo | Around 3.5 GHz | Varies by node | NVMe, specs vary |
| Recurring discount | Yes, 40% with code | First term only | Promo-based | No |
| Free backups | Weekly, included | Weekly; daily costs extra | Not standard | Not standard |
| Crypto payment | Yes | No | No | No |
| Locations | 16 | 6 regions | Mostly US | EU and US |

Hostinger wins on panel polish and brand track record. IONOS wins on the absolute lowest entry price and EU footprint. RackNerd is competitive on promo pricing if you're US-only and comfortable with the usual promo-cycle buying. Evoxt's case rests on the renewal price holding and on single-core speed at that price point.

## Questions that come up before checkout

**Can I stack EVOXT595 and BHW595?**
No. One code per order, and the second entry gets rejected.

**Does the 40% work on VM-0.5?**
No. The discount starts at VM-1. VM-0.5 is already priced at $2.99 without one.

**Will the price jump at renewal?**
The codes are described as recurring by every source that lists them, meaning the discounted rate repeats each billing cycle. Given the reports of renewal billing inconsistencies, verify the amount on your first renewal invoice.

**Is there a refund if I don't like it?**
Yes, within 24 hours of deployment, in full.

**Are Hong Kong and Japan the same price as US regions?**
Same plan price. The transfer allowance is lower on the premium tiers, so you're trading bandwidth for latency.

**What's the cheapest way to get 2 GB of RAM?**
VM-1 with a code at about $3.59, which undercuts VM-0.75 at $4.99.

## Before you order

Match the plan to the job rather than to the discount: 512 MB and nothing more goes on VM-0.5 at $2.99; a single site or app goes on VM-1 at $3.59; several sites or a real database go on VM-2 or VM-3; Asian latency matters more than bandwidth goes on a Premium region with a smaller transfer pool.

Two things to confirm on the order screen before you pay. First, which network tier you selected, because the transfer number changes while the price doesn't. Second, that the discounted total appears in the cart and not just in your head, since the code only counts once you've clicked Apply.

👉 [Compare all Evoxt plans and apply EVOXT595 at checkout](https://bit.ly/EvoXt)
