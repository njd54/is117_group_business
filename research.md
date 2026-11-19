# CampusFuel — Abhinav’s Research Contribution

**Contributor:** Abhinav Anipeddi · **GitHub:** aka223-ui

**Course:** IS117-007 · Group Business Research

**Research date:** November 19, 2026 (Eastern)

**Status:** AI-assisted research draft for teammate review. No interviews, prototype tests or reviewer retry are claimed. Prepared on the date shown, not backdated.

## Research index

[Question](#1-question-and-scope) · [Sources](#2-original-sources-and-comparison) · [Alternatives](#3-two-positions) · [Personas](#4-two-persona-hypotheses) · [Brand](#5-brand-design-and-honest-persuasion) · [Decision trace](#6-research-to-feature-trace) · [Contributions](#7-contributions-and-proposed-cross-review) · [Review](#8-review-request-and-evidence-history)

Shared repository: https://github.com/njd54/is117_group_business

Teammate’s existing research: [Nicholas’s record](docs/njd54-research.md).

## 1. Question and scope

**Question:** How should a fictional student-focused café explain pickup ordering and a possible study-space offer without promising affordability, seating or availability that has not been established?

CampusFuel’s existing concept combines food, coffee and study space. Nicholas’s record covers Starbucks/Dunkin’, Persona A and convenience. This contribution adds Panera, Persona B, a study-space alternative and an amenity-information decision. Official sources were rechecked rather than treating AI suggestions or the teammate’s document as primary evidence.

The three businesses are relevant café/category and workflow references. This does not establish local competition with an operating CampusFuel café: no actual CampusFuel location, stock or capacity is established.

## 2. Original sources and comparison

Original company-page text retrieved **November 19, 2026**. Publication dates are separate from check dates. Observations describe company-published information, not independently measured service performance.

| ID / business | Original source / publication date | Observed evidence | Interpretation for CampusFuel |
|---|---|---|---|
| R1 — Starbucks | [Making it easier to plan your Starbucks visit](https://about.starbucks.com/press/2026/making-it-easier-to-plan-your-starbucks-visit/) · April 22, 2026 | Describes scheduled mobile pickup, with pickup-time selection during order review and location-dependent availability. | Explore a visible review/timing step; do not assume our concept has comparable scheduling capacity. |
| R2 — Dunkin’ | [Mobile app](https://www.dunkindonuts.com/mobile-app/) · publication date not stated | Promotes order-ahead, customization and saved favorites. | Show selected options in the order summary; saved favorites can be deferred. |
| R3 — Panera | [Free Wi-Fi](https://www.panerabread.com/en-us/services/wifi.html) · publication date not stated | Addresses studying/working and explains guest Wi-Fi, noting possible location restrictions. | Study information may help, but amenities need explicit status rather than assumed guarantees. |
| R3b — Panera (supporting page, same business) | [Services & Amenities](https://www.panerabread.com/en-us/services.html) · publication date not stated | Groups pickup, delivery, Wi-Fi and other services under named headings. | Separate café information from the ordering task. This does not demonstrate student demand or available seats. |

**Comparison:** Starbucks emphasizes pickup timing; Dunkin’ emphasizes convenient/custom repeat ordering; Panera presents café services and connectivity. Together they suggest distinct ordering and café-information sections, with clear limits. They do not prove which position CampusFuel customers prefer.

**Verification limits:** company text was read; rendered colors/fonts, real app tasks, prices, customer satisfaction, waiting times and seating were not measured. Panera extraction included shared account/error UI strings; only explicit service sections support these observations, not a claim that its live service was failing. No screenshots or interviews are invented.

## 3. Two positions

**A — Between-class convenience:** help students inspect menu prices, select options and review a simulated pickup request. Benefit hypothesis: a compact flow suits a short class break. Risk: “fast” or “affordable” may imply unsupported service performance or savings.

**B — Study-break clarity:** explain proposed amenities before a student decides whether to visit or browse food. Benefit hypothesis: practical information helps plan a longer break. Risk: a study-space promise requires evidence about real hours, noise, seating and connectivity that this concept lacks.

**Proposed recommendation for team review:** keep A as the primary menu task and borrow B’s clear amenity/limitations section. Ordering sources provide concrete workflow ideas; Panera supports explaining amenities, not inventing seat reservations. The final group decision is pending. A walkthrough could change this recommendation if readers consistently need café context first.

## 4. Two persona hypotheses

These are fictional design hypotheses, **not interviewed customers or observed behavior**. No customer quotes, sample or demographic statistics are claimed.

| | Persona A — between-class buyer | Persona B — student planning a study break |
|---|---|---|
| Situation | Short class break; wants food or a drink | Longer gap; considering somewhere to sit and work |
| Goal | Understand choices, total and pickup status | Understand what café information is actually established |
| Concern | Too many steps or unclear order status | Assuming guaranteed seating, quietness or Wi-Fi |
| Information needed | Prices, options, summary and honest demo status | Supported location/hours information, amenity status and limits |
| Evidence versus assumption | Nicholas’s existing persona; ordering sources suggest a workflow, not this person’s behavior | Panera addresses studying and Wi-Fi; relevance to CampusFuel users remains unvalidated |

**Audience recommendation:** Persona A guides the primary task; Persona B cross-checks supporting information. Neither establishes demand, purchasing power or a preferred price.

## 5. Brand, design and honest persuasion

**Source-language interpretations:** Starbucks’ instructions suggest practical/helpful communication; Dunkin’s action benefits suggest an energetic voice; Panera’s guest Q&A suggests welcoming help. These are editorial interpretations, not official archetypes. Retrieved headings support information-organization observations; historical style, colors and typography were not visually verified.

**Proposed CampusFuel brief:** “Clear choices for your next campus break.” Everyperson character; friendly, clear, practical voice. Translate this into readable menu cards, visible example prices, distinct café information and unambiguous demo actions. No agreed group logo/palette or Brand Studio file was found here. Reuse the team’s actual agreed assets when supplied; do not silently apply the individual T-shirt identity to the café. Slogan and visual decisions remain proposals.

- **Reciprocity:** a free “Before your study break” checklist helps visitors confirm hours, amenities and pickup status without signup. No measured conversion effect is claimed.
- **Liking:** welcoming, student-relevant plain language may make choices approachable. This does not establish that real customers identify with the brand.

No invented testimonials, scarcity, discounts, sustainability, nutrition/allergen guarantees, seat counts, quietness or service-speed claims. Example menu prices and pickup slots must say fictional/demo. Do not imply real payment, fulfillment, guaranteed pickup or a reserved seat.

## 6. Research-to-feature trace

| Trace | Observation / hypothesis | Proposed decision and story | Observable check — planned, not run |
|---|---|---|---|
| F1 → D1 → C1 | R3 explains Wi-Fi and exceptions. Study-break readers may need clear amenity status. | Add “Café & study information” distinguishing proposed, confirmed and unknown details. As a student, I want to know what is established so I do not assume a seat or Wi-Fi guarantee. | A peer finds the section and explains which amenities are unconfirmed and whether a seat is reserved. Record the actual answer before coaching; revise if they infer a guarantee. |
| F2 → D2 → C2 | R1 explains pickup selection during review; R2 promotes customization. | Show selected item/options and clearly labeled demo pickup choice in one summary. As a buyer, I want to check choices before submission. | Future prototype: fictional $4 drink plus $1 option displays $5 plus any separately labeled example fees, preserves the slot and says demo only. Missing required choices block submission. |
| F3 → D3 → C3 | R3b groups services; R2 uses short benefits. Ordering and café information may need separate paths. | Compare menu-first with café-information-first navigation using identical content. | Give the same menu/amenity task in both future versions. Record navigation errors and understanding of limits. A preference alone does not prove speed or sales gains. |

**Affordability remains unproven:** visible prices support inspection, not a claim that CampusFuel is cheaper or affordable. Do not copy competitor prices without location/date context.

## 7. Contributions and proposed cross-review

| Member evidenced in repository | Documented research/decision contribution | Review evidence and next task |
|---|---|---|
| Nicholas Duarte — njd54 | Existing file covers Starbucks/Dunkin’, Persona A, convenience and ordering checks. | Issue #1 records his response to feedback. Establish completion from actual change/retry evidence. |
| Abhinav Anipeddi — aka223-ui | This AI-assisted contribution adds Panera, source rechecks, Persona B, alternatives, amenity-status trace and proposed checks. Recommendation awaits team discussion. | [Existing review comment on Nicholas’s research](https://github.com/njd54/is117_group_business/issues/1#issuecomment-7011649217) asks for a specific ordering sequence and mobile/desktop checks. Nicholas’s review of this new file is pending. |

**Proposed work split, not completed or team-approved:** Abhinav owns amenity/checklist content and responsive presentation; cross-reviews validation and receipt language. Nicholas owns menu/options/summary logic; cross-reviews information accuracy and navigation. Both share integration/retesting and should compare effort before agreeing the split. Any additional members must add their actual names/usernames and contributions; none are invented here.

## 8. Review request and evidence history

**Reviewer task:** open R3’s original Wi-Fi page, locate its availability caveat, and follow **F1 → D1 → C1**. Is the inference supported? Will the proposed check reveal mistaken amenity/seat guarantees? File an issue with the source, specific gap, why it matters and a useful next step.

Record feedback → implement/investigate/defer/decline decision with reason → linked documentation/code commit referencing the issue → actual verification → reviewer retry before closing. Leave unfinished work open with its next step.

**Current status:** this file is ready for review. No incoming review, retry or prototype result is claimed. [Issue #1](https://github.com/njd54/is117_group_business/issues/1) concerns Nicholas’s record, not a review of this file. It links a different filename from the committed docs/njd54-research.md; use the real link above. Its placeholder revision-commit/retry fields do not establish a complete evidence chain. This contribution does not edit or reopen that teammate-owned issue.

## 9. AI assistance and remaining work

AI retrieved official sources on November 19, read Nicholas’s committed research, drafted this contribution and checked its structure/local teammate-file link. No purchase, sign-in, app task, interview, café visit, reviewer retry or attendance verification was performed. Abhinav should review the recommendation and explain F1 → D1 → C1; AI assistance does not demonstrate independent student understanding.

This Markdown artifact does not prove a separate published documentation site or prototype exists. The team still needs to integrate member records, agree the audience/brand/work split, link the shared documentation site and record actual review/retry. GitHub does not submit Canvas coursework. No new group issue quota is inferred. This work is honestly dated after the original November 17 checkpoint.
