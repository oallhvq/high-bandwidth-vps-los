# High bandwidth VPS Los Angeles: is 10 Gbps a port or a DDoS filter, how much traffic do you actually get, and which SixtyNet plan fits? (Full plan table with prices)

SixtyNet's cheapest Los Angeles plan is **LAX-STARTER**: 2 cores, 2 GB RAM, 40 GB NVMe, a 2 Gbps port and 5 TB of traffic a month, at $200 for the year when you prepay ($240 at the standard rate, so about $17 a month). The same LAX family runs up to LAX-LARGE with a 10 Gbps port and 40 TB of traffic for $1,600 a year.

Three different numbers get sold as "high bandwidth" in this market, and only two of them affect what your server can actually serve: the port rate and the monthly traffic allowance. The third, DDoS scrubbing capacity, is the one most often printed in 10 Gbps-sized type. SixtyNet's pricing page keeps them apart, and the table below does the same.

> Most people searching this keyword need 1–5 TB a month and a 1–2 Gbps port. LAX-STARTER covers that at $200 a year with a real 5 TB allowance. Past roughly 20 TB, the traffic cap becomes the binding constraint rather than the port, and LAX-MEDIUM at $800 a year is the cheapest point in the LAX range where you get 20 TB and a 10 Gbps port together.
> 👉 [See SixtyNet's Los Angeles plans and monthly traffic caps](https://sixtynet.net/aff.php?aff=39)

## Every SixtyNet plan, with the port and the traffic cap in separate columns

SixtyNet shows two prices per plan. The higher one is the standard twelve-month figure; the lower one is what you pay when you prepay the year, a saving of 13–17% depending on the plan. Divide by twelve for the monthly equivalent.

| Plan | vCPU / RAM | NVMe | Port & monthly traffic | Price (USD) | Order |
| --- | --- | --- | --- | --- | --- |
| LAX-STARTER | 2 cores / 2 GB | 40 GB | 2 Gbps · 5 TB · DDoS | $200/yr ($240 std) | [LAX-STARTER](https://sixtynet.net/aff.php?aff=39) |
| LAX-MICRO | 4 cores / 4 GB | 80 GB | 4 Gbps · 10 TB · DDoS | $400/yr ($480 std) | [LAX-MICRO](https://sixtynet.net/aff.php?aff=39) |
| LAX-MEDIUM | 8 cores / 8 GB | 160 GB | 10 Gbps · 20 TB · DDoS | $800/yr ($960 std) | [LAX-MEDIUM](https://sixtynet.net/aff.php?aff=39) |
| LAX-LARGE | 8 cores / 16 GB | 320 GB | 10 Gbps · 40 TB · DDoS | $1,600/yr ($1,920 std) | [LAX-LARGE](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-500G | 4 cores / 4 GB | 300 GB + 200 GB RAID10 | 10 Gbps · 10 TB · DDoS | $400/yr ($480 std) | [LAX-Storage-500G](https://sixtynet.net/aff.php?aff=39) |
| LAX-Storage-1TB | 8 cores / 8 GB | 700 GB + 300 GB RAID10 | 10 Gbps · 15 TB · DDoS | $700/yr ($840 std) | [LAX-Storage-1TB](https://sixtynet.net/aff.php?aff=39) |
| IRVINE-PRO-STARTER | 2 cores / 2 GB | 40 GB | 2 Gbps · 5 TB · AS9929 | $350/yr ($420 std) | [IRVINE-PRO-STARTER](https://sixtynet.net/aff.php?aff=39) |
| Irvine Pro, 4-core tier | 4 cores / 4 GB | 80 GB | 4 Gbps · 10 TB · AS9929 | not shown on page | [Irvine Pro tier](https://sixtynet.net/aff.php?aff=39) |
| Residential-STARTER | 2 cores / 2 GB | 40 GB | 2 Gbps · 5 TB · residential IP | $260/yr ($300 std) | [Residential-STARTER](https://sixtynet.net/aff.php?aff=39) |
| Residential-MICRO | 4 cores / 4 GB | 80 GB | 4 Gbps · 10 TB · residential IP | $460/yr ($540 std) | [Residential-MICRO](https://sixtynet.net/aff.php?aff=39) |
| Residential-MEDIUM | 8 cores / 8 GB | 160 GB | 10 Gbps · 20 TB · residential IP | $860/yr ($1,020 std) | [Residential-MEDIUM](https://sixtynet.net/aff.php?aff=39) |
| Residential-LARGE | 16 cores / 16 GB | 320 GB | 10 Gbps · 40 TB · residential IP | $1,660/yr ($1,980 std) | [Residential-LARGE](https://sixtynet.net/aff.php?aff=39) |
| Los Angeles China Unicom-Premium | not published | not published | 100 Mbps base, 3× burst, 95th percentile | $2,500/yr ($3,000 std) | [China Unicom-Premium](https://sixtynet.net/aff.php?aff=39) |

The page writes the port figures as "2G / 4G / 10G Premium Network". Disk throughput is listed separately: 12,500 IOPS on the STARTER and MICRO tiers, 25,000 IOPS on MEDIUM and LARGE.

Three things the table doesn't show, all from the same page:

- **DDoS protection appears on the LAX and LAX-Storage plans only.** The Residential, Irvine Pro and China Unicom lines don't list it.
- **Residential IP plans block ports 80 and 443.** SixtyNet states this openly, citing IP risk control. You cannot host a normal website on the Residential line, whatever the specs suggest.
- **No general refund policy is published.** The only refund wording on the page is attached to the Irvine Pro line, and it says refunds are issued as website balance, not money back.

## What "high bandwidth" means at each provider, and where the label misleads

Port rate is a ceiling on throughput at any instant. The traffic cap is what you're allowed to move across a month. They are not interchangeable, and the arithmetic is sobering: 5 TB spread evenly across 30 days averages about 15 Mbps, and even 40 TB averages roughly 125 Mbps. A 10 Gbps port is a burst allowance, not a sustained one.

The same word covers all three quantities across the Los Angeles market:

- **ExtraVM** sells 5 Gbps ports paired with 3 TB to 40 TB of traffic, from $4.50/month for 1 GB RAM up to $192/month for 64 GB and 40 TB. Its page header advertises "up to 10 Gbps ports" while the plan table stops at 5 Gbps, so go by the table.
- **INIZ** puts a 2.5 Gbps port on every Los Angeles plan, backed by 10 Gbps server uplinks, with traffic from 2 TB to 32 TB. Note its two price lists: the main site quotes pounds (£4.50 to £64 a month) and the store page quotes dollars ($6.07 to $86.34 a month). Different currencies, no exchange rate published, so don't mix the two columns.
- **OliveVPS** is the clearest example of the trap. Its page displays "10 Gbps" prominently, and all three plans ($3.99 to $15.99) run 1 Gbps ports. The 10 Gbps refers to free DDoS scrubbing capacity, and traffic tops out at 5 TB.
- **Hawk Host** publishes configurations from 1 GB/2 TB up to 64 GB/20 TB, no prices on the page, and charges extra for DDoS mitigation.

SixtyNet sits at the top of that range on both axes: 2 Gbps on the entry plan, 10 Gbps from LAX-MEDIUM upward, and 40 TB on the largest LAX tiers. Nothing on its page inflates the scrubbing capacity into a headline number.

## The bandwidth model that catches people out: 95th percentile and burst

The Los Angeles China Unicom-Premium plan isn't sold like a VPS at all. It's a committed 100 Mbps circuit with a 3× burst rate and 95th percentile billing, priced at $2,500 a year with a free BGP session setup and limited BGP technical support.

Percentile billing works on samples rather than totals. The provider polls your throughput at intervals, discards the top 5% of samples, and bills on the highest remaining one. Short spikes, like a nightly backup or an OS update pushed to a fleet, get discarded. Sustained load sets your rate. With a 3× burst, traffic can spike to roughly 300 Mbps without instantly changing the committed rate.

That suits VPN endpoints, relays and anyone announcing their own address space over BGP. It's a poor fit if you want a fixed monthly figure you can predict from a traffic counter, and it's a different purchase from the LAX plans, which are byte-capped.

## When you exceed the traffic cap, what does it cost?

Of the Los Angeles providers checked, only one publishes an overage rate: **OliveVPS charges $0.005/GB**, about $5.12 per TB, and describes it as roughly 18 times cheaper than the major clouds (a vendor claim, not an independently verified one). ExtraVM, INIZ, Hawk Host and SixtyNet publish no overage rate on their pricing pages.

That silence matters more than it looks. A 5 TB plan running 6 TB is either a small bill or a suspension, depending on a policy you can't read. Before prepaying a year anywhere, including here, ask three questions in writing:

1. What is the per-GB overage rate, and is it billed automatically or does the port get throttled first?
2. Is the allowance metered on outbound traffic only, or inbound plus outbound?
3. Does unused traffic roll over, and does the cap reset on the billing anniversary or the calendar month?

A provider that answers those three clearly is telling you something about how the rest of the service is run. SixtyNet's advantage here is that the traffic allowance is generous relative to the plan size: 40 TB on LAX-LARGE is hard to exhaust with a normal workload, which reduces how often the unanswered question bites.

👉 [Check the current LAX plan prices and traffic caps before you commit to a year](https://sixtynet.net/aff.php?aff=39)

## Choosing between the five SixtyNet lines

The LAX family is the one that matches this search. Los Angeles location, DDoS protection listed, 2 to 10 Gbps premium network, 5 to 40 TB of traffic, 2 to 16 GB RAM. LAX-Storage swaps CPU headroom for RAID10 capacity and free bonus disk (300 GB + 200 GB, or 700 GB + 300 GB), which is the better buy if you're storing media rather than serving requests per second.

Irvine Pro and the China Unicom line both list AS9929, China Unicom's premium backbone, aimed at mainland Chinese users. Irvine Pro also carries a hard security note: it rejects external probes and scans, and access is restricted to whitelisted or port-forwarded devices. Expect to configure it before you can reach anything, and expect refunds to land as account credit.

The Residential line sells consumer ISP IP addresses rather than datacenter IPs. The page doesn't name the city for these plans, and the port 80/443 block rules out web hosting. A pair of third-party test write-ups published in October 2025 described the residential series as KVM-based on AMD EPYC 7002 hardware, with the advertised 10 Gbps measuring closer to 1 Gbps in practice and ICMP blocked. Those observations are over a year old and cover the residential line only, so treat them as a reason to test before prepaying rather than as a verdict on the LAX plans.

## Real latency numbers from Los Angeles, and how to read them

Los Angeles is the main US landing point for trans-Pacific submarine cables, which is why this location keeps coming up for anyone serving Asia.

ExtraVM publishes ranges: 110–150 ms to Tokyo, 160–180 ms to Singapore, 5–30 ms across the western US, 60–80 ms to the east coast. OliveVPS publishes single-point figures: 1–3 ms locally, 108 ms to Tokyo, 138 ms to London, 150 ms to Sydney. The two Tokyo numbers come from different measuring conventions (a range against a single sample), so treat both as ballparks. SixtyNet doesn't publish latency figures for the LAX line, which is the one gap worth closing with a test IP before you pay for a year.

## Who should not buy a high-bandwidth Los Angeles VPS

A single site with a few hundred visitors a day does not need 10 Gbps or 20 TB. 1 Gbps and 1–2 TB will do, and the reference prices in this market are OliveVPS Starter at $3.99/month and ExtraVM's 1 GB plan at $4.50/month. SixtyNet's cheapest Los Angeles plan is $200 a year, roughly $17 a month, so if budget is the deciding factor, it loses that comparison outright and isn't trying to win it.

Skip the Residential line entirely if you plan to run a website. Skip any plan whose overage policy you can't get in writing if you expect to run near the cap. And if you need a money-back guarantee as a condition of buying, ask first: the only refund language on SixtyNet's page is account credit on the Irvine Pro line.

## The decision, in rules

- **5 TB or less, one application, Los Angeles presence** → LAX-STARTER at $200 a year.
- **10 TB and a 4 Gbps port** → LAX-MICRO at $400 a year.
- **20 TB with a 10 Gbps port, CDN origin or media delivery** → LAX-MEDIUM at $800 a year.
- **40 TB, or storage-heavy with RAID10** → LAX-LARGE at $1,600, or LAX-Storage-1TB at $700 if 15 TB is enough.
- **Mainland Chinese users on AS9929** → Irvine Pro from $350 a year, with the whitelist caveat.
- **Committed bandwidth with BGP and percentile billing** → the China Unicom-Premium line at $2,500 a year.

Two things to settle with support before you pay: the overage rate and whether the cap throttles or bills, and the refund terms in writing. Everything else is on the pricing page.

👉 [Open SixtyNet's VPS pricing page and match a plan to your monthly traffic](https://sixtynet.net/aff.php?aff=39)
