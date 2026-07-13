# Digital Automation of Jess's Rule

A First Class BSc Computer Science dissertation project that presents a proof-of-concept clinical decision support system to operationalise Jess's Rule. The prototype analyses simulated Electronic Health Record (EHR) data to identify repeated unresolved patient presentations and support the early recognition of potential diagnostic delays in primary and urgent care.

---

## Academic Achievement

This project was developed as my final-year BSc Computer Science dissertation at the University of West London and was awarded a **First Class**.

**Dissertation Title**

**Digital Automation of Jess's Rule: A Smart Alert System to Detect Repeat Patient Visits and Prevent Diagnostic Delays in Primary and Urgent Care**

---

## The Problem

Patients who repeatedly present with unresolved symptoms are often treated as isolated encounters. This can delay diagnosis and result in missed opportunities for earlier clinical intervention.

Jess's Rule, introduced by NHS England following the death of Jessica Boniface, promotes a "three strikes and rethink" approach to encourage clinicians to reconsider repeated presentations. However, there is currently no widely available digital solution that automatically detects these patterns within Electronic Health Record (EHR) systems.

---

## My Solution

To address this challenge, I independently conceived, designed, and developed a rule-based smart alert prototype that analyses simulated EHR-style data to identify repeated unresolved patient presentations.

The prototype evaluates:

- Symptom similarity across multiple visits
- Resolution status of previous encounters
- Number of repeat presentations
- Time intervals between visits using configurable monitoring windows (30, 90 and 180 days)

Based on these criteria, the system generates colour-coded clinical alerts:

🟢 **Green** – Routine monitoring

🟠 **Amber** – Monitor closely

🔴 **Red** – Escalation recommended

The aim is to assist clinicians in recognising potential diagnostic delays earlier and encourage timely review of patients with recurring unresolved symptoms.

---

## Prototype Demonstration

A demonstration of the working prototype is available below:

https://youtu.be/smSS2uq9dUo

---

## Technologies Used

- Python 3
- Gradio
- Figma
- PyCharm
- Google Forms (questionnaire design and analysis)

---

## Project Evaluation

The prototype underwent functional testing and usability evaluation.

### Functional Testing

- Successfully implemented a fully functional proof-of-concept prototype
- Successfully passed all five predefined scenario-based functional tests

### User Evaluation

The prototype was evaluated by **26 NHS clinical and operational professionals** using a structured questionnaire.

Key findings included:

- Average understanding score: **4.50 / 5**
- Average ease of use score: **4.31 / 5**
- Average perceived clinical usefulness score: **4.15 / 5**
- **19 of 26 participants** agreed that the prototype could help identify patients at risk of diagnostic delay.

---

## Future Development

Potential future enhancements include:

- Integration with Electronic Health Record systems
- Automated patient record screening
- Intelligent symptom matching using Natural Language Processing (NLP)
- Machine learning-assisted risk prediction
- Clinical validation using real-world NHS datasets
- Integration into NHS clinical workflows

---

## Skills Demonstrated

- Python Programming
- Clinical Decision Support Systems
- Healthcare Data Analysis
- Rule-Based System Design
- Software Prototyping
- User Interface Design
- Research Methods
- Usability Evaluation
- Technical Documentation

---

## Research Context

This project was independently conceived, designed, and implemented by me as part of my undergraduate research.

It was inspired by the challenges of diagnostic safety and my interest in applying computing technologies to improve patient safety, healthcare delivery, and clinical decision-making.

---

## Source Code Availability

The full source code is not currently publicly available while future development opportunities are being explored.

This repository provides an overview of the project together with a demonstration of the working prototype.

---

## Disclaimer

This project is a proof-of-concept developed exclusively using simulated data for academic research purposes.

It is not intended for direct clinical use or deployment within NHS systems without further development, validation, regulatory review, and clinical evaluation.

---

## Contact

If you would like to discuss this project, potential collaboration, or opportunities in digital health, health data science, or clinical decision support systems, please feel free to connect with me on LinkedIn.
