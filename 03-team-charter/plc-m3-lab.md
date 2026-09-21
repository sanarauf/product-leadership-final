# Lead and Develop High-Performing Teams, Module 3 Lab

## Name the situation
- **Who they are (role, not name), what you have observed, and how long it has been happening.:** Our Engineering director brought on an external hire to join his Engineering team. Other engineers who interviewed this candidate did not think he met the "internal bar" for Team Lead (the role he would fill) and the director hired him anyway. This was a major de-motivator for all the Senior Engineers on the team who had been working toward a Team Lead promotion. Not only did the external hire not operate as a team lead, he lowered the bar for how a Team Lead would operate within the team. As a result, some of our best engineers were then demotivated to work as hard or take ownership of their work.

## Make a diagnosis
- **Your diagnosis, plus one sentence on why. Is your frustration with their behavior, or with a decision you made?:** I believe the issue was at System level.

This individual received feedback and clear guidance on what is expected of a Team Lead. He was not able to perform at that level. The result of that was that top-performers at a couple levels below were de-motivated and losing ownership of their work. Team morale was taking a nose-dive and our output was slowing down.

## Write your opening line
- **One next action I will take in the next two weeks is:** As the Product partner in this scenario, I shared objective feedback with the Engineering director on what I have come to expect from a Team Lead at our organization vs what I was observing in the new hire. I concretely laid out the gaps and provided specific expectations.
- **The first sentence of the conversation I need to have is:** I have had a chance to work closely with Team Lead and would like to share some opportunities for improvement.

## AI role-play
- **After you step out: what did the role-play change about how you will open this conversation for real?:** _(not filled in)_

## Refine and complete your charter
- **What We Own. What this team owns.:** What We Own
Foundations Initiative (Lead): Shared platform architecture, core data models, offline-first reliability, cross-cutting performance non-negotiables, and cross-team strategic cohesion.

Field Adoption & Mobile Experience (PM 1): Frontline job-site surfaces (under-15-second mobile interactions, daily log simplification, photo markups) designed specifically for field superintendents and foremen at our 38 core enterprise firms.

Enterprise & Governance (PM 2): Back-office web workflows, administrative governance, compliance reporting, and enterprise integration pipelines for corporate management.
- **What is out of scope.:** Administrative Friction on Mobile Surfaces: Adding approval gates, multi-field governance forms, or complex enterprise administrative workflows to the mobile app. Mobile remains exclusively optimized for under-15-second frontline data capture.

Sales-Driven Web UI Refreshes: Desktop cosmetic redesigns or non-strategic features driven purely by isolated enterprise deal renewals or sales vanity metrics without direct alignment to core field OKRs.

Standalone Mobile Apps: Building separate, fragmented mobile apps outside the unified Meridian platform codebase.
- **Cross-boundary decisions that need a joint call.:** Cross-Boundary Decisions (Joint Call Required)
Capacity & Bandwidth Reallocation: Shifting engineering or product capacity between Enterprise capabilities (PM 2) and Field Adoption/Mobile systems (PM 1).

Data Schema & Integration Pipelines: Modifying shared data models or APIs that connect frontline mobile capture tools (e.g., photo markups, daily logs) to back-office enterprise workflows (e.g., RFIs, compliance records).

Enterprise Renewal Requests Touching Mobile: Any enterprise contract commitment or renewal request that introduces new fields, steps, or requirements to the frontline mobile interface.
- **How We Decide. Who decides feature and scope calls.:** How We Decide: Feature & Scope Calls
Frontline Mobile & Field Adoption (PM 1): Has final decision rights over mobile feature design, job-site user flows, and field interaction speed. Bound strictly by the "One Hard No" (under-15-second interactions, zero mobile administrative friction).

Enterprise & Governance (PM 2): Has final decision rights over back-office web workflows, compliance features, administrative reporting, and enterprise integration needs that do not touch mobile surfaces.

Platform Architecture & Strategic Alignment (Foundations Lead): Has final decision rights on core platform data models, shared engineering resource allocation across initiatives, and overall strategic trade-offs between enterprise and field bets.

Strategic Shielding (Foundations Lead): Explicitly protects PM 1’s field adoption roadmap and engineering capacity against scope creep or feature dumping driven by enterprise renewals.
- **How cross-team conflicts escalate.:** Level 1 (PM Alignment — 24 Hours): PM 1 (Field) and PM 2 (Enterprise) evaluate the conflict against the "One Hard No" guardrail and current roadmap priorities to find an internal resolution.

Level 2 (Foundations Lead Resolution — 48 Hours): Foundations Lead (You) resolves unresolved PM disputes or capacity shifts, enforcing the rule that engineering bandwidth dedicated to NOW horizon field bets is protected by default.

Level 3 (VP of Product Arbitration — 5 Business Days): Triggered by external commercial or enterprise renewal pressures threatening field resources; Foundations Lead submits a Trade-Off Memo, and the VP of Product issues the final binding decision.
- **Who resolves escalations from outside the team.:** The VP of Product resolves external escalations (e.g., enterprise sales or customer renewal pressures) within 5 business days, after reviewing a trade-off memo from the Foundations Lead.

## Show and swap your team charter
- **Where does the charter leave room for interpretation that could cause a conflict?:** Here are the primary areas in the charter where ambiguity or gray areas could trigger cross-team friction:

Defining a "Field" vs. "Enterprise" Feature: Features that span both surfaces (e.g., a field observation tool that feeds directly into an enterprise compliance report) leave room to debate whether PM 1 or PM 2 owns the feature and its primary requirements.

"Under-15-Second Interaction" Criteria: Subjective interpretation of what constitutes "friction" or a "15-second interaction" allows PM 2 or Sales to argue that a required enterprise data field is "quick enough" to include on mobile.

Shared Platform Engineering Capacity: The charter protects PM 1’s NOW horizon bets, but it does not specify fixed headcount or capacity percentages between PM 1 and PM 2 for baseline maintenance, shared architecture, or bug fixes.

Threshold for Level 3 Escalation: It is unclear what ARR value or deal size constitutes a "significant renewal" justifying an escalation directly to the VP of Product versus handling it internally at Level 2.

Definition of "Data Schema" Changes: Minor API or database updates may not clearly trigger the "Joint Call Required" rule, leading one team to push unvetted changes that break the other team's data ingestion flows.
