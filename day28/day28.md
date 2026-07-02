# Build a Hospital Admission Readiness Simulator  
>*Experience hospital admissions through an interactive healthcare workflow*  
>*Healthcare Operations with Claude*

Hospital admissions require coordination between providers, insurance companies, utilization review teams, nursing staff, and administrative personnel. Claude can generate complete workflow simulations that teach healthcare operations through interactive decision-making.

**1.Admission Readiness:** Understand the operational steps before hospital admission.  
**2.Healthcare Operations:** Learn how documentation, insurance, and prior authorization impact admissions.  
**3.Risk Management:** Identify and reduce administrative and clinical risks.  
**4.Interactive Simulation:** Build complete browser-based workflow applications using Claude.  

**Tasks**:  
1
Read the provided resources.
2
Watch the solution video.
3
Open Claude.
4
Set Claude effort level to Low.
5
Start a new conversation.
6
Paste the provided Hospital Admission Readiness Simulator prompt.
7
Generate the complete HTML application.
8
Save the generated HTML file.
9
Open the simulator in your browser.
10
Enter provider and physician details.
11
Select a diagnosis and admission type.
12
Configure Prior Authorization status and admission date.
13
Analyze the initial admission readiness score.
14
Complete workflow actions to improve readiness.
15
Resolve Prior Authorization scenarios including approvals, pending requests, or appeals.
16
Reduce documentation, insurance, bed, and clinical risks.
17
Review the Governance Snapshot when available.
18
Analyze the final admission decision.
19
Restart and test multiple diagnosis scenarios.
20
Take screenshots of the simulator and results.
21
If Claude does not complete the output or usage limits are reached, wait for the reset period and continue later.
22
Create a Day28 folder in your GitHub repository.
23
Create a day28.md file.
24
Upload screenshots, generated HTML file, and key learnings.
25
Commit and push the changes.
26
Submit the GitHub commit URL.  

**Input Prompt**:  
Hospital Admission Readiness Simulator

Single-file HTML app. HTML, Tailwind CSS CDN, Vanilla JavaScript.
style: same as previously established
Healthcare simulation design system. Task-first — no dashboard on load.
User plays Hospital Admission Coordinator.

Setup — collect:
- Provider, Attending Physician
- Diagnosis: Acute MI / CHF / Pneumonia / Elective Surgery / Hip Fracture
- Admission Type: Inpatient / Observation / Emergency / ICU / Same-Day Surgery
- PA Status, Admission Date

Observation Status must always show: 'CMS 2-Midnight Rule applies — different cost-sharing, SNF eligibility, and billing than inpatient. Medicare patients require written MOON notification.'
Label all provider/payer names as illustrative training data.

Button: 🏥 Analyze Admission Readiness

Initial Analysis
Generate status for: PA, Insurance, Bed, Documentation, Physician Orders, Consent.
Readiness Score 30–60%. Do not reveal final decision yet.

Score Weighting:
PA Status 25% · Clinical Documentation 20% · Physician Orders 20% · Insurance 15% · Consent 10% · Bed 10%
Denied PA + ICU admission cannot reach 70% from admin tasks alone.

PA Branches:
Approved → continue.
Pending → Follow Up, Upload Docs, Contact Physician.
Denied → Review Reason, Contact Insurance, Submit Appeal.
Successful appeal converts to Approved.

Workflow Actions:
Assign Bed / Verify Insurance / Upload Documentation / Complete Consent / Contact Physician / Notify Nursing / Prepare Patient Arrival

Acute MI and CHF trigger a criteria note:
'InterQual/Milliman thresholds apply — ensure documentation meets medical necessity standards before UR review.'

Timeline milestones:
PA Review → Insurance Verification → Bed Assignment → Documentation → Consent → Patient Arrival → Registration → Clinical Assessment → Admission Complete

Care Coordination Cards:
Attending / Case Manager / Nursing / Utilization Review / Discharge Planner
UR card must name: concurrent review, denial risk identification, InterQual, Milliman.

Risk Tracking:
Documentation Risk / Insurance Risk / Bed Risk / Clinical Risk
Clinical Risk weighted higher for Acute MI, CHF, ICU.

At Readiness ≥ 75% show Governance Snapshot:
'Industry benchmarks (estimates only): PA turnaround 3–5 days · Inpatient denial rate ~8–10% (CMS) · PA rework cost ~$11/transaction (CAQH)'

Final Decision:
≥ 90% → ✅ Admit — full summary.
< 90% → ⚠ Not Ready — missing items, required actions, remaining risks.  

**Learning Outcomes**  
Understand hospital admission workflows  
Build healthcare operations simulators  
Model Prior Authorization scenarios  
Implement weighted scoring systems  
Create interactive HTML applications using Claude
