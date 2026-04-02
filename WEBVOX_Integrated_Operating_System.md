# WebVox Integrated Operating System for Project Delivery and Calling/Sales

## Executive Summary

WebVox can operate as a single integrated **Revenue → Delivery** system by standardizing shared policies (communication SLAs, leave, confidentiality, pay date, performance management, and dispute handling), while keeping role-specific mechanics (deadlines, commission triggers, penalties) in two aligned agreements:

- **Agreement A:** Project Delivery Team Agreement (PM + delivery contributors)
- **Agreement B:** Calling/Sales Team Agreement (calling agents)

This framework gives operational clarity, measurable performance controls, and cleaner handoffs between sales and delivery.

> **Compliance Note:** Because governing jurisdiction is not specified, penalty/deduction enforcement must be validated under local labor law before payroll deductions are applied.

---

## 1) Integrated Operating Model

### Pipeline 1: Revenue (Calling/Sales)
1. Contact lead
2. Qualify lead
3. Book sales meeting
4. Close deal
5. Confirm full payment
6. Handoff package to PM

### Pipeline 2: Delivery (PM + Creators)
1. Onboarding meeting
2. Content meeting
3. Schedule/content plan
4. Task assignment
5. Production (writer/designer/editor/marketer)
6. Internal QA review
7. Client approval
8. Final delivery
9. Monthly/project close and upsell loop

---

## 2) Roles, Responsibilities, and KPIs

| Function | Role | Core responsibilities | Primary KPIs | Evidence/Tracking |
|---|---|---|---|---|
| Leadership | Owner / Ops Head | Targets, policy approval, escalations | Revenue growth, margin, dispute closure time | Monthly ops review |
| Revenue | Sales Lead | Lead QA, coaching, sales reporting | Qualified lead rate, conversion rate | CRM/sheet + call logs |
| Revenue | Calling Agent | 5 hrs/day calling, qualify, close, handoff | Sales count, revenue, adherence | Timesheet + call logs |
| Delivery | PM | Client communication, onboarding, planning, assignments, review, delivery | On-time rate, missed SLA count, rework/cancellation rate | Task board + WhatsApp + calendar |
| Delivery | Content Writer | Copy development + revisions | On-time submissions, approval rate | Docs/version history |
| Delivery | Designer | Asset creation + export | 24h post turnaround, acceptance rate | Task timestamps |
| Delivery | Video Editor | Video production + revisions | ≤4-day delivery, rework cycles | File timestamps |
| Growth | Marketer | Campaign setup/reporting | Launch timeliness, performance metrics | Platform reports |
| Social | Social Media Handler | Posting execution + response handling | Posting adherence, response SLA | Content calendar |

---

## 3) End-to-End Flow (Mermaid)

```mermaid
flowchart LR
  A[Lead list / inbound inquiry] --> B[Calling/Sales: contact & discovery]
  B --> C{Qualified Lead?}
  C -- No --> B
  C -- Yes --> D[Book Sales Call / Google Meet]
  D --> E[Close sale & confirm scope]
  E --> F{Payment status}
  F -- Not paid --> E
  F -- Full payment received --> G[Sales Handoff Pack to PM]

  G --> H[PM: Onboarding Meeting]
  H --> I[Content Meeting]
  I --> J[Create Schedule / Content Plan]
  J --> K[Task Assignment]
  K --> L1[Content Writer]
  K --> L2[Designer (24h SLA)]
  K --> L3[Video Editor (≤4 days SLA)]
  K --> L4[Marketer/Social Handler]

  L1 --> M[PM Internal Review & QA]
  L2 --> M
  L3 --> M
  L4 --> M

  M --> N[Client Approval]
  N --> O{Approved?}
  O -- Revisions --> K
  O -- Approved --> P[Final Delivery + Handover Files]
  P --> Q[Project/Monthly Close]
  Q --> R[Upsell Opportunity]
  R --> B
```

---

## 4) Communication & SLA Standards

- **Mandatory channels:**
  - WhatsApp (daily updates, escalation)
  - Google Meet (onboarding/content/review meetings)
- **Baseline response SLA:** 24 hours for internal requests
- **Urgent escalation (recommended):** 2 hours in working time for messages tagged urgent
- **Decision logging:** Scope/timeline/approval decisions must be confirmed in writing

---

## 5) Delivery Timelines and Clock Start Rules

### SLA Rules
- Post design: **within 24 hours**
- Video edits: **within 4 days**

### Project Value Tiers
- `< 100,000 LKR` → within 1 week
- `100,000–500,000 LKR` → within 2 weeks
- `500,000–1,000,000 LKR` → within 3 weeks

### Clock Start Definition
SLA clock starts when PM posts a **Complete Brief** containing:
1. Objective
2. Technical/creative specs
3. Required assets
4. References
5. Due date/time

---

## 6) Attendance, Leave, and Transition

### Work Setup
- PM & Delivery roles: Work From Home
- Calling agents: Work From Home, **5 hours/day**

### Leave Policy
- Maximum **4 leave days/month**
- Leave plan submitted at month start
- Emergency leave allowed with immediate notice and approval workflow

### Exit/Resignation
- Minimum **1-month written notice**
- Mandatory transition support
- **2-week replacement training/handover** required

---

## 7) Compensation, Commission, Bonuses, and Penalties

### Pay Timing
- Payment date: **4th of every month**

### Calling/Sales Commission Rules
- Sales 1–4: **No commission**
- From 5th sale onward: **3% commission**
- Commission payable only when **full client payment is received**
- If refunded: commission is **void**

### Bonus Rules
- 5 projects in calendar month: **5,000 LKR**
- 1,000,000 LKR project: **10,000 LKR**

### Penalty Rules
- Missed working time (Calling): **150 LKR/hour**
- Fake/wrong lead info: **500 LKR/case**
- Missed monthly target (3 sales + 150,000 LKR): **3,000 LKR**
- Delivery task delay: **500 LKR per delayed deliverable**
- Project cancellation due to mismanagement: **10,000 LKR**

### Compliance-Safe Enforcement Language
All penalties are performance controls. Wage/fee deductions are applied only if lawful and properly authorized in the governing jurisdiction. If deductions are not lawful, WebVox may apply non-monetary remedies (warnings, bonus reduction, reassignment, termination/non-renewal).

---

## 8) Agreement Template A: Project Delivery Team

**Title:** WEBVOX PROJECT DELIVERY TEAM AGREEMENT

### Key Clauses
1. Term: 4 months; auto-renewal in 4-month cycles
2. Work mode: WFH
3. Response SLA: 24 hours
4. PM is owner of client communication
5. Standard mandatory workflow (lead handoff to final delivery)
6. Deadline and complete-brief clock start definitions
7. Payment terms and pay date (4th)
8. Delay/cancellation penalties with legal compliance override
9. Leave cap: 4 days/month, month-start submission
10. 3-step performance process (warning/final warning/termination)
11. 1-month resignation notice + 2-week replacement training
12. Confidentiality and company asset-use restrictions
13. Dispute resolution sequence and governing law placeholder

---

## 9) Agreement Template B: Calling/Sales Team

**Title:** WEBVOX CALLING / SALES TEAM AGREEMENT

### Key Clauses
1. Term: 4 months; auto-renewal
2. WFH with 5 working hours/day
3. Attendance logging required
4. Qualified lead definition (mandatory)
5. Monthly minimum target: 3 sales + 150,000 LKR
6. Commission from 5th sale at 3% (full payment only)
7. Refund nullifies commission
8. Bonus structure (5 projects / 1M project)
9. Daily reporting and 24-hour response SLA
10. Performance 3-step path
11. Leave and resignation requirements
12. Confidentiality and compliance-safe deduction clause
13. Dispute path + governing law placeholder

---

## 10) Onboarding Checklists

### PM/Delivery Onboarding
- Role scope confirmation
- Tool access (WhatsApp, Meet, task board, file storage)
- Workflow training
- SLA training
- Quality standards and revision rules
- PM-only client communication rule
- Penalty/bonus explanation
- Confidentiality briefing
- Shadow onboarding/content meetings
- Written acknowledgment

### Calling/Sales Onboarding
- Tool + script setup
- 5h/day attendance process
- Qualified lead calibration
- Target/commission training
- No-misrepresentation compliance training
- First-week sample lead validation
- Coaching on objections and PM handoff package

---

## 11) Reporting Templates

### Daily WhatsApp Template
- Role/Name:
- Date:
- Planned tasks:
- Completed tasks (with links):
- Blockers/risks:
- Support needed:
- Tomorrow’s plan:

### Weekly Template
- Week range:
- Projects touched:
- Deliverables completed:
- Missed SLAs + reason:
- Client approval status:
- Sales metrics (if applicable):
- Risks + action plan:

---

## 12) Finalization Checklist

Before execution:
1. Fill governing law and jurisdiction in both agreements
2. Validate deduction/penalty enforceability under local labor law
3. Confirm whether target sales are booked or fully paid
4. Finalize PM “+5,000 after first project” logic (one-time vs monthly allowance)
5. Choose dispute endpoint (mediation, arbitration, or courts)
6. Fill all compensation placeholders and signatory blocks

---

## 13) Recommended Next Artifacts

- `Agreement_A_Project_Delivery.pdf`
- `Agreement_B_Calling_Sales.pdf`
- `SOP_Daily_Weekly_Reporting.pdf`
- `HR_Penalty_Commission_Calculator.xlsx`

