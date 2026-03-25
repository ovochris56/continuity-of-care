# Continuity of Care
This project analyzes how delays in insurance renewal and resulting coverage gaps can disrupt continuity of care and contribute to worse patient outcomes. he dashboard focuses on the operational and clinical impact of coverage lapses, including higher patient severity and increased emergency room utilization after a gap in coverage.

# Business Problem

When patients fail to renew insurance coverage on time, they may experience a temporary lapse in access to care. These disruptions can delay treatment, reduce follow-up adherence, and increase the likelihood that patients return in worse condition. For providers and healthcare systems, this creates avoidable clinical risk and downstream utilization.

# Project Goal

The goal of this analysis is to identify how coverage gaps affect patient severity and care utilization, and to frame continuity-of-care interventions as a measurable analytics opportunity.

# Key Questions
- How common are coverage gaps within the patient population?
- Do patients with coverage gaps present with higher severity?
- Does longer gap duration appear associated with worse outcomes?
- Are there differences in gap rates across language groups?
- Could proactive outreach reduce avoidable disruptions in care?

# Dashboard Snapshot

From the dashboard:
- Total patients: 5,954
- Patients with coverage gaps: 39.5%
- Average gap duration: 23.1 days
- Post-gap ER utilization: 24.6%

The dashboard also shows:
- Patients with coverage gaps had higher average severity than those without gaps
- Severity increased as coverage gap duration lengthened
- Gap rates were relatively similar across Spanish, Portuguese, and English-speaking groups 

# Key Insights
	1.	Coverage gaps are common and operationally significant. Nearly 4 in 10 patients in this analysis experienced a lapse in coverage.  ￼
	2.	Patients with coverage gaps show higher average severity. This suggests delayed access to care may contribute to worsening condition by the time patients re-engage.  ￼
	3.	Longer coverage gaps are associated with higher severity. The relationship shown in the dashboard suggests duration matters, not just whether a gap occurred.  ￼
	4.	Post-gap ER utilization is notable. This points to a possible downstream consequence of disrupted access and delayed intervention.  ￼
	5.	Language differences in gap rate appear limited in this version of the analysis. That may mean the issue is broad-based, though future work could explore whether language influences renewal completion, portal usage, or reminder effectiveness. 

# Strategic Recommendations
- Implement insurance renewal reminders 60 to 90 days before expiration
- Use patient portals, SMS, and call-center workflows to flag at-risk patients
- Prioritize patients with prior lapses for proactive outreach
- Track gap rate, average gap days, and post-gap utilization as operational KPIs
- Explore whether digital literacy, portal comprehension, or language access barriers contribute to late renewal

# Tools Used
- Power BI
- Healthcare operations analysis
- KPI design
- Data storytelling

# Why This Project Matters

This project sits at the intersection of healthcare analytics, access, and prevention. It reframes insurance renewal not as an administrative issue, but as a continuity-of-care problem with measurable consequences for patient severity and downstream utilization.

# Next Steps

Future versions of this project could incorporate:
- demographic and payer segmentation
- appointment adherence before and after a gap
- outreach intervention scenarios
- integration with patient portal reminder workflows
- SQL-based data modeling for scalable operational reporting

