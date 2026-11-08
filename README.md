# Awesome-API-Uptime-Performance-Monitoring

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **the open-source side of your list is essentially empty**, and several SaaS entries have no usable pricing.



## The data problems



**"Postman Monitoring"** is a feature inside a proprietary client, not a standalone uptime monitoring platform. No pricing for the monitoring feature itself was surfaced. Mark it "quote-only" or omit it.



**Datadog Synthetic Monitoring pricing is per test run**, which makes cost estimation fundamentally different from monitor-based tools. A test running every minute from one location generates **60 runs/hour**, and **every added location multiplies that** . UptimeRobot's comparison shows 50 endpoints checked every 60 seconds costs **~$1,080/month on Datadog** versus **$19/month on UptimeRobot** . **Do not present these as interchangeable pricing models.**



**Dynatrace's rate card is fragmentary.** The results show **$0.0045 per synthetic action**, **$0.0001 per property per session**, and per-request rates—but no complete pricing picture . Treat as indicative only.



**Sematext has no public list pricing**—its guide describes a cost calculator and custom plans, not published tiers .



**Pingdom has no pricing in the results.** Do not fabricate figures.



## What the search results actually contain



**SaaS pricing (usable):**



| Vendor | Entry pricing | Free tier |

|---|---|---|

| **UptimeRobot** | Solo **$9/mo** (10 monitors, 60s); Team **$35/mo** (100 monitors, 30s); Scale **$65/mo** (200 monitors, 15s)  | **Yes—50 monitors, 5-min checks**  |

| **Checkly** | Starter **$24/mo annual** (Detect) + $9 Communicate + $12 Resolve; Team **$64/mo** (Detect) + $30 + $39  | **Yes—Hobby: 10 monitors, 1k browser checks, 10k API checks**  |

| **New Relic** | Usage-based; **500 synthetic checks free**; additional **$0.005/check**  | **Yes—500 checks/mo**  |

| **Site24x7** | **From $9/mo** per the title ; monitor-license based (basic/advanced/host)  | Not specified |



**Open-source tools (usable):**



| Project | What it actually does |

|---|---|

| **Upptime** | Uptime monitor powered by **GitHub Actions**—no server required  |

| **Kuvasz** | Open-source uptime and SSL monitoring service, built in **Kotlin**  |

| **Upstat** | Simple self-hosted status monitoring tool  |

| **miniboard** | Lightweight dashboard with tabs, uptime monitoring and notifications  |

| **arewedown** | Customizable HTTP uptime and status checking service  |

| **uptime-kuma-helm** | Helm chart for deploying Uptime Kuma on Kubernetes  |



**What is missing:**

- **No star counts** for Upptime, Kuvasz, Upstat, or any open-source project.

- **No pricing** for Pingdom, Postman Monitoring, or Datadog's per-test-run rates beyond UptimeRobot's secondary citation .

- **No revenue or valuation** for any vendor.



## What I recommend



**Remove Postman Monitoring** from the platform list—it is a client feature, not a monitoring platform.



**The open-source section is functional but niche.** Upptime (GitHub Actions-based) and Kuvasz (Kotlin) are the most substantive entries, but **no star counts were surfaced**—do not invent them. **Uptime Kuma** is notably absent from the results, but the Helm chart  implies its existence; do not list it without verified data.



**The SaaS section has usable pricing for UptimeRobot, Checkly, New Relic, and Site24x7.** Pingdom, Postman, Sematext, and Dynatrace should be marked **"pricing not surfaced"** or **"quote-only."**



**Flag the pricing model difference explicitly** in your README: monitor-based (UptimeRobot, Checkly) versus per-test-run (Datadog) versus per-check (New Relic) produce wildly different costs at the same monitoring frequency . A reader choosing between them needs that context.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate star counts, invent Pingdom or Postman pricing, or present Datadog and UptimeRobot as directly comparable without the per-run caveat.
