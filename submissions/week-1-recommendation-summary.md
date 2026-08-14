# Week 1 Recommendation Summary

## Executive Summary

Legacy Trust's debt recovery process is not failing because of one isolated issue. It is failing because a high-volume recovery workflow depends on fragmented spreadsheets, email trails, manual status checks, and a legacy collections system. The result is duplicated activity, missed or delayed follow-ups, inconsistent statuses, manual reconciliation, slow customer journeys, and limited management visibility.

The discovery work shows that Smart-Recovery should focus on **straightforward, repeatable and lower-risk recovery activities**, while complex, disputed, hardship, vulnerable and specialist cases remain agent-led.

The strongest immediate Phase 1 direction is to improve straightforward follow-up management, account/balance visibility and consistent status/outcome capture. Customer-facing payment and resolution options also have significant potential financial upside, but the value case is more dependent on low-confidence recovery-uplift assumptions and should therefore be validated before being treated as a firm Phase 1 commitment.

---

## 1. The Problem

Legacy Trust currently manages a very large delinquent-account population through a process built around multiple manual sources and workarounds. Agents may need to check the legacy collections system, spreadsheet tracker and email or communication history before they can establish the current position of an account.

This creates several connected problems:

- Agents repeat work because previous activity is difficult to see.
- Follow-ups can be missed or delayed between shifts.
- Account statuses are not consistently defined.
- Agents manually update information across multiple systems.
- Managers have limited confidence in workload, pipeline and recovery performance.
- Customers may experience repeated contact and unclear resolution journeys.
- Complex and straightforward cases are not consistently separated.

The stakeholder evidence repeatedly supports these issues. For example, Christopher Richards described the lack of synchronisation between the collections database and email tracker, while Sylvia Turner identified stopping agents from checking whether work was already completed as a major potential improvement. The evidence also reports that 20%+ of follow-ups can be lost between shifts and that straightforward cases can be delayed behind complex cases. 

---

## 2. Key Discovery Findings

### 2.1 Duplicate work and fragmented information

The current process requires agents to check multiple sources before taking action. This creates duplicate checks, repeated contact and unnecessary handling.

Key evidence includes:

- **SN-011 — Christopher Richards:** the collections database does not sync with the email tracker, resulting in re-contact of customers.
- **SN-028 — Diana White:** customers can go through the contact process multiple times.
- **SN-038 — Sylvia Turner:** the biggest win would be agents no longer checking whether work was already done.
- **SN-063 — Mr Martyn Akhtar:** agents manually check three different sheets to determine whether customers have already been contacted.
- **SN-087 — Mr Dale Jackson:** agents spend time hunting for information that should already be available.

### 2.2 Missed and delayed follow-up

Follow-up management is a major operational weakness.

The discovery evidence includes:

- **SN-040 — Catherine Frost:** at least 20% of follow-ups are lost between shifts because ownership is unclear.
- **SN-053 / SN-118:** cases can remain in pending callback status because callback dates are not enforced.
- **SN-052 — Lawrence Bennett:** reducing the time between identifying a payment opportunity and contacting the customer is seen as valuable.

This connects directly to recovery performance because delayed or missed actions can mean delayed customer contact and missed payment opportunities.

### 2.3 Status and data-quality problems

The current workflow lacks consistent status governance.

Evidence includes:

- **SN-015:** the same case can have different statuses in different systems.
- **SN-085 / SN-107:** there is no standard definition of statuses across the team.
- **SN-111 — Daniel Okoye:** every status update in the old system requires manual re-keying into the spreadsheet.
- **SN-122:** different status codes make reporting meaningless.
- **SN-123 — Christopher Richards:** finance activity counts and the database do not reconcile.

These problems reduce operational visibility and weaken confidence in reporting and financial forecasting.

### 2.4 Customer friction

Customers can experience repeated contact, unclear information and unnecessary dependence on agents.

Evidence includes:

- **SN-001:** customers respond positively to control and transparency.
- **SN-002:** customers may call back multiple times because they do not remember what they were told.
- **SN-017:** many customers do not know they can pay online.
- **SN-036:** customers can be transferred between departments and repeat their situation.
- **SN-065:** customers may be more willing to pay when they clearly understand what they owe and their available options.

This supports a customer-facing self-service opportunity, but only for cases where the journey is straightforward and appropriate.

---

## 3. Priority Jobs-to-be-Done

The discovery work produced eight JTBDs. The highest-priority unmet jobs were:

### JTBD-02 — Ensure follow-ups are completed on time

**When** an account requires follow-up across different shifts,  
**I want to** ensure that the follow-up remains clearly assigned and tracked,  
**So that** promised actions are completed on time instead of being lost between handovers.

This is a high-priority operational job because missed follow-up is directly evidenced and closely linked to recovery performance.

### JTBD-01 — Prevent duplicate recovery activity

**When** I am preparing to contact a customer,  
**I want to** know whether another agent has already contacted them or scheduled a follow-up,  
**So that** I can avoid duplicating work and confusing the customer.

This is strongly supported by repeated agent and operations evidence and is closely connected to wasted handling time.

### JTBD-07 — Route cases according to their complexity

**When** an account enters the recovery process,  
**I want to** distinguish straightforward cases from those requiring specialist handling,  
**So that** each case follows an appropriate recovery path without unnecessary delay.

This is critical to Smart-Recovery because it provides the boundary between cases suitable for self-service and cases that require human judgement.

---

## 4. Current-State Process Diagnosis

The As-Is process map shows that debt recovery is not a simple customer-contact workflow. It includes:

- Agent worklist review
- Account-position checking
- Multiple source checks
- Previous-contact checks
- Customer contact
- Outcome recording
- Follow-up decisions
- Spreadsheet activity logging
- Legacy-system updates
- Team-leader escalation
- Reconciliation and monitoring
- Rework and follow-up cycles

The map also highlights that escalation is not necessarily a single handoff. Complex cases may wait for specialist input, return to the agent, and require additional clarification or rework.

The current process therefore contains several loops where operational cost can compound over multiple activities before a case is resolved.

### Key pain points identified on the map

1. **Fragmented information across systems**
2. **Duplicate checks and repeated customer contact**
3. **Inconsistent status definitions**
4. **Manual updates and reconciliation**
5. **Unclear routing between straightforward and complex cases**
6. **Poor management visibility**
7. **Missed or delayed follow-up**
8. **Potential waiting and rework around specialist escalation**

---

## 5. Self-Service Candidates

The process diagnosis indicates that not every broken step should become a portal feature.

The strongest self-service candidates are:

| ID | Opportunity | Why it is suitable |
|---|---|---|
| **AUTO-01** | View outstanding balance and account position | Straightforward customer information that can reduce repetitive agent explanation and account-status handling. |
| **AUTO-02** | View payment and resolution options | Repeatable and rules-driven for eligible straightforward cases. |
| **AUTO-03** | Make a payment / capture straightforward promise-to-pay | Can remove unnecessary agent handling for simple payment outcomes. |
| **AUTO-04** | Set/manage straightforward follow-up | Directly addresses missed follow-up and manual tracking. |
| **AUTO-05** | Capture straightforward contact/outcome consistently | Can improve status consistency and reduce manual reconciliation. |

### Activities that should remain agent-led

The following should remain within the agent or specialist workflow:

- Disputed balances
- Hardship cases
- Vulnerability cases
- Regulatory forbearance
- Complex cases requiring specialist judgement
- Cases requiring additional information or rework
- Unclear recovery outcomes

This is a deliberate scope boundary rather than a weakness in the proposal.

---

## 6. Baseline and Financial Evidence

The ROI workbook uses observed data separately from assumptions.

The baseline contains:

- **3,214 unique delinquent accounts** in the sample
- **£3.03m overdue amount** in the sample
- **9,890 recovery activities**
- **69,226 minutes** of recorded handling effort, approximately **1,154 hours**
- **2,020 duplicate-check activities**, approximately **20.4%** of activity
- **1,465 activities without a next follow-up date**, approximately **14.8%**
- **1,458 spreadsheet reconciliation activities**
- Approximately **218.7 hours** of spreadsheet reconciliation effort
- **1,275 activities** with an unclear next action
- **38% straightforward-case share** as a Finance planning assumption

The account sample also contains a larger source flag for self-service candidates, but this is kept separate from the 38% Finance planning estimate. The two measures should not be treated as interchangeable.

---

## 7. ROI and P&L Approach

The ROI model separates:

### Hard operational benefit

Examples:

- Reduced agent handling time
- Reduced manual reconciliation
- Reduced administrative effort

### Recovery / revenue benefit

Examples:

- Faster payment or plan capture
- Reduced missed recovery opportunities
- Reduced revenue leakage

### Softer benefits

Examples:

- Better visibility
- Improved status consistency
- Better customer control
- Improved reporting confidence

This separation is important because the 15% revenue-loss figure in the case study should not be assumed to be fully recoverable through process improvement.

The workbook therefore treats the Finance recovery-uplift assumptions as lower-confidence inputs and tests them through conservative and optimistic scenarios.

---

## 8. Ranked Opportunities

The five modelled opportunities are:

| Rank consideration | Opportunity | Phase 1 view |
|---|---|---|
| **1** | **AUTO-04 — Set/manage straightforward follow-up** | Strong Phase 1 candidate |
| **2** | **AUTO-01 — View outstanding balance and account position** | Strong Phase 1 candidate |
| **3** | **AUTO-05 — Capture straightforward contact/outcome consistently** | Supporting Phase 1 capability |
| **4** | **AUTO-02 — View payment and resolution options** | Validate before committing |
| **5** | **AUTO-03 — Make a payment / capture straightforward promise-to-pay** | Validate before committing |

The highest pure financial upside should not automatically determine Phase 1.

AUTO-02 and AUTO-03 produce potentially strong value in the model because they rely on recovery-uplift assumptions. Those assumptions have lower confidence, so their headline ROI should not be treated as guaranteed.

By contrast, AUTO-04 and AUTO-01 are more closely aligned to the Week 2 operational diagnosis and do not depend on speculative recovery uplift to justify their relevance.

---

## 9. Conservative vs Optimistic Scenarios

The ROI model uses two scenarios:

### Conservative

- 70% of the assumed operational time reduction
- 50% of the stated Finance recovery-uplift assumption

### Optimistic

- 100% of the assumed operational time reduction
- 100% of the stated Finance recovery-uplift assumption

The purpose is not to create an optimistic headline number. It is to show which opportunities remain credible when assumptions are weakened.

The model demonstrates that recovery-uplift assumptions have a much larger effect on financial returns than the relatively modest labour-saving benefit from small individual administrative tasks.

---

## 10. Phase 1 Recommendation

### Recommended Phase 1 scope

**Prioritise:**

1. **AUTO-04 — Straightforward follow-up management**
2. **AUTO-01 — Balance and account-position visibility**
3. **AUTO-05 — Consistent capture of straightforward outcomes**

These opportunities are recommended because they:

- Directly address the strongest Week 2 pain points.
- Reduce repetitive administrative work.
- Have clear links to the priority JTBDs.
- Are relevant to the proposed self-service workflow.
- Can be designed around straightforward cases.
- Allow complex work to remain agent-led.
- Provide measurable operational outcomes.

### Validate before full Phase 1 commitment

**AUTO-02 — Payment and resolution options**  
**AUTO-03 — Payment / straightforward promise-to-pay**

These opportunities should remain in consideration because they may create significant recovery upside. However, the financial case depends more heavily on recovery-uplift assumptions, so those assumptions should be validated before the bank commits them as core Phase 1 value.

---

## 11. Scope Boundaries and Risks

The recommendation should not be interpreted as a decision to automate debt recovery end-to-end.

The main risks are:

- Complex cases may be incorrectly routed into self-service.
- Customer vulnerability or hardship may require human judgement.
- Disputed balances may require investigation.
- Inconsistent underlying data could undermine the portal.
- Agents may reject the portal if unsupported cases return without enough context.
- Previous system-change failures may create adoption resistance.
- Revenue uplift could be overstated if process-related leakage is confused with genuinely uncollectable debt.

These risks should become explicit validation points in the next phase rather than being hidden behind an optimistic business case.

---

## 12. Measures of Success

Recommended measures include:

- Missed follow-up rate
- Duplicate activity / repeat-contact rate
- Average handling time for straightforward cases
- Time spent on manual reconciliation
- Percentage of straightforward cases successfully resolved through self-service
- Percentage of cases correctly routed to agent/specialist handling
- Customer self-service completion rate
- Agent workload before and after change
- Recovery performance for eligible straightforward cases
- Number of cases requiring rework after self-service

---

## 13. Overall Recommendation

Legacy Trust should **continue with Smart-Recovery discovery and a narrow Phase 1**, rather than attempting an end-to-end replacement of debt recovery.

The strongest case is to use self-service and workflow improvements to remove repetitive work from the straightforward end of the recovery process while keeping complex and higher-risk cases with agents.

The evidence supports a clear sequence:

**Fix visibility and follow-up to separate straightforward from complex cases to enable appropriate self-service to measure operational and recovery outcomes to expand only where evidence supports it.**

This gives Legacy Trust a more defensible path to value than treating the entire debt-recovery process as a single automation opportunity.

The detailed calculations, assumptions, scenarios and opportunity comparison are contained in the accompanying ROI workbook.
