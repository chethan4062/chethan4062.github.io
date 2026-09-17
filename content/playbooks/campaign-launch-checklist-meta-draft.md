# Campaign Launch Checklist — Meta Ads (Draft v2 for review)

**Page intro:** A launch checklist for Meta and Google Ads, built from platform documentation and industry best practice. India-first, with notes for global campaigns. Tick items as you go; progress is saved only in your browser.

**Last updated:** September 2026

---

## How to read this checklist

- **Pick two filters:** Campaign objective + Business type.
- **You see three blocks:** Core (every campaign) → Objective → Business type.
- **Each block has three phases:** Before launch → Launch day → First 14 days.
- **★ = essential.** Skipping it usually breaks tracking, wastes budget or breaks policy. A "Show essentials only" toggle will show just these.
- **Every item starts with an action** and fits on one line.

**Which objective fits which business?**

| Business type | Usually runs |
|---|---|
| D2C e-commerce | Sales, Traffic, Awareness |
| Lead generation | Leads, Engagement (WhatsApp) |
| Fintech app | App promotion, Leads |
| Health & fitness | Sales, App promotion, Awareness |

---

## 1. Core — every Meta campaign

### Before launch

**Account**
- [ ] ★ Verify the business portfolio and turn on two-factor authentication
- [ ] Give admin access to at least two people
- [ ] ★ Set ad account time zone and currency (INR) correctly — hard to change later
- [ ] Add a backup payment method and your GSTIN for GST invoices
- [ ] Verify your domain in Business settings
- [ ] Connect the Facebook Page and Instagram account

**Tracking**
- [ ] ★ Install the Meta Pixel and check events with Meta Pixel Helper
- [ ] ★ Set up Conversions API for the same key events
- [ ] ★ Match event name and event ID in Pixel and Conversions API to avoid double counting
- [ ] Send hashed email and phone to improve Event Match Quality
- [ ] ★ Pass value and currency (INR) with purchase and lead events
- [ ] Confirm every key event in the Test Events tool
- [ ] Check your data source category in Events Manager (health and finance can be restricted)
- [ ] ★ Add UTM parameters to every ad using one naming format
- [ ] Confirm campaign traffic shows in GA4 or your analytics tool

**Goals & budget**
- [ ] ★ Set target, acceptable and stop-loss CPA or ROAS — use the [Marketing Calculators](tools.html)
- [ ] ★ Check the budget can reach around 50 optimisation events a week per ad set; if not, pick a higher-volume event or merge ad sets
- [ ] Choose the attribution setting on purpose and note it

**Setup**
- [ ] ★ Match the objective to the real business goal
- [ ] Use fewer ad sets with more creatives in each
- [ ] Set Advantage+ audience controls: location, minimum age, language, exclusions
- [ ] Review placement settings — Meta is testing removal of placement exclusions; use value rules or account-level controls if needed
- [ ] ★ Review each Advantage+ creative enhancement; turn off any that change brand text, claims or offers
- [ ] Set brand safety block lists and inventory filter
- [ ] Apply one naming convention to campaigns, ad sets and ads

**Creative & landing page**
- [ ] ★ Prepare several different creative concepts (angle, format, hook), not small variations
- [ ] Make 9:16 and 4:5 versions with text inside safe zones
- [ ] Put the video hook in the first 3 seconds and add captions
- [ ] ★ Check copy, offer and claims against Meta Advertising Standards
- [ ] Match the ad message to the landing page headline and offer
- [ ] ★ Test the landing page on mobile: speed, forms and checkout
- [ ] Confirm customer lists have proper consent (India's DPDP consent rules are enforceable from 13 May 2027)

**Final check**
- [ ] Preview ads on a real phone in Feed, Stories and Reels
- [ ] ★ Click every link
- [ ] Check dates, schedule and budget
- [ ] ★ Complete one test conversion and see it in Events Manager

### Launch day
- [ ] ★ Confirm all ads are approved; fix or appeal rejections
- [ ] ★ Confirm delivery has started and spend is pacing
- [ ] ★ Check events arrive with correct values and no duplicates
- [ ] Check UTMs show correctly in analytics
- [ ] Assign someone to moderate and reply to comments
- [ ] Record launch date, budget, settings and creatives
- [ ] ★ Avoid significant edits after launch

### First 14 days
- [ ] Days 1–3: check delivery, CPM, CTR and cost per result
- [ ] Add "Last significant edit" and "Optimization events" columns to track learning
- [ ] ★ Avoid restarting learning: pausing, or changing optimisation event, audience or creative, resets it; big budget or bid changes can too
- [ ] If cost per result is far above target, check tracking, landing page and creative first
- [ ] Day 7+: pause clearly weak ads; add new creatives in batches
- [ ] Watch frequency and negative feedback for creative fatigue
- [ ] ★ Compare Meta results with backend data (store, CRM or GA4)
- [ ] Scale budget in steps once results are stable, and log each change
- [ ] Day 14: write a short review — what worked, what didn't, next tests

---

## 2. Objective items

> Each objective opens with a quick summary: **Use it for · Optimise for · Judge it by**.

### Awareness
**Use it for:** new launches and brand recall · **Optimise for:** reach or ad recall lift · **Judge it by:** reach, frequency, CPM

**Before launch**
- [ ] ★ Choose the goal: reach, impressions or ad recall lift
- [ ] Set a frequency cap that suits the campaign length
- [ ] Decide how to measure impact (brand lift study if eligible, branded search, direct traffic)
- [ ] Show the brand clearly in the first seconds of the creative

**Launch day**
- [ ] Check reach and frequency are delivering as planned

**First 14 days**
- [ ] Track reach, frequency, CPM and ThruPlays against plan
- [ ] Check whether branded search or direct traffic moved

### Traffic
**Use it for:** sending visitors to content or pages · **Optimise for:** landing page views · **Judge it by:** cost per landing page view, engaged sessions

**Before launch**
- [ ] ★ Optimise for landing page views, not link clicks (needs a working Pixel)
- [ ] Make sure the page loads fast enough for clicks to become visits

**Launch day**
- [ ] Check landing page views are recording, not only link clicks

**First 14 days**
- [ ] Compare link clicks with landing page views to spot load-time drop-off
- [ ] Check engaged sessions and bounce rate, not just CPC

### Engagement
**Use it for:** conversations, video views, post engagement · **Optimise for:** messages or ThruPlays · **Judge it by:** cost per conversation, conversations that convert

**Before launch**
- [ ] ★ Pick the conversion location: messages, video views, on-ad engagement or calls
- [ ] ★ For click-to-WhatsApp ads: connect the WhatsApp Business number and set greeting and quick replies
- [ ] Assign someone to reply to messages quickly
- [ ] Use existing posts where social proof helps

**Launch day**
- [ ] ★ Test one message conversation end to end

**First 14 days**
- [ ] Track cost per conversation and reply time
- [ ] Check how many conversations turn into leads or sales

### Leads
**Use it for:** enquiries, sign-ups, bookings · **Optimise for:** leads or conversion leads · **Judge it by:** cost per qualified lead

**Before launch**
- [ ] ★ Choose the lead source: instant form, website, messaging or calls
- [ ] For instant forms, use the higher-intent form type and add qualifying questions
- [ ] Add a privacy policy link and a thank-you screen with next steps
- [ ] ★ Send leads automatically to your CRM or sheet, and test with Meta's lead ads testing tool
- [ ] Connect Conversions API for CRM to use the Conversion Leads goal (instant forms only)
- [ ] Download or sync leads regularly — Meta keeps them for a limited time

**Launch day**
- [ ] ★ Confirm the first real leads reach the CRM and the sales team

**First 14 days**
- [ ] ★ Track cost per qualified lead, not just cost per lead
- [ ] Send lead stages back to Meta if CRM integration is set up

### App promotion
**Use it for:** installs and in-app actions · **Optimise for:** installs, app events or value · **Judge it by:** cost per key in-app event, early retention

**Before launch**
- [ ] ★ Integrate the Meta SDK or an MMP (AppsFlyer, Adjust, Branch)
- [ ] ★ Set up and validate key in-app events (sign-up, purchase, subscription)
- [ ] Set up iOS measurement with your MMP
- [ ] Choose the optimisation: installs, app events or value
- [ ] Match the app store listing to the ad promise and test deep links

**Launch day**
- [ ] ★ Confirm installs and in-app events appear in both Meta and the MMP

**First 14 days**
- [ ] ★ Judge on cost per key in-app event, not only cost per install
- [ ] Check MMP fraud reports

### Sales
**Use it for:** online purchases · **Optimise for:** purchase or purchase value · **Judge it by:** CPA and ROAS against break-even

**Before launch**
- [ ] ★ Connect the catalog and fix product feed errors
- [ ] Track Add to Cart and Initiate Checkout as well as Purchase
- [ ] Define existing-customer and engaged-audience segments in Advantage+ settings

**Launch day**
- [ ] ★ Confirm purchases record with correct values

**First 14 days**
- [ ] ★ Compare ROAS and CPA with break-even, not just platform ROAS
- [ ] Check the new vs returning customer split
- [ ] Check catalog ads for disapproved or out-of-stock products

---

## 3. Business type items

> Each business type opens with: **Key metric · Watch out for**.

### D2C e-commerce
**Key metric:** contribution margin after ad spend · **Watch out for:** RTO and festive-season CPMs

**Before launch**
- [ ] ★ Calculate break-even ROAS using real margin (shipping, discounts, returns)
- [ ] Decide the COD vs prepaid plan; consider a prepaid incentive to cut RTO
- [ ] Show shipping, returns and payment options (UPI, cards, COD) on the product page
- [ ] Check the sale calendar — festive and marketplace sale days usually raise CPMs
- [ ] Show reviews and ratings on the landing page

**Launch day**
- [ ] Place one real order (prepaid and COD) and check it end to end

**First 14 days**
- [ ] ★ Track RTO and cancellation rate alongside ROAS
- [ ] Check AOV and top-selling products from ads

### Lead generation
**Key metric:** cost per qualified lead · **Watch out for:** junk leads and slow follow-up

**Before launch**
- [ ] ★ Agree on what a qualified lead is with the sales team
- [ ] Add phone/OTP verification or qualifying questions to cut junk leads
- [ ] ★ Set a response-time target (for example, same-day call)

**Launch day**
- [ ] Confirm the sales team received and contacted the first leads

**First 14 days**
- [ ] ★ Review lead quality with sales every week
- [ ] Track contact rate, junk-lead share and cost per closed deal

### Fintech app
**Key metric:** cost per KYC-completed or transacting user · **Watch out for:** regulatory rules and fake sign-ups

**Before launch**
- [ ] ★ For securities and investment ads in India, verify payer and beneficiary with SEBI registration (or the alternative if exempt)
- [ ] ★ Include required disclosures and clear claims (returns, approvals) with compliance
- [ ] Track deeper events: KYC completed, account funded, first transaction
- [ ] Check whether a Special Ad Category applies in your target countries

**Launch day**
- [ ] Confirm KYC and first-transaction events are recording

**First 14 days**
- [ ] ★ Judge on cost per KYC-completed user or first transaction, not installs
- [ ] Check MMP reports for fraud and fake sign-ups

### Health & fitness (wearables and apps like Ultrahuman, Whoop)
**Key metric:** cost per device sale and subscription start · **Watch out for:** health-data event restrictions and claims

**Before launch**
- [ ] ★ Check your data source category; plan for restricted lower-funnel events if flagged
- [ ] ★ Avoid ads that imply a user's health condition; keep claims accurate and supportable
- [ ] Track device purchases and app subscriptions as separate events
- [ ] Prepare reviews, comparisons and retargeting content for a longer buying decision
- [ ] Set shipping countries and pricing per market for global launches

**Launch day**
- [ ] Confirm no key events show as blocked in Events Manager

**First 14 days**
- [ ] Check for any new event restrictions
- [ ] Track device sales and subscription starts separately

---

## 4. Notes for global campaigns
- **EU:** payer and beneficiary details are required for all ads targeting the EU, and user consent is needed before tracking fires.
- **Other countries:** some (for example, Singapore and Taiwan) need extra advertiser details — check before targeting.
- **Structure:** run separate campaigns by country or region when budget, pricing or rules differ.
- **Reporting:** keep separate ad accounts per currency or region if needed.

---

## Notes for the page build (not shown on the page)
- Show a progress count on each phase header (for example, "Before launch · 8/32").
- Add a "Show essentials only" toggle for ★ items.
- Show the objective/business summary line at the top of each block.
- Save progress separately for each objective + business type combination.
- Keep the same design system, tabs and card style as the calculators page.

---

## Sources (for your reference)
- Meta Conversions API best practices and deduplication — developers.facebook.com
- Meta SEBI verification for India securities ads — developers.facebook.com (June 2025)
- Meta Conversions API for CRM (Conversion Leads) — developers.facebook.com
- DPDP Rules 2025 timeline — legal summaries (compliance deadline 13 May 2027)
- Practitioner coverage: Jon Loomer, PPC Land, Social Media Today (placement exclusions test, Advantage+ changes)
