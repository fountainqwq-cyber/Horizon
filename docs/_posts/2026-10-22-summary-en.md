---
layout: default
title: "Horizon Summary: 2026-10-22 (EN)"
date: 2026-10-22
lang: en
---

> From 96 items, 8 important content pieces were selected

---

**AI Products &amp; Industry**
1. [Meta: Muse tops 10M users as shopping leads](#item-personal-ai-1) ⭐️ 8.0/10
2. [NSA warns on two critical PHP flaws found with AI tooling](#item-personal-ai-2) ⭐️ 8.0/10
3. [Recursive launches Flint, a free local coding model](#item-personal-ai-3) ⭐️ 7.5/10

**Semiconductor Industry**
1. [Google Cloud, NVIDIA Pin Vera Rubin A5X GA to Next Month](#item-personal-chips-1) ⭐️ 7.0/10
2. [NVIDIA&\#x27;s cuDSS reaches general availability](#item-personal-chips-2) ⭐️ 6.0/10

**Consumer Electronics Industry Trends**
1. [Micron Rules Out 4F² DRAM Scaling, Charts 3D DRAM Roadmap With Wafer Bonding and High-NA EUV](#item-personal-electronics-1) ⭐️ 7.0/10

**Business &amp; Economy**
1. [Big Three U.S. banks take nearly 80% of equities revenue](#item-personal-business-1) ⭐️ 6.5/10
2. [Super Micro raises revenue outlook; SpaceX reports 161% jump](#item-personal-business-2) ⭐️ 6.2/10

---

## AI Products &amp; Industry

<a id="item-personal-ai-1"></a>
### [Meta: Muse tops 10M users as shopping leads](https://techcrunch.com/2026/10/21/meta-says-muse-has-over-10m-users-with-shopping-a-top-activity/) ⭐️ 8.0/10

On its Q3 earnings call, Meta said its AI app Muse has surpassed 10 million users, with about 25% using it daily and shopping emerging as a top activity. CEO Mark Zuckerberg said more than a quarter of engaged shopping users averaged purchases over $200; these are company claims and were not independently verified.

rss · TechCrunch AI · Oct 21, 21:14

**「Impact」** Muse is shifting from adoption to monetization: Meta plans to keep it free for most users, take a cut of commerce, and charge power users for advanced models or more tokens. The shopping activity links the AI agent to merchants, Plaid-connected payments and Meta’s broader smart-glasses strategy.

**「Details」** Disclosed Oct. 21, 2026. Meta also cited forthcoming “Muse Confidential VM” privacy controls, a target to improve compute cost efficiency more than 10x next year, and a teased “Muse network” for agents to interact. Source: https://techcrunch.com/2026/10/21/meta-says-muse-has-over-10m-users-with-shopping-a-top-activity/

**Tags**: `#Meta Muse`, `#AI agents`, `#agentic shopping`, `#earnings`, `#consumer AI`

---

<a id="item-personal-ai-2"></a>
### [NSA warns on two critical PHP flaws found with AI tooling](https://techcrunch.com/2026/10/21/php-armageddon-openai-googles-wiz-find-ancient-holes-panicking-the-internet/) ⭐️ 8.0/10

The U.S. National Security Agency warned Wednesday that two critical vulnerabilities exist in PHP, the server-side language used by roughly 70% of websites, and said sites that cannot be patched immediately should be taken offline. The PHP Foundation has already issued patches; the flaws date back to PHP 5 \(2004\), and PHP 8.1 and older are no longer supported, with PHP 8.5.12 recommended. OpenAI said its &quot;Patch the Planet&quot; participant Calif found one flaw using GPT-5.6 Sol, while Wiz said its Atlas agent, using Gemini 4 Argon and GPT-5.6 Sol, found multiple PHP vulnerabilities; both coordinated disclosure with PHP and other vendors. OpenAI said no exploits were reported in the wild before disclosure.

rss · TechCrunch AI · Oct 21, 17:59

**「Impact」** Administrators of PHP-based sites, including WordPress installations and their hosting providers, face urgent upgrade or takedown decisions because the flaws could allow attackers to reach server file systems or databases. Wiz warned that LLMs now lower the barrier to adapting exploits across PHP versions and configurations, raising risk for unpatched systems.

**「Details」** Recommended action: update servers to PHP 8.5.12; the NSA advised pulling sites offline until patching is possible. WordPress said the flaw is not WordPress-specific and that sites must patch servers with their hosting companies. Wiz credited Automattic, Akamai, AWS, Cloudflare, Fastly, Imperva, Microsoft and Vercel in the coordinated effort.

**Tags**: `#AI security`, `#PHP vulnerabilities`, `#OpenAI`, `#Google Wiz`, `#NSA warning`

---

<a id="item-personal-ai-3"></a>
### [Recursive launches Flint, a free local coding model](https://techcrunch.com/2026/10/21/recursive-launches-flint-a-laptop-coding-model-it-says-was-largely-built-by-ai/) ⭐️ 7.5/10

Recursive released Flint on Oct. 21, a free coding model that runs locally on a laptop and is downloadable from Hugging Face under the Apache 2.0 license. The company says its Eureka Machine research system helped build Flint in under four months and that the model generated about 131 tokens per second on an M4 Pro MacBook Pro—roughly double comparable small models. Those performance and AI-build claims are company assertions, not independently verified.

rss · TechCrunch AI · Oct 21, 20:27

**「Impact」** For developers, Flint offers offline, private coding assistance without per-token cloud fees. Recursive concedes it needs more guidance than paid coding assistants, so its practical value depends on tasks that can be broken into smaller steps.

**「Details」** Flint is a mixture-of-experts model activating 2.5 billion of its 40 billion parameters per task. Recursive reports over 150 tokens per second on Nvidia’s RTX Spark and says Flint beat models under 50 billion parameters on SWE-Bench Verified, though Alibaba’s Qwen3.8 27B scored higher on its six-test average.

**Tags**: `#local AI models`, `#coding models`, `#model launch`, `#recursive self-improvement`, `#benchmarks`

---

## Semiconductor Industry

<a id="item-personal-chips-1"></a>
### [Google Cloud, NVIDIA Pin Vera Rubin A5X GA to Next Month](https://blogs.nvidia.com/blog/google-cloud-vera-rubin-infrastructure/) ⭐️ 7.0/10

Google Cloud and NVIDIA announced A5X instances built on Vera Rubin NVL72, with general availability scheduled for next month and planned expansion to Europe. According to the vendor announcement, Google Cloud plans to scale its Vera Rubin-based infrastructure to as many as 960,000 Rubin GPUs across multiple sites. The post gives no firmer GA date than “next month.”

rss · NVIDIA official blog · Oct 21, 10:45

**「Impact」** The instances target cloud customers running large-scale training, inference and reinforcement learning; London-based Ineffable Intelligence is the first customer. The announcement also places NVIDIA’s rack-scale Vera Rubin platform inside Google Cloud’s AI Hypercomputer, with a planned European footprint.

**「Details」** A5X combines Vera Rubin NVL72, ConnectX-9 SuperNICs, Google Cloud Virgo Network and fourth-generation liquid cooling. Google Cloud also said it will be among the first providers to offer NVIDIA Confidential Computing at rack scale on bare-metal A4X Max instances and is making Confidential Computing generally available on G4 VMs. WPP tested a creative-agent workflow on a single A5X instance, the companies said.

**Tags**: `#NVIDIA`, `#Google Cloud`, `#Vera Rubin`, `#AI infrastructure`, `#GPU capacity`

---

<a id="item-personal-chips-2"></a>
### [NVIDIA&\#x27;s cuDSS reaches general availability](https://blogs.nvidia.com/blog/cudss-generally-available-engineering-scientific-simulation/) ⭐️ 6.0/10

NVIDIA announced general availability of cuDSS, a CUDA-X library that moves sparse-system solving in engineering and scientific simulation onto GPUs. The company says integrations include Cadence Celsius, Synopsys Sentaurus and Siemens Simcenter STAR-CCM+. NVIDIA and partners report vendor-measured speedups, including up to 10x in Applied Materials&\#x27; Ginestra and 8–10x in Dassault Systèmes&\#x27; Abaqus solvers.

rss · NVIDIA official blog · Oct 21, 10:30

**「Why it matters」** The library targets chip-design, materials and multiphysics workloads where repeated sparse solves can limit how many designs teams test. It affects EDA and simulation software users rather than changing semiconductor manufacturing capacity or supply.

**「Availability and claims」** NVIDIA announced cuDSS on Oct. 21, 2026. It offers C, C++, Python and Fortran interfaces and is designed to scale from workstations to clusters. The cited speedups — including 4x for a ZEISS SMT EUV lithography plasma benchmark with COMSOL Multiphysics — are vendor claims. Source: https://blogs.nvidia.com/blog/cudss-generally-available-engineering-scientific-simulation/

**Tags**: `#NVIDIA`, `#cuDSS`, `#EDA simulation`, `#semiconductor design`, `#GPU acceleration`

---

## Consumer Electronics Industry Trends

<a id="item-personal-electronics-1"></a>
### [Micron Rules Out 4F² DRAM Scaling, Charts 3D DRAM Roadmap With Wafer Bonding and High-NA EUV](https://www.ithome.com/1/016/208.htm) ⭐️ 7.0/10

At its 2026 annual technology webinar \(reported 22 October 2026\), Micron said 4F² DRAM has no viable path to volume production after more than two decades of development, citing complexity and cost, and will pursue 3D DRAM instead as conventional 2D 6F² DRAM runs into scaling limits. The vendor-sourced roadmap puts the 7th-generation 10nm-class node 1δ in yield ramp with roughly 25% generational density gain, adds wafer bonding at the 8th-generation 1ε node, plans High-NA EUV for the first sub-10nm node ζÅ in early development, and is pathfinding the second sub-10nm node ηÅ with new materials. Micron also said DRAM CMOS logic will move to 3D.

rss · IT Home industry reports \(strict trend filter\) · Oct 22, 01:31

**「Diverging roadmaps reshape DRAM supply chain」** Per the report, Micron&\#x27;s roadmap shifts the density-scaling burden from lithographic shrink toward wafer bonding, High-NA EUV and eventually 3D cell architecture — implying new equipment and process requirements at 1ε and ζÅ, and a longer, costlier path to each node. Micron says 1δ&\#x27;s ~25% density gain will feed HBM5, vHBM, vEIM, LPDDR and DDR, so that node&\#x27;s yield ramp matters for high-value memory supply. Vendor strategies are splitting: the article notes ChangXin Memory said it plans a 4F² hybrid-bonded DDR5 RDIMM within the year, while reports say Samsung dropped 4F² for its first sub-10nm DRAM. Inference, not stated in the source: this divergence could fragment process tooling and materials demand across suppliers and complicate cost comparisons between vendors&\#x27; node claims.

**「Evidence caveat」** The roadmap details are vendor claims presented at Micron&\#x27;s own event, with no independent shipment, bit-share, wafer-capacity or cost data in the source; the ~25% density figure is a Micron estimate for 1δ and has not been verified externally. The CXMT plan and Samsung report are cited by the article without primary documentation, and timing for 1ε, ζÅ and ηÅ volume production was not given.

**Tags**: `#DRAM`, `#3D DRAM`, `#Micron`, `#High-NA EUV`, `#wafer bonding`

---

## Business &amp; Economy

<a id="item-personal-business-1"></a>
### [Big Three U.S. banks take nearly 80% of equities revenue](https://www.cnbc.com/2026/10/21/goldman-sachs-jpmorgan-morgan-stanley-ai-trading.html) ⭐️ 6.5/10

Goldman Sachs, JPMorgan and Morgan Stanley generated a combined $52 billion in equities-trading revenue through Sept. 30, almost 80% of the $67 billion booked by the five largest investment banks, according to company filings. The total already exceeds the group’s full-year 2025 record by about $7 billion, helped by AI-related trading and Asian semiconductor flows. Goldman’s equities financing revenue rose 96% in the third quarter to a record $3.37 billion.

rss · CNBC business and economy · Oct 21, 15:30

**「Impact」** The concentration gives the Big Three more balance-sheet capacity to finance multibillion-dollar AI trades, while smaller banks struggle to underwrite single-trade risks of that size. It also ties their equities results more closely to demand for AI hardware, hyperscalers and Asian chipmakers.

**「Details」** The figures cover revenue through Sept. 30. Comparisons are imperfect because banks do not use a uniform definition of equities-trading revenue, and Asian totals include transaction taxes and stamp duties, the report said.

**Tags**: `#AI stocks`, `#investment banks`, `#equities trading`, `#Wall Street`, `#semiconductors`

---

<a id="item-personal-business-2"></a>
### [Super Micro raises revenue outlook; SpaceX reports 161% jump](https://www.cnbc.com/2026/10/21/stocks-making-the-biggest-moves-premarket-spcx-smci-nflx-more.html) ⭐️ 6.2/10

Super Micro Computer raised its fiscal first-quarter revenue outlook to $18.5bn–$19.5bn from $14.5bn–$15.5bn, CNBC reported Oct. 21. SpaceX reported a 161% year-over-year rise in third-quarter revenue to $14.58bn, and Elon Musk said SpaceX and Tesla had formed special committees to discuss a possible merger, according to the report.

rss · CNBC business and economy · Oct 21, 11:49

**「Impact」** The Super Micro update points to stronger expected demand for data-center servers and was accompanied by premarket gains at Dell and HPE. SpaceX’s figures and possible Tesla combination matter to suppliers and Tesla investors, but no deal has been announced.

**「Details」** Netflix reported third-quarter revenue of $12.87bn, up 12% year over year and in line with Wall Street expectations, CNBC said. Dell rose 5.5% and HPE 4.5% premarket after Super Micro’s guidance update. Source article: https://www.cnbc.com/2026/10/21/stocks-making-the-biggest-moves-premarket-spcx-smci-nflx-more.html

**Tags**: `#Super Micro`, `#SpaceX`, `#Netflix`, `#earnings`, `#AI infrastructure`

---