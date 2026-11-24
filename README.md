# Evoxt vs LightNode: Which Cheap VPS Should You Buy? Full Evoxt Plan List, Same-Budget Spec Diffs and What the Benchmark Grades Say

Evoxt's VM-2 costs **$11.99/month** for 2 vCPUs, 4 GB RAM and 30 GB NVMe. LightNode's nearest plan in the same independent benchmark set, Agency, costs **$14.70** for the same cores and RAM plus 20 GB more disk. Evoxt is $2.71 cheaper and runs newer silicon (AMD EPYC Genoa/Milan against Intel Xeon Skylake). LightNode took an A for performance stability on that plan where Evoxt's VM-2 took an E.

That single trade-off drives most of this comparison. Everything else, including two network grades that should make you pause on both sides, is secondary.

Below you'll find every plan Evoxt currently lists, the two same-budget matchups broken down line by line, the feature gaps that eliminate one vendor or the other depending on what you're building, and the three things Evoxt's own pages don't lead with.

> **Most readers should start with Evoxt VM-2**: $11.99/month, 2 vCPUs, 4 GB RAM, 30 GB NVMe, weekly offsite backup included. It's the best CPU-per-dollar at the $12 mark. Take LightNode instead if you need hourly billing, block storage, or the strongest stability grade in this price range.
> 👉 [Check VM-2's current price and deploy it](https://bit.ly/EvoXt)

## Every Evoxt plan on the pricing page

Evoxt sells eleven plans, from a 512 MB box at $3.49 to a 16-core machine at $95.99. The three that make sense for most independent developers are VM-1 at $5.99, VM-2 at $11.99 and VM-4 at $23.99; the rest exist for people who already know their RAM ceiling.

| Plan | vCPU / RAM | NVMe | Transfer | Price/mo | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 / 512 MB | 5 GB | 150 GB | $3.49 | [Deploy](https://bit.ly/EvoXt) |
| VM-0.75 | 1 / 1 GB | 10 GB | 250 GB | $4.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-1 | 1 / 2 GB | 20 GB | 300 GB | $5.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-1.5 | 2 / 2 GB | 20 GB | 300 GB | $6.95 | [Deploy](https://bit.ly/EvoXt) |
| VM-2 | 2 / 4 GB | 30 GB | 600 GB | $11.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-3 | 4 / 4 GB | 30 GB | 700 GB | $14.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-4 | 4 / 8 GB | 60 GB | 1,000 GB | $23.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-6 | 8 / 8 GB | 60 GB | 1,250 GB | $29.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-8 | 8 / 16 GB | 80 GB | 2,000 GB | $47.99 | [Deploy](https://bit.ly/EvoXt) |
| VM-12 | 16 / 16 GB | 80 GB | 2,500 GB | $60.95 | [Deploy](https://bit.ly/EvoXt) |
| VM-16 | 16 / 32 GB | 100 GB | 4,000 GB | $95.99 | [Deploy](https://bit.ly/EvoXt) |

Every plan includes a weekly offsite backup, IPv6, browser VNC, API access, KVM virtualisation and NVMe storage. Billing runs monthly, quarterly, semi-annually, annually, biennially or triennially; longer prepayments are cheaper per month. Prices are in USD.

**One number to verify before you prepay:** transfer quotas for these plans differ between Evoxt's pricing page and third-party trackers. VM-1 appears as 300 GB on the pricing page and 1,000 GB in benchmark listings; VM-8 appears as 2,000 GB and 6,000 GB respectively. The quota attached to your chosen region and billing cycle is the one shown on the deploy screen, so look at it before committing to a three-year term.

👉 [See the quota and price for your region on Evoxt's deploy page](https://bit.ly/EvoXt)

## Same budget, side by side: $11.99 vs $14.70 and $47.99 vs $54.11

The $12 tier is where most readers will land, so start there. Both plans have 2 vCPUs and 4 GB RAM. LightNode's Agency gives you 50 GB of disk against Evoxt's 30 GB NVMe.

|  | Evoxt VM-2 | LightNode Agency |
| --- | --- | --- |
| Price | $11.99 | $14.70 |
| vCPU / RAM | 2 / 4 GB | 2 / 4 GB |
| Disk | 30 GB NVMe | 50 GB |
| Monthly transfer (benchmark listing) | 2 TB | 2 TB |
| CPU | AMD EPYC Genoa / Milan | Intel Xeon Skylake |
| Provisioning time (median) | 175 s | 90 s |

At the top of the range the pattern holds. Evoxt VM-8 is $47.99 for 8 vCPUs, 16 GB RAM and 80 GB NVMe; LightNode Enterprise is $54.11 for the same cores and RAM with 150 GB of disk. You pay $6.12 more to LightNode and get 70 GB more space; you pay Evoxt less and get a newer CPU.

Neither of those differences decides anything on its own. The benchmark grades do.

## The five benchmark grades, and where each vendor falls down

VPSBenchmarks grades each plan from A (top of its comparison set) to F across web performance, raw CPU capacity, performance stability, disk I/O and network performance. These are the plans in both lineups that overlap on price, tested between July 2025 and August 2026.

| Plan | Web | Raw CPU | Stability | Disk IO | Network |
| --- | --- | --- | --- | --- | --- |
| Evoxt VM-1 ($5.99) | B | E | C | B | D |
| Evoxt VM-2 ($11.99) | C | D | E | B | C |
| LightNode Agency ($14.70) | C | E | A | B | F |
| Evoxt VM-4 ($23.99) | B | B | D | B | D |
| Evoxt VM-8 ($47.99) | A | A | D | C | E |
| LightNode Enterprise ($54.11) | D | C | D | C | F |

Three readings matter here.

**Evoxt's strength shows up as you pay more.** VM-8 earns A in both web performance and raw CPU, the best result in this table by a clear margin. At $5.99 and $11.99 you're buying clock speed per dollar, not benchmark dominance.

**Evoxt's stability is the weak column.** C, E, D and D across four plans. VM-2, the plan I'd recommend at $12, has the worst stability grade in Evoxt's lineup. If your app falls over when a noisy neighbour saturates the disk, that letter is the one to stare at, and LightNode Agency's A is the reason to pay $2.71 more.

**Neither provider is good at networking.** Evoxt's network grades run D, C, D and E; LightNode scored F on both tested plans. You are not buying a network-optimised VPS from either vendor at these prices.

LightNode's sample is thin: two provisioning runs against Evoxt's six, and its trials are older (July and October 2025 against Evoxt's February and August 2026). Treat the direction as informative and the exact letter as approximate.

## Feature differences that decide it before price does

|  | Evoxt | LightNode |
| --- | --- | --- |
| Hourly billing | No | Yes |
| Block storage volumes | No | Yes |
| Object storage | No | No |
| Managed databases | No | No |
| Kubernetes | No | No |
| Load balancers | No | No |
| Backups | Weekly offsite, all plans, free | Included |
| Provisioning (median) | 175 s (6 runs) | 90 s (2 runs) |

Two rows in that table settle most buying decisions.

**Hourly billing.** Evoxt's comparison data lists no hourly option; its shortest cycle is monthly. LightNode advertises pay-as-you-go hourly billing on its Tokyo pages and in third-party write-ups. If you need a box for a three-day migration test or a weekend load experiment, Evoxt is the wrong tool regardless of price.

**Block storage.** LightNode offers attachable block volumes; Evoxt does not. Anything that needs a separate data disk you can resize independently of the VM has to run on LightNode.

Everything above the block-storage row is a gap on both sides. If your architecture needs managed Postgres, object storage or a managed Kubernetes control plane, neither vendor sells it, and comparing their VPS prices is wasted effort.

**Provisioning speed** favours LightNode in the measurements available (90 seconds median against Evoxt's 175 seconds median and 261 seconds average). Six runs against two, so don't read too much into the multiplier; do read it as "Evoxt takes a few minutes, not 30 seconds."

## Three things Evoxt's own pages don't lead with

**1. The Japan routing story and the benchmark grades point in different directions.** Evoxt runs two Japan locations: Tokyo on its standard network tier, peering through multiple Tier-1 carriers and BBIX, and Osaka on a premium tier with Softbank as primary transit. Hong Kong and Malaysia premium nodes carry CN2 routes, which is why China-facing projects end up looking at this provider. None of that shows up in the network grades above, which measure throughput under the benchmark's own conditions rather than path quality to a specific country. If your traffic is Japan- or China-bound, run your own latency checks before you pay for a year.

**2. Tokyo has an evening peak.** A published Japan-focused review of Evoxt's nodes reports Tokyo latency in the 50–80 ms range from East Asia during normal hours, degrading to roughly 160 ms at Japanese evening peak, with Osaka holding steadier under load. That is consistent with Evoxt tiering Osaka as the premium network location, and it's a reason to pick Osaka if your users are most active between 8 and 11 pm JST.

**3. There is one loud negative report.** A Reddit post titled "Evoxt, Worst VPS hosting service I've ever experienced" describes packet loss on a single IPv4 address. It's one user, one address, and it sits against years of top-three placings in VPSBenchmarks' price categories and a four-star Trustpilot average from a small reviewer base. Support is ticket, live chat, Telegram and Discord, with peak ticket responses reported at 4–8 hours and no phone line. Budget-provider support, priced accordingly.

## Billing, refunds and the promo code question

New accounts get a **14-day money-back guarantee**, which is the cheapest way to test Evoxt's Tokyo or Osaka network against your actual users: pay monthly, benchmark from three locations, and decide inside two weeks.

On promo codes: they circulate heavily on coupon sites and affiliate posts, including recurring-discount codes that would cut VM-1 well below its $5.99 list price. None of the codes I found could be confirmed against an official Evoxt promotion page, and the published claims contradict each other. So treat the checkout total as the real price. If you have a code, that page is the only place that tells you whether it's still live.

Evoxt's pricing page lists one monthly price per plan with no separate renewal rate, unlike hosts that advertise a first-term discount and raise it later. Confirm the amount on the checkout screen anyway before you prepay three years.

👉 [Start on a monthly term and use the 14-day refund window](https://bit.ly/EvoXt)

## FAQ

**Is the $3.49 VM-0.5 with 512 MB usable?**
For a WireGuard endpoint, a DNS resolver, an uptime monitor or a tiny static site, yes. For anything with a database, a control panel or a Node build step, no: 512 MB and 5 GB of NVMe run out during the install. Step up to VM-1 at $5.99, which gives 2 GB RAM and 20 GB.

**Does Evoxt offer hourly billing?**
No. Its shortest billing cycle is monthly, with quarterly through triennial prepayment options. If you need per-hour billing, LightNode is the one that advertises it.

**Which is better for Japan?**
Both run Tokyo. Evoxt also sells Osaka on Softbank transit. The benchmark network grades are weak on both sides, so don't choose on marketing copy; deploy in Tokyo, ping your own users, and switch regions if the evening numbers disappoint.

**Can I get my money back?**
Evoxt offers a 14-day money-back guarantee to new accounts. I did not verify LightNode's refund terms here, so check those separately if that matters to you.

**Will the price jump at renewal?**
Evoxt's pricing page shows a single price per plan with no renewal column, so the listed price appears to be the recurring one. Verify on the checkout page before you commit to a long prepayment.

## How to choose

Run down this list and stop at the first line that matches.

- **Single-threaded web app, API proxy, game server, VPN, bot — under $15/month:** Evoxt VM-2 at $11.99. Newest CPU generation at this price, free weekly offsite backup, and 30 GB of NVMe.
- **Same workload, but the app can't tolerate performance variance:** LightNode Agency at $14.70. You pay $2.71 for an A stability grade.
- **Need a box for days, not months:** LightNode, on hourly billing.
- **Need an attachable data volume:** LightNode, on block storage.
- **Need managed databases, object storage or Kubernetes:** neither. Look at a platform that sells those services.
- **8 cores and 16 GB with the fastest single-core response:** Evoxt VM-8 at $47.99, the only plan in this comparison with A grades for both web and raw CPU. Accept the E network grade and keep the workload latency-tolerant.

Two things to confirm before you pay: pick **Tokyo or Osaka** deliberately (Osaka for steadier evening performance, Tokyo for the wider peering mix), and pick a billing cycle you're willing to test with for 14 days before extending.

👉 [Deploy an Evoxt VM in Tokyo or Osaka](https://bit.ly/EvoXt)
