# CLAUDE.md

Guidance for Claude Code when working in this repository.

## Purpose

Chethan Shankar's personal portfolio, published via GitHub Pages at
`https://chethan4062.github.io`. Its only job is to support **applications for
full-time performance marketing roles**.

This is **not** a freelance or agency site. Do not add:

- "Hire me", "Let's work together", "Got a project in mind?" or similar CTAs
- Contact forms, project-enquiry wording, service menus, pricing or packages
- Any copy that addresses the reader as a prospective client

Write for a hiring manager or recruiter, not a buyer. The contact section reads
"Open to full-time performance marketing roles. Happy to connect."

## Design system

- **Fonts:** Instrument Serif (headings, large numbers) + DM Sans (everything else),
  loaded from Google Fonts. Headings are `font-weight: 400` — Instrument Serif has
  one weight.
- **Colours:** background `#FAFAF8`, text `#1A1A1A`, accent `#E8E4DF`.
  Supporting tokens already used across pages: card `#FFFFFF`, muted `#6B6B6B`,
  border `#E5E3DE`, highlight `#2C2C2C` (dark sections), warm `#C8A882`
  (eyebrows, accents), warm-bg `#F5EFE8`.
- Declare these as CSS custom properties on `:root` in every page.
- **Minimal.** Restrained type, thin borders, generous whitespace, no shadows
  beyond a subtle hover lift, no gradients, no decorative illustration.
- **No emojis.** Anywhere — not in page copy, not as icons, not in commit messages.
- **Responsive.** Must work at 390px with no horizontal scroll. Multi-column grids
  collapse to one column; the homepage nav links hide below 768px.
- **Every page is a single self-contained HTML file** with its CSS in one `<style>`
  block and its JS in one `<script>` block. No build step, no bundler, no shared
  stylesheet, no framework. Duplicated CSS between pages is expected and fine.

## Repository layout

| Path | What it is |
| --- | --- |
| `index.html` | Homepage |
| `case-study-d2c-skincare.html` | Selected Work — campaign I managed (client anonymised) |
| `case-study-minimalist.html` | Brand Teardown |
| `case-study-mamaearth.html` | Brand Teardown |
| `case-study-cultfit.html` | Brand Teardown |
| `case-study-cred-phonepe.html` | Brand Teardown — CRED vs PhonePe, 12 ads |
| `tools.html` | Tools — Marketing Calculators (ROAS & break-even, CAC & LTV, budget pacing). Tabs are addressed by hash: `#roas`, `#cac`, `#pacing` |
| `playbooks.html` | Playbooks — Campaign Launch Checklist. Views are addressed by hash: `#<platform>/<objective-or-campaign-type>/<business-type>`, e.g. `#meta/sales/d2c` |
| `content/playbooks/*.md` | Source markdown for the checklist content. Not published; the page carries its own copy of the items |
| `case-study-workout-app.html` | Workout Session Sequencer write-up; links to `workout/index.html`. Not currently linked from the homepage |
| `workout/index.html` | Live workout app demo |
| `templates/` | Page templates. `noindex`, never linked from the site |
| `*.png`, `workout-shots/` | Case study images |

## Homepage sections

In page order, with the ids the nav links to:

| Section | id | Nav label |
| --- | --- | --- |
| Hero | `home` | — |
| About | `about` | — |
| Skills & Tools | `skills` | — |
| Selected Work | `work` | Work |
| Brand Teardowns | `teardowns` | Teardowns |
| Tools | `tools` | Tools |
| Playbooks | `playbooks` | Playbooks |
| AI Lab | `ai-lab` | AI Lab |
| Experience | `experience` | Experience |
| Certifications & Education | `certifications` | — |
| Contact | `contact` | Contact |

Nav is: name on the left, those seven links, LinkedIn button on the right. Keep
section order matching nav order. Every other page carries `Tools` and
`Playbooks` links (to `tools.html` and `playbooks.html`) in its nav as well.

## Section rules

- **Selected Work** — campaigns I personally managed. First person ("I scaled…",
  "I built…"). **Clients must be anonymised and non-identifiable.** No brand name,
  domain, founder names, branded product or ingredient names, verbatim customer
  reviews, exact review or customer counts, named marketplaces, or named vendors.
  Use "a D2C skincare brand" / "the brand" / "a pharma-background founder" and
  generic product descriptions. Every such page keeps a confidentiality note in the
  footer stating that client name and product details have been anonymised.
  Competitor brands that are only being compared against (Minimalist, Mamaearth,
  Dot & Key, Plum, The Ordinary) may be named.
- **Brand Teardowns** — third-person analysis of other companies' performance
  marketing, built from public information. Never imply I worked on them. Name the
  brand freely; cite public figures only.
- **AI Lab** — my own AI tools and workflows. Each card carries an `In Progress`
  badge and no link until the thing is actually finished and has a page to point at.
  Use the `.cases-grid` / `.case-card` markup so cards can be added by copy-paste.
- **Tools** — free calculators and utilities for performance marketers. **Every tool
  must be plain HTML and vanilla JavaScript in a single self-contained file: no
  libraries, no API keys, no external calls (the Google Fonts stylesheet is the only
  external resource, as on every page), no cookies, no `localStorage` or any other
  data storage, no analytics.** Everything runs in the browser on the values the
  visitor types. Invalid, empty or negative inputs show `—`, never `NaN` or
  `Infinity`. Zero is also treated as invalid, except where zero is a genuine state
  (Revenue from Ads, Spend So Far), which compute normally. Money is formatted with
  `en-IN` (`₹1,20,000`). Each tool page reuses the homepage nav and footer and gets
  a card in `#tools`.
- **Playbooks** — checklists and process guides for running campaigns. The content
  lives in `content/playbooks/*.md`: **when the content changes, edit the markdown
  file first, then update the page's data object to match.** Never let the two drift.
  **Keep item ids stable** (`m-core-before-01`, `g-search-launch-02`) so saved
  progress survives edits — add new ids at the end of a phase rather than
  renumbering. Update the "Last updated" date on any content change. Items marked
  `★` in the markdown become `essential: true` in the data with the `★` stripped
  from the text. The markdown's "Notes for the page build" sections and any review
  tips are never shown on the page; "Sources" appears as a collapsed section with
  the words "for your reference" dropped.

## Facts to keep consistent everywhere

- Name: **Chethan Shankar**
- Title: **Performance Marketer**, open to full-time roles
- Location: Bengaluru, India
- **4+ years** in performance marketing
- **₹1Cr+** monthly ad spend managed
- **16X** organic traffic growth
- **10X** app downloads increased
- Email: `chethan4062@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/chethanshankar` (always `target="_blank"`
  with `rel="noopener noreferrer"`)
- Selected Work campaign figures, which must match between the homepage card and
  the case study: ₹30L to ₹60L/month spend (₹50L Meta, ₹10L Google), 3x blended
  ROAS, 35% CAC reduction, 63% AOV increase, ₹1.8 Cr monthly revenue

**Never invent numbers, metrics, claims, tools, certifications or job details that
are not already on the site or in the resume.** If a figure is needed and no source
exists, ask rather than estimate. When a shared fact changes, update every page that
carries it.

## Hard rules

- **Never show a phone number anywhere on the site**, in any page, meta tag,
  structured data or asset.
- **No gaming, gambling or real-money gaming content anywhere on the site** — not as
  a case study, client, example, checklist item or passing mention.
- **Storage exception for playbooks.** Tools store nothing, but playbook tick boxes
  may use `localStorage` for one visitor's own progress: key
  `checklist:v1:<platform>:<objective>:<business>`, every read and write wrapped in
  `try/catch` so the page still works when storage is unavailable, and nothing ever
  sent to a server.
- No emojis.
- No resume link until asked — see below.
- Keep `templates/` out of the site: `noindex` stays, and no page links to them.

## Planned for later, not live yet

A downloadable resume at `Chethan-Shankar-Resume.pdf` (repo root), linked from the
nav, hero and contact sections.

**Do not add it, or any link or button pointing at it, until Chethan explicitly
asks.** When that happens: the PDF must not contain his phone number, and the link
should open in a new tab.

## How to add a new item

1. Copy the matching template:
   - A campaign or teardown → `templates/case-study-template.html`
   - An AI Lab project → `templates/ai-lab-template.html`
   - A calculator or utility → a new single-file page modelled on `tools.html`
     (or a new tab inside it), following the Tools rule above
   - A playbook or checklist → the markdown in `content/playbooks/` first, then a
     page modelled on `playbooks.html`, following the Playbooks rule above
2. Save it in the repo root as `case-study-<slug>.html` or `ai-lab-<slug>.html`.
3. Replace every `[PLACEHOLDER]`, set `<title>` and the meta description, and
   **remove the `noindex` meta tag**.
4. Add a card to the matching homepage section (`#work`, `#teardowns`, `#tools`,
   `#playbooks` or `#ai-lab`) by copying an existing `.case-card` in that grid.
   Teardown and Work cards are `<a>` elements with three metrics and a "Read case
   study" arrow; Tools and Playbooks cards are `<a>` elements with a tag, title,
   description and an "Open tool" / "Open playbook" arrow; AI Lab cards are `<div>`
   elements with an `In Progress` badge and no metrics.
5. Check the back-link to `index.html` and any footer cross-links resolve.

## Before finishing a change

- Verify internal links and anchors resolve across all HTML files.
- Check the page at desktop and 390px width.
- Confirm no emoji, no phone number, no freelance or hire-me language, no gaming or
  gambling content, and no new unsourced numbers were introduced.
