# CampusFuel — Combined Group Business Research

**Course:** IS117-007 — Group Business Research  
**Group members:** Nicholas Duarte (`njd54`) and Abhinav Anipeddi (`aka223-ui`)  
**Research records dated:** November 19, 2026  
**Status:** Combined documentation of two individual research contributions. Group decision and prototype tests are not independently confirmed.

## Group synthesis

**Business concept:** CampusFuel is a fictional café for college students, combining menu and pickup information with transparent café/study-space information.

### Three-site comparison

| Reference | Evidence from team research | Design implication |
|---|---|---|
| [Starbucks](https://about.starbucks.com/press/2026/making-it-easier-to-plan-your-starbucks-visit/) | Scheduled mobile pickup at participating locations | Consider a clearly labeled pickup-time choice and review step |
| [Dunkin'](https://www.dunkindonuts.com/mobile-app/) | Ordering ahead, customization, saved favorites | Display item options, quantities and updated totals; defer favorites if needed |
| [Panera Bread](https://www.panerabread.com/en-us/services/wifi.html) | Publishes Wi-Fi/study information with location-dependent limitations | Clearly distinguish known, unknown and proposed amenities |

These company-published sources describe their services, not measured student demand or proof that CampusFuel could provide them.

### Two positioning approaches

- **A — Between-class convenience (Nicholas):** A mobile-first menu with visible example prices, customization, an order summary, and simulated pickup selection. Risk: claiming speed or affordability without evidence.
- **B — Study-break clarity (Abhinav):** Useful café and study-space information with explicit uncertainty around Wi-Fi, seating, hours and reservations. Risk: implying unverified amenities are guaranteed.

**Proposed combined direction, awaiting both members' approval:** Make the menu-to-pickup review the primary customer task and offer a separate café/study-information section. This combines the concrete ordering workflow with truthful amenity disclosure. It is not yet a tested customer preference.

### Two audience hypotheses

| Persona | Situation | Proposed need | Evidence limitation |
|---|---|---|---|
| **A — Alex, between-class buyer** (Nicholas) | Short break between classes | See prices, customize an item, review total and pickup time | Fictional; no student interview or timed task |
| **B — Study-break planner** (Abhinav) | Longer gap between classes | Understand café amenities and what is or isn't confirmed | Fictional; no evidence of actual CampusFuel seating or Wi-Fi |

### Primary customer task and planned checks

**Proposed task:** Find an item, inspect its example price, customize it, check quantity and total, choose a *demo* pickup time, and review the order without implying a real purchase or guaranteed pickup.

1. At desktop and mobile widths, locate the menu and select a sample item with a stated base price.
2. Add an option and verify the item, option, quantity and recalculated total in the summary; show example taxes/fees separately if used.
3. Choose a demo pickup time and verify the same time appears in the review and any implemented confirmation.
4. Verify that missing required choices prevent proceeding and that all actions clearly indicate a fictional/demo flow.
5. In the separate café/study section, identify which amenities are proposed, confirmed or unknown; confirm there is no implied seat reservation or Wi-Fi guarantee.
6. Record actual results, screen sizes, accessibility/keyboard observations and failures **only after** a prototype exists.

### Evidence and collaboration

- **Nicholas:** Starbucks/Dunkin' comparisons, Persona A, convenience positioning, ordering acceptance criteria, peer-review revision in [Issue #1](https://github.com/njd54/is117_group_business/issues/1), [revision commit](https://github.com/njd54/is117_group_business/commit/4228090be62e2b6e78cfe0f2116a9fbacf667378).
- **Abhinav:** Panera comparison, Persona B, study-space positioning, amenity-status acceptance checks, and source limitations. Any separate review/retest must be supported by its own issue and commit evidence.
- **Team confirmation still needed:** Both members approve the combined direction, verify links and record any final cross-review. No prototype usability test, real café operation, or interviews are claimed.

**AI assistance:** ChatGPT helped organize and combine the member-authored research records and draft the synthesis. Members should check the combined interpretations against their source documents and agree to the proposed direction.

---

## Appendix A — Nicholas Duarte: full individual research record

# CampusFuel — Individual Research Contribution

**Course:** IS117-007 — Group Business Research  
**Contributor:** Nicholas Duarte  
**GitHub:** njd54  
**Research date:** November 19, 2026  
**Status:** Individual research documented; peer feedback incorporated into planned checks; prototype verification pending

## 1. Business Concept

CampusFuel is a fictional café designed for college students who want affordable food, coffee, and a convenient place to study.

The proposed website will help students browse the menu, compare prices, and arrange pickup orders between classes.

**Research question:** How can CampusFuel create a convenient ordering experience for college students by learning from established café and coffee businesses?

## 2. Competitor Research

### Competitor 1 — Starbucks

**Website:** https://www.starbucks.com/  
**Source:** https://about.starbucks.com/press/2026/making-it-easier-to-plan-your-starbucks-visit/  
**Source publication date:** April 22, 2026  
**Date reviewed:** November 19, 2026

**Observation:** Starbucks introduced scheduled ordering for participating locations, allowing customers to select a pickup time up to one hour ahead. Its ordering experience supports planning around busy schedules.

**Strength:** Customers can arrange pickup around other commitments.

**Potential limitation for CampusFuel's audience:** A scheduling feature alone does not establish that food is affordable for students.

**Proposed CampusFuel feature:** Allow customers to select a pickup time when placing an order.

**Verification needed:** Test whether a student can select a pickup time, see that time in the order review, and receive an accurate confirmation when the feature is implemented.

### Competitor 2 — Dunkin'

**Website:** https://www.dunkindonuts.com/  
**Source:** https://www.dunkindonuts.com/mobile-app/  
**Date reviewed:** November 19, 2026

**Observation:** Dunkin' promotes mobile ordering, drink customization, and the ability to save favorite orders.

**Strength:** Returning customers can customize products and reorder familiar items conveniently.

**Potential limitation for CampusFuel's audience:** The available source does not demonstrate whether its ordering experience meets the specific needs of college students between classes.

**Proposed CampusFuel feature:** Provide a simple menu with customizable drinks, clearly displayed prices, and an easy-to-understand order summary.

**Verification needed:** Test whether a customer can select a drink, modify its options, and confirm the updated total price before checkout.

## 3. Comparison of Research Findings

| Category | Starbucks | Dunkin' | CampusFuel opportunity |
|---|---|---|---|
| Ordering | Mobile ordering | Mobile ordering | Simple student-focused ordering |
| Pickup | Scheduled pickup | Order-ahead pickup | Pickup-time selection |
| Customization | Product options | Customizable drinks | Basic drink customization |
| Convenience | Plan around schedules | Save and reorder favorites | Fast navigation and clear prices |
| Student focus | Not established by this research | Not established by this research | Test a student-specific experience |

**Research finding:** Both competitors emphasize convenience in digital ordering. This suggests that ordering speed and clarity are reasonable design priorities to investigate, but it does not prove that college students prefer a particular interface.

## 4. Audience Hypothesis A

**Persona:** Alex — College Student

**Type:** Fictional persona hypothesis, not a real interview participant.

**Age:** 20  
**Occupation:** Full-time college student  
**Situation:** Has a short break between classes and wants to buy food without spending much time waiting.

**Hypothesized needs:**
- Quickly find affordable meals.
- See prices before ordering.
- Choose a convenient pickup time.
- Use the website comfortably on a phone.

**Hypothesized frustrations:**
- Long ordering processes.
- Unclear menu prices.
- Difficulty finding pickup information.

**Customer task:** Find a meal, check its price, customize it if needed, and arrange pickup before the next class.

**Assumptions requiring testing:** We have not interviewed students or measured how much time they spend ordering. The persona's needs are design hypotheses.

## 5. Positioning Approach A — Convenience

**Proposed positioning:** CampusFuel helps busy college students find affordable food and arrange pickup quickly between classes.

**Brand character:** Friendly, energetic, approachable, and practical.

**Design direction:** A mobile-first layout with clear navigation, readable prices, and prominent menu and pickup actions.

**Honest persuasion:** Emphasize the ability to view prices and plan pickup rather than promising guaranteed waiting times or unverified savings.

**Reason for this approach:** The Starbucks and Dunkin' sources show that convenient digital ordering is an established feature among café competitors. CampusFuel can investigate whether a simpler student-focused experience would be useful.

**Alternative positioning:** A study-space and community-focused café. This approach remains open for group comparison and evaluation.

## 6. Research-to-Feature Trace

| Source observation | Proposed feature | Planned acceptance check |
|---|---|---|
| Starbucks offers scheduled pickup | Pickup-time selection | Select an available pickup time; verify the same time appears in the order review and eventual confirmation. |
| Dunkin' offers customization | Customizable menu items | Change an item option; verify the selected option and any price change appear in the order summary. |
| Dunkin' supports convenient ordering | Clear mobile ordering flow | Complete the planned ordering sequence on mobile and desktop; check that navigation and controls remain usable. |
| Persona A may need affordable meals | Visible prices | Confirm each listed product displays its price before selection and that the order summary shows an accurate total. |

These are proposed acceptance checks, not completed test results. The persona-based feature is a hypothesis, not a finding from the competitor sources.

## 7. Planned Verification — Revised After Peer Feedback

**Test scenario:** A customer wants to order a customizable drink for pickup between classes.

**Precondition:** A future CampusFuel prototype includes a menu item with a base price, at least one customization option, and selectable pickup times. Use an example item with known prices so the expected total can be calculated independently.

**Acceptance sequence (perform on both desktop and mobile):**

1. Open the CampusFuel website and navigate to the menu.
2. Select a menu item and verify its base price is visible before adding it to the order.
3. Change a customization option and verify the selected option is reflected in the order.
4. Check that the order summary displays the correct item, customization, quantity, and recalculated total price. If there are taxes or fees, display them separately and confirm the total includes them accurately.
5. Choose an available pickup time and verify that the same time appears in the order review.
6. Review the complete order **before** confirming it, including item details, total price, and pickup time.
7. If a confirmation feature is implemented, submit the order and verify that the confirmation matches the reviewed details. Do not treat an unimplemented checkout as a passed test.

**Device and accessibility checks:**
- [ ] Repeat the sequence at a desktop viewport (for example, 1280 px wide).
- [ ] Repeat the sequence at a mobile viewport (for example, 375 px wide).
- [ ] Verify there is no horizontal scrolling needed to complete the ordering flow.
- [ ] Verify menu controls, customization choices, and pickup-time selection are readable and operable.
- [ ] Use keyboard navigation to check focus visibility and control order.
- [ ] Record actual observed results, failures, screenshots or other evidence, and the date of testing.
- [ ] Ask a reviewer to trace one research observation to a proposed feature and repeat the documented test when a prototype is available.

**Current verification status:** The research and acceptance criteria are documented. CampusFuel's proposed ordering features have not been implemented or tested as part of this record; all prototype checks remain pending.

## 8. Individual Contribution and Group Integration

**Nicholas Duarte (njd54):**
- Researched Starbucks and Dunkin'.
- Compared their ordering-related features.
- Developed Audience Hypothesis A.
- Proposed convenience-focused positioning.
- Defined the primary customer task.
- Created the research-to-feature trace and planned checks.
- Revised the planned acceptance checks in response to peer feedback on Issue #1.

The teammate's research, contributions, and review decisions will be documented separately by that teammate.

The group must still compare three relevant sites, two positioning approaches, and two persona hypotheses before finalizing its shared research decision.

## 9. AI Assistance

ChatGPT assisted with identifying official competitor sources, organizing observations, developing a fictional persona hypothesis, drafting the research-to-feature trace, and revising acceptance criteria in response to peer feedback.

The competitor observations are based on the linked sources. The persona, positioning, and CampusFuel features are proposed ideas rather than verified customer findings. Actual prototype testing and reviewer confirmation remain pending.

## 10. Peer Feedback and Revision Record

**Review issue:** https://github.com/njd54/is117_group_business/issues/1  
**Feedback date:** November 19, 2026  
**Decision:** Revise

**Feedback addressed:** The peer-review suggestion called for a more specific end-to-end pickup-ordering acceptance check, including item selection, customization, updated total price, pickup time, order review, and testing on desktop and mobile.

**Revision made in this document:** Section 6 now links the proposed features to more precise checks. Section 7 now defines a complete ordering scenario, expected outcomes, device checks, and evidence to record.

**Reason for decision:** A defined sequence makes the proposed customer task easier to evaluate and reduces ambiguity about what a successful ordering experience should demonstrate.

**Revision commit:** Pending — add the actual commit URL after pushing this file.  
**Documentation verification:** Pending — check the committed file on GitHub and confirm the revised criteria are visible.  
**Reviewer retry:** Pending — ask the reviewer to confirm that the revised criteria address the suggestion.  
**Prototype verification:** Pending — no claim is made that an ordering flow is implemented or functioning.

Keep the issue open until the review is resolved or clearly document any outstanding confirmation.

## 11. Next Steps

1. Commit and push this revised `docs/nick-research.md` file.
2. Add the actual revision commit link to GitHub Issue #1 and request a reviewer retry.
3. Verify the revised documentation is visible in the repository and record the result.
4. Have the teammate complete their independent research and integrate the group's three-site, two-positioning, and two-persona comparison.
5. Select the group's final customer task and explain the decision.
6. When a prototype exists, perform the planned ordering, desktop, mobile, and accessibility checks and record actual results.

---

## Appendix B — Abhinav Anipeddi: full individual research record

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