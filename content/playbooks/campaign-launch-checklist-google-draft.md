# Campaign Launch Checklist — Google Ads (Draft v1 for review)

**Last updated:** September 2026
**Format:** same as the Meta tab (filters, ★ essentials, three phases).

---

## How to read this checklist

- **Pick two filters:** Campaign type + Business type.
- **You see three blocks:** Core (every campaign) → Campaign type → Business type.
- **Each block has three phases:** Before launch → Launch day → First 14 days.
- **★ = essential.** Skipping it usually breaks tracking, wastes budget or breaks policy.
- **Every item starts with an action** and fits on one line.

**Which campaign type fits which business?**

| Business type | Usually runs |
|---|---|
| D2C e-commerce | Search, Shopping, Performance Max, Demand Gen |
| Lead generation | Search, Performance Max, Demand Gen |
| Fintech app | App, Search, Video (YouTube) |
| Health & fitness | Search, Shopping, Performance Max, Video (YouTube), App |

---

## 1. Core — every Google Ads campaign

### Before launch

**Account**
- [ ] ★ Turn on two-factor authentication and give admin access to at least two people
- [ ] ★ Complete Google's advertiser verification if prompted
- [ ] ★ Set time zone and currency (INR) correctly — hard to change later
- [ ] Add a payment method and your GSTIN for GST invoices
- [ ] ★ Turn on auto-tagging
- [ ] Link GA4, and Merchant Center, YouTube channel or app accounts where relevant

**Tracking**
- [ ] ★ Install the Google tag on every page (directly or through Google Tag Manager)
- [ ] ★ Create conversion actions and set only one primary conversion per goal; keep the rest secondary
- [ ] ★ Pass real conversion values, not a flat 1 for everything
- [ ] Set the count setting: "One" for leads, "Every" for purchases
- [ ] Set conversion windows to match how long customers take to convert
- [ ] ★ Turn on enhanced conversions (accept the customer data terms first)
- [ ] Check tags with Tag Assistant before launch
- [ ] Use data-driven attribution unless you have a clear reason not to
- [ ] ★ Add UTM parameters or confirm auto-tagging data shows in GA4

**Goals & budget**
- [ ] ★ Set target, acceptable and stop-loss CPA or ROAS — use the [Marketing Calculators](tools.html)
- [ ] ★ Choose a bid strategy that matches your conversion data (Smart Bidding needs enough conversions to learn)
- [ ] Remember Google can spend up to twice the average daily budget on some days
- [ ] Plan for the learning period: up to around 50 conversions or 3 conversion cycles

**Setup**
- [ ] ★ Set locations to "Presence" (people in the area) unless you want people only interested in it
- [ ] Set languages and ad schedule
- [ ] ★ Review auto-applied recommendations and turn off any you don't want
- [ ] Add account-level negative keywords (jobs, free, irrelevant terms)
- [ ] Set brand safety: content suitability, excluded content and placement exclusion lists
- [ ] Review every AI or automatically created asset setting before launch
- [ ] Apply one naming convention to campaigns, ad groups and assets

**Creative & landing page**
- [ ] ★ Check ads, claims and landing pages against Google Ads policies
- [ ] Add business name, logo, sitelinks, callouts and images where available
- [ ] Match the ad message to the landing page headline and offer
- [ ] ★ Test the landing page on mobile: speed, forms and checkout
- [ ] Confirm Customer Match lists have proper consent (India's DPDP consent rules are enforceable from 13 May 2027)

**Final check**
- [ ] Preview ads with the Ad Preview and Diagnosis tool
- [ ] ★ Click every final URL and check tracking parameters
- [ ] Check dates, budgets and bid targets
- [ ] ★ Complete one test conversion and confirm it records

### Launch day
- [ ] ★ Confirm ads are approved; fix any "Disapproved" or "Approved (limited)" issues
- [ ] ★ Confirm campaigns are serving and spend is pacing
- [ ] Check conversion action status moves to recording
- [ ] Check campaign status for "Limited by budget"
- [ ] Record launch date, budget, settings and assets
- [ ] ★ Avoid bid strategy, target or budget changes after launch

### First 14 days
- [ ] Days 1–3: check impressions, CTR, CPC and conversion tracking
- [ ] ★ Wait out the "Learning" bid status before judging results
- [ ] ★ Review search terms (or search term insights) every few days and add negatives
- [ ] Check impression share lost to budget and to rank
- [ ] Review asset performance and replace weak assets
- [ ] ★ Compare Google results with backend data (store, CRM or GA4)
- [ ] Adjust targets or budgets in steps, and log each change
- [ ] Day 14: write a short review — what worked, what didn't, next tests

---

## 2. Campaign type items

> Each campaign type opens with: **Use it for · Optimise for · Judge it by**.

### Search (including AI Max)
**Use it for:** capturing people already searching · **Optimise for:** conversions or conversion value · **Judge it by:** CPA, ROAS, impression share

**Before launch**
- [ ] ★ Keep brand and non-brand in separate campaigns
- [ ] Group keywords into tight intent themes, one theme per ad group
- [ ] ★ Build negative keyword lists before launch
- [ ] Write responsive search ads with at least "Good" ad strength; pin only when needed
- [ ] Decide on Search partners; turn off the Display network in Search campaigns
- [ ] If using AI Max: set negatives, brand controls and URL exclusions first
- [ ] Note that Google plans to auto-upgrade Dynamic Search Ads to AI Max (currently planned for February 2027)

**Launch day**
- [ ] Check keywords are eligible and not "Low search volume"

**First 14 days**
- [ ] ★ Review search terms and add negatives
- [ ] Review AI Max text and URL choices if enabled
- [ ] Check Quality Score and lost impression share

### Performance Max
**Use it for:** conversions across all Google channels · **Optimise for:** conversions or value · **Judge it by:** CPA or ROAS, non-brand performance

**Before launch**
- [ ] ★ Add brand exclusions so PMax doesn't take branded searches from your Search campaign
- [ ] Add campaign-level negative keywords (they apply to Search and Shopping inventory only)
- [ ] ★ Build asset groups by theme or landing page, each with a full set of assets including video
- [ ] Add audience signals (customer lists, website visitors) and search themes
- [ ] Set URL expansion rules and exclude pages you don't want (thank-you, careers, blog)
- [ ] Connect the product feed for e-commerce

**Launch day**
- [ ] Check every asset group is approved and serving

**First 14 days**
- [ ] ★ Avoid structural changes during early learning
- [ ] Check the channel performance report to see where spend goes
- [ ] Review search term insights and placements; add exclusions

### Display
**Use it for:** remarketing and low-cost reach · **Optimise for:** conversions or viewable impressions · **Judge it by:** conversions, CPM, placement quality

**Before launch**
- [ ] ★ Choose one clear goal: remarketing or prospecting
- [ ] Set audiences or content targeting; review the optimised targeting setting
- [ ] Upload responsive display ads with several images, logos and headlines
- [ ] ★ Exclude low-quality placements (for example, mobile apps and kids' content) at account level
- [ ] Set a frequency cap

**Launch day**
- [ ] Check ads preview well across sizes

**First 14 days**
- [ ] ★ Review the placements report and exclude junk sites and apps
- [ ] Separate view-through conversions from click conversions when judging results

### Demand Gen
**Use it for:** mid-funnel prospecting on YouTube, Discover and Gmail · **Optimise for:** conversions or clicks · **Judge it by:** CPA and new-customer reach

**Before launch**
- [ ] ★ Use Demand Gen for conversion-focused video (it replaced Video action campaigns)
- [ ] Add image assets and vertical, square and horizontal videos
- [ ] Use customer lists and lookalike segments as audiences where allowed
- [ ] Set channel controls (YouTube only or all channels) on purpose
- [ ] Connect the product feed for e-commerce

**Launch day**
- [ ] Check all ad formats preview correctly on mobile

**First 14 days**
- [ ] ★ Plan a test of several weeks before judging results
- [ ] Compare results with PMax to avoid overlap

### Video (YouTube)
**Use it for:** reach, awareness and consideration · **Optimise for:** reach, views or impressions · **Judge it by:** CPM, CPV, view rate, brand lift

**Before launch**
- [ ] ★ Link the YouTube channel to the ad account
- [ ] Choose the right format: skippable in-stream, non-skippable, Shorts or in-feed
- [ ] ★ Show the brand and key message before viewers can skip
- [ ] Make vertical versions for Shorts
- [ ] Set frequency caps and content suitability
- [ ] Plan measurement (brand lift if eligible, branded search, site traffic)

**Launch day**
- [ ] Check videos are approved and not age-restricted

**First 14 days**
- [ ] Track view rate, CPV and frequency
- [ ] Review where ads appeared and exclude unsuitable channels

### Shopping
**Use it for:** product sales from search · **Optimise for:** conversion value · **Judge it by:** ROAS and product-level profit

**Before launch**
- [ ] ★ Link Merchant Center and fix all feed errors
- [ ] ★ Use strong product titles, correct GTINs and clear images
- [ ] Set shipping and returns in Merchant Center
- [ ] Make sure price and stock match the landing page
- [ ] Group products by margin or priority

**Launch day**
- [ ] Check products show as approved and eligible

**First 14 days**
- [ ] ★ Check product diagnostics for new disapprovals
- [ ] Review search terms and top products; add negatives

### App
**Use it for:** installs and in-app actions · **Optimise for:** installs, in-app actions or value · **Judge it by:** cost per key in-app action, retention

**Before launch**
- [ ] ★ Link Firebase or your MMP and import in-app conversion events
- [ ] ★ Optimise each campaign for one in-app action
- [ ] ★ Set budget to at least 50x target CPI, 10x target CPA (installs) or 15x target CPA (engagement)
- [ ] Upload enough assets for at least "Good" ad strength
- [ ] Set up deep links and follow iOS best practices
- [ ] Run one campaign per country and platform for clean reporting

**Launch day**
- [ ] ★ Confirm installs and in-app events appear in Google Ads and the MMP

**First 14 days**
- [ ] ★ Avoid changes while the campaign is learning
- [ ] Judge on cost per key in-app action, not only cost per install

---

## 3. Business type items

> Each business type opens with: **Key metric · Watch out for**.

### D2C e-commerce
**Key metric:** contribution margin after ad spend · **Watch out for:** RTO, feed errors and festive CPCs

**Before launch**
- [ ] ★ Calculate break-even ROAS using real margin (shipping, discounts, returns)
- [ ] ★ Run a brand Search campaign to protect branded searches
- [ ] Keep the Merchant Center feed accurate on price, stock and offers
- [ ] Decide the COD vs prepaid plan; consider a prepaid incentive to cut RTO
- [ ] Check the sale calendar for festive and marketplace sale days

**Launch day**
- [ ] Place one real order and check the purchase value records correctly

**First 14 days**
- [ ] ★ Track RTO and cancellation rate alongside ROAS
- [ ] Use conversion adjustments for returns or cancellations if possible

### Lead generation
**Key metric:** cost per qualified lead · **Watch out for:** spam leads and offline results not reaching Google

**Before launch**
- [ ] ★ Save the click ID (GCLID) with each lead in your CRM
- [ ] ★ Set up enhanced conversions for leads or offline conversion import
- [ ] Keep new offline conversion actions as secondary for the first 2–3 weeks
- [ ] Add spam protection (reCAPTCHA or phone verification) to forms
- [ ] Set up call tracking if you run call ads or call assets

**Launch day**
- [ ] Confirm the sales team received and contacted the first leads

**First 14 days**
- [ ] ★ Review lead quality with sales every week
- [ ] Move qualified leads to primary once there's enough volume

### Fintech app
**Key metric:** cost per KYC-completed or transacting user · **Watch out for:** verification and policy blocks

**Before launch**
- [ ] ★ Complete Google's Financial Services Verification for India (starts with G2RS third-party verification)
- [ ] ★ Follow Google's financial products policy, including extra rules for loan products
- [ ] Include required disclosures and clear claims with compliance
- [ ] Import deeper events: KYC completed, account funded, first transaction

**Launch day**
- [ ] Confirm KYC and first-transaction events are recording

**First 14 days**
- [ ] ★ Judge on cost per KYC-completed user or first transaction, not installs
- [ ] Check MMP reports for fraud and fake sign-ups

### Health & fitness (wearables and apps like Ultrahuman, Whoop)
**Key metric:** cost per device sale and subscription start · **Watch out for:** health targeting limits and claims

**Before launch**
- [ ] ★ Check whether your products fall under Google's health sensitive category; if so, remarketing, Customer Match and lookalikes aren't allowed
- [ ] ★ Keep health claims accurate and within Google's healthcare policy
- [ ] Track device purchases and app subscriptions as separate conversions
- [ ] Keep the Merchant Center feed accurate for devices and accessories
- [ ] Plan for a longer buying decision with reviews and comparison content

**Launch day**
- [ ] Confirm no ads or audiences are limited by the personalised advertising policy

**First 14 days**
- [ ] Check for new policy limits on ads or audiences
- [ ] Track device sales and subscription starts separately

---

## 4. Notes for global campaigns
- **EEA and UK:** set up Consent Mode v2 and a consent banner before running ads.
- **Financial services:** verification is needed separately for each country that requires it.
- **Structure:** run separate campaigns by country when budget, pricing or rules differ.
- **Merchant Center:** set up shipping, currency and feeds for each target country.

---

## Notes for the page build (not shown on the page)
- Same layout as the Meta tab: filters, ★ toggle, progress count per phase, summary line per block.
- Save progress separately for each campaign type + business type combination.

---

## Sources (for your reference)
- Google Ads Help: bid strategy learning period, App campaign best practices, enhanced conversions for leads checklist
- Google Ads Policy Help: Financial Services Verification (India), restricted targeting in personalised advertising
- Google Ads Help: Video Action Campaigns upgraded to Demand Gen
- Google Ads announcements: PMax campaign-level negative keywords (10,000 limit)
- Google Ads Developer Blog via PPC Land: DSA to AI Max auto-upgrade moved to February 2027
- Practitioner coverage: Search Engine Land, PPC Land (PMax brand exclusions, AI Max setup)
