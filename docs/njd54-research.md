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
