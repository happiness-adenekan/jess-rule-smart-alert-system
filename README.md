# Digital Automation of Jess's Rule

A rule-based smart alert prototype for detecting repeated unresolved patient visits and preventing diagnostic delays in primary and urgent care.

## Problem Solved

Repeated patient presentations with unresolved symptoms are often treated as isolated encounters. This can lead to missed opportunities for earlier diagnosis and contribute to preventable diagnostic delays in primary and urgent care.

Jess's Rule, introduced by NHS England, promotes a "three strikes and rethink" approach, but there is currently no widely available digital tool that automatically detects these patterns in Electronic Health Record (EHR) systems.

## My Approach

I designed and developed a rule-based smart alert prototype that analyses simulated EHR-style data to identify repeated unresolved presentations for the same symptom.

The system evaluates:

- Symptom similarity across visits
- Resolution status of previous encounters
- Number of repeat visits
- Time between visits within configurable monitoring windows (30, 90, and 180 days)

Based on these criteria, the system generates:

- 🟢 Green: Routine monitoring
- 🟠 Amber: Monitor closely
- 🔴 Red: Escalation required

## Demo of the Working System

Watch the project demonstration here:

https://youtu.be/smSS2uq9dUo

## Technologies Used

- Python 3
- Gradio
- Pandas
- Figma
- PyCharm
- GitHub

## Measurable Outcomes

- Successfully implemented a fully functional proof-of-concept prototype
- Passed all 5 predefined scenario-based functional tests
- Evaluated by 26 NHS clinical and operational professionals
- Achieved an average understanding score of 4.50/5
- Achieved an average ease of use score of 4.31/5
- Achieved an average clinical usefulness score of 4.15/5
- 19 out of 26 participants agreed that the system could help identify patients at risk of diagnostic delay

## Source Code

The full source code is not publicly available at this time. However, the demonstration video and project overview provide a detailed explanation of the system design and functionality.

## Research Context

This project was developed as part of my final-year BSc Computer Science (Health Informatics) dissertation at the University of West London.

**Dissertation Title:**
Digital Automation of Jess's Rule: A Smart Alert System to Detect Repeat Patient Visits and Prevent Diagnostic Delays in Primary and Urgent Care

## Disclaimer

This project is a proof-of-concept developed using simulated data only and is intended for academic and research purposes. It is not designed for direct clinical use.
