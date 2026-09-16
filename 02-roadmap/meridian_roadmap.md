# Meridian Foundations: Outcome Roadmap & Trade-Off Memo (Module 2)

## 1. Executive Summary & Strategic Context
* **Winning Aspiration:** Field superintendents and foremen input their data (photos, notes, status) directly into Meridian as their primary method for daily project management and job-site collaboration.
* **Where to Play:** Frontline field teams (superintendents and foremen) at the 38 top-100 US general contractors where Meridian is already the enterprise system of record.
* **How to Win:** Leverage Meridian’s entrenched enterprise status by delivering an uncompromised, under-15-second frontline mobile experience that directly competes with native camera rolls and group text chains.

---

## 2. OKRs (Quarterly Commitments)
* **Objective:** Transform Meridian into the frictionless, primary daily entry point for frontline field teams, making field-captured data the real-time source of truth for back-office operations.
  * **KR1 (Active Adoption):** Increase the percentage of weekly active field superintendents and foremen at our 38 enterprise firms who log at least one field update (photo, daily log, or issue) directly in Meridian.
  * **KR2 (Cycle Time):** Reduce the average lag time between a field photo/observation being captured and its formal logging in back-office RFIs or daily reports.
  * **KR3 (Friction Reduction):** Decrease the volume of back-office-initiated manual data entries and offline text/email attachments processed per active project.

---

## 3. Backlog Prioritization: Rocks & Hard Nos

### 🏔️ Rocks (Top 3 Strategic Bets)
1. **Item #1: Build offline-first mobile experience for job sites with poor connectivity**
   * *Rationale:* Offline reliability is a table-stakes prerequisite. If the app fails underground or inside concrete structures, superintendents immediately fall back to native SMS and offline camera rolls.
2. **Item #4: Simplify the daily log: reduce from 14 required fields to 4**
   * *Rationale:* Directly eliminates administrative overhead. Reducing data input to an under-15-second task removes the tax driving foremen to off-app text channels.
3. **Item #2: Add photo markup and annotation tool for field teams**
   * *Rationale:* Competes directly with the native phone photo gallery. Instant visual markup at the point of capture enables frontline teams to highlight issues rapidly, driving down RFI lag time.

### ❌ Hard Nos (Explicit Trade-Offs)
1. **Item #10: Build an executive reporting dashboard with custom KPIs**
   * *Rationale:* Serves C-suite reporting demands but adds zero value to frontline job-site workflows, diluting focus away from field adoption.
2. **Item #7: Create a foreman-facing mobile app (separate from PM web app)**
   * *Rationale:* Violates the foundational constraint that core capabilities must be additive to the unified platform. A standalone app creates codebase fragmentation and data sync debt.
3. **Item #13: Refresh the web UI (feedback: "looks outdated" from prospects)**
   * *Rationale:* Desktop cosmetic updates do not solve the job-site adoption crisis. Bandwidth must remain focused on mobile field execution rather than sales vanity metrics.

---

## 4. Now / Next / Later Outcome Roadmap

### 🔴 NOW (Current Horizon — Outcome-Based Bets)
* **Bet 1 (Job-Site Data Reliability):** We bet eliminating offline connectivity dead zones will drive a 30% increase in daily mobile activity for field superintendents working in concrete shafts and underground site areas. **[Traces to KR1]**
* **Bet 2 (Frictionless Daily Reporting):** We bet compressing daily logging into a four-field, under-15-second interaction will reduce off-app WhatsApp/SMS chatter by 40% for foremen on active job sites. **[Traces to KR3]**
* **Bet 3 (Visual-First Site Communication):** We bet enabling native on-photo markups at the point of capture will cut the lag time between site issue identification and formal back-office RFI creation in half for field teams and project managers. **[Traces to KR2]**

---

### 🟡 NEXT (Near-Term Horizon)
* **AI-Assisted RFI & Observation Drafting:** *Follows NOW because field teams must first adopt native photo markups before automated language models can accurately structure visual logs into formal documents.*
* **Real-Time Push Alerts for Schedule Changes:** *Follows NOW because automated site alerts depend on superintendents consistently updating active site logs in real time during the current phase.*
* **Procore Import/Export Integration Repair:** *Follows NOW because stabilizing external data ingestion bridges active field inputs into legacy workflows without disrupting frontline mobile work.*
* **Automated Compliance Checklist Generator:** *Follows NOW because streamlining core daily logs establishes the foundational field habit needed before adding automated compliance workflows.*
* **Subcontractor Document Sharing Portal:** *Follows NOW because driving internal foreman adoption must precede expanding digital touchpoints to external trade partners.*

---

### 🟢 LATER (Future Horizon — Strategic Bets, Not Commitments)
* **AI-Driven Predictive Risk & Weather Integration:** *Explores proactive safety and schedule risk mitigation once real-time job-site telemetry reaches critical mass.*
* **Mid-Market Light-Mobile Onboarding Motion:** *Explores a low-friction entry tier for smaller contractors ($5M–$50M) without diluting enterprise-grade governance.*
* **Subcontractor Performance & Compliance Analytics:** *Transforms aggregated field logs into automated contractor reliability scoring for C-suite risk teams.*

---

## 5. Peer Evaluation & Strategic Self-Audit

### Show and Swap Rationale
* **Traceability to Strategy:** The Rock selections (#1, #2, #4) read strictly as a strategy to eliminate frontline friction. Every item targets job-site speed, reliability, and ease of use to win mindshare away from native camera rolls and WhatsApp.
* **Defense of Hard No Swap (Item #9 - AI-Assisted RFI Drafting):** An enterprise leader might argue that AI RFI drafting should be a Rock because it automates back-office paperwork. However, AI drafting relies on high-quality, real-time field inputs. If field teams haven't adopted native capture tools (NOW horizon), AI tools will lack the necessary site telemetry to generate accurate RFIs.

### Strategic Pressure-Test Audit
1. **Strategic Bets vs. Feature Descriptions:** Every NOW item is framed using explicit hypothesis logic (*"We bet [action] will [outcome] for [who]"*), focusing on target behavior changes rather than delivery milestones.
2. **OKR Alignment:** 
   * Offline reliability $\rightarrow$ **KR1** (Active adoption).
   * 4-field daily log compression $\rightarrow$ **KR3** (Reduction of off-app attachments/manual entries).
   * On-photo markups $\rightarrow$ **KR2** (Reduction of RFI resolution cycle time).
3. **Cold-Reader Clarity:** Anyone reading the NOW column immediately sees that Meridian’s core problem is job-site friction (connectivity loss, cumbersome forms, and lack of visual tools) driving field teams off-platform, and that this quarter's focus is capturing frontline usage at the point of work.