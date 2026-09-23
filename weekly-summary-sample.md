# Weekly Ads Summary — 14 Sep to 20 Sep 2026

**Bottom line:** Spend rose 5% but conversions fell 5%. Total CPA rose 10% to ₹345 and ROAS fell to 3.47x. Google is on target and improving. Meta missed its CPA target (₹539 vs ₹450), driven by a Prospecting slump and a tracking gap on 17 Sep.

## Scoreboard

| | Spend | Conv. | CPA | ROAS | vs last week | vs target |
|---|---|---|---|---|---|---|
| Total | ₹65,826 | 191 | ₹345 | 3.47x | Spend +5.3%, CPA +10.2%, ROAS −9.9% | — |
| Meta | ₹28,573 | 53 | ₹539 | 2.27x | Spend +3.1%, CPA +51.7%, ROAS −31.6% | Off target (CPA ₹450; 20% over) |
| Google | ₹37,253 | 138 | ₹270 | 4.40x | Spend +7.1%, CPA −5.4%, ROAS +3.3% | On target (ROAS 3.5x) |

## What changed and why

- **Meta tracking gap on 17 Sep.** Both Meta campaigns recorded 0 conversions that day, despite 1,035 clicks. Last week they averaged about 11 per day. That day matches the "Website checkout update deployed" entry in the Change Log, and conversions came back on 18 Sep. Excluding 17 Sep, Meta CPA is ₹467, which is still above target.
- **Meta Prospecting fatigue.** CPA roughly doubled from ₹417 to ₹811, and ROAS fell from 2.69x to 1.42x. CTR dropped 22% (1.09% to 0.85%) while CPC rose 37%, starting on 14 Sep, before the checkout release. The Change Log shows no new creatives were launched this week. Even excluding 17 Sep, CPA is ₹704.
- **Google PMax scaled well.** The Change Log shows a 15% budget increase. Spend rose 14%, conversions rose 26% (61 to 77) and ROAS improved from 3.92x to 4.22x.
- **Meta Retargeting dip is mostly the tracking gap.** Its CPA rose from ₹280 to ₹331. Excluding 17 Sep it is ₹286, and CTR held steady at 1.85%.
- **Google Generic is still below target after the bidding switch.** It moved to Target ROAS 3.5x on 7 Sep. ROAS improved slightly (2.83x to 2.96x) but is still under 3.5x, at only 22 conversions per week.

## Campaign movers

| Campaign | Platform | Spend | CPA or ROAS | WoW | Note |
|---|---|---|---|---|---|
| PMax – All products | Google | ₹21,401 | 4.22x | ROAS +7.7% | Budget +15% converted efficiently |
| Generic – Search | Google | ₹8,192 | 2.96x | ROAS +4.6% | tROAS still learning, below 3.5x |
| Brand – Search | Google | ₹7,660 | 6.43x | ROAS −4.6% | Stable |
| Prospecting – Broad | Meta | ₹18,655 | ₹811 CPA | CPA +94.5% | Fatigue plus tracking gap |
| Retargeting – 30D | Meta | ₹9,918 | ₹331 CPA | CPA +18.3% | Mostly the 17 Sep gap |

## Issues and risks

- 17 Sep Meta conversions are missing, likely because the checkout release broke the Pixel or Conversions API.
- Prospecting creative fatigue will worsen with no new creatives until the next shoot lands.
- Pacing is fine. Meta spent 102% of its ₹28,000 budget and Google spent 106% of its ₹35,000 budget, so the PMax increase is pushing Google toward the upper limit.

*One line was removed from this sample: it treated a normal low day on another campaign as a possible tracking issue. The skill now only flags anomalies that meet a clear rule.*

## Action items for this week

| # | Priority | Action | Campaign | Why | Owner |
|---|---|---|---|---|---|
| 1 | High | Check that Pixel/CAPI events fire through the new checkout, and backfill or annotate 17 Sep | All Meta | 0 conversions on 1,035 clicks after the release | — |
| 2 | High | Launch 2–3 new creatives (existing assets or UGC) and pause the lowest-CTR ads | Prospecting – Broad | CTR −22%, CPA ₹811 | — |
| 3 | Medium | Trim Prospecting budget 15–20% until the new creatives are live, and shift it to Retargeting | Prospecting / Retargeting | Protect Meta CPA target | — |
| 4 | Medium | Hold the PMax budget at its current level for another week before any further increase | PMax | ROAS 4.22x, but Google is at 106% of budget | — |
| 5 | Low | Review Generic after about 30+ conversions on tROAS, then consider a lower target or budget cut | Generic – Search | 2.96x vs 3.5x target | — |

## Data notes

- Compared 14–20 Sep (latest complete week) with 7–13 Sep.
- Targets and Change Log tabs were used; numbers match the sheet's Weekly View tab.
- Meta CPA excluding 17 Sep is shown for context only. No attribution claims are made.

## Slack version

**Ads 14–20 Sep:** Spend ₹65.8K (+5%), 191 conv (−5%), CPA ₹345 (+10%), ROAS 3.47x
- Google on target: 4.40x ROAS; PMax +15% budget brought +26% conversions
- Meta off target: CPA ₹539 vs ₹450 goal
- Meta logged 0 conv on 17 Sep after the checkout release, so we need to check Pixel/CAPI
- Prospecting fatigue: CTR −22%, CPA ₹811, and no new creatives
- This week: fix tracking and launch new Prospecting creatives
