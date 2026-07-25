# Digital Automation of Jess's Rule

> **A rule-based clinical decision support prototype that analyses simulated Electronic Health Record (EHR) data to identify repeated unresolved patient presentations and support earlier recognition of potential diagnostic delays.**

---

## Overview

What if Electronic Health Records could automatically recognise when a patient repeatedly presents with the same unresolved symptoms before a serious diagnosis is delayed?

This project explores that question by digitally operationalising **Jess's Rule**, transforming the NHS *"three strikes and rethink"* principle into a transparent, rule-based clinical decision support prototype.

Using simulated Electronic Health Record (EHR) data, the system analyses repeat patient presentations, identifies clinically significant patterns across multiple visits, and generates intelligent alerts to support earlier clinical review in primary and urgent care settings.

This project was developed as my final-year **BSc Computer Science dissertation** at the **University of West London**, where I graduated with **First Class Honours** and was recognised as an **Outstanding Graduate**.

---

## Research Context

### Dissertation Title

**Digital Automation of Jess's Rule: A Smart Alert System to Detect Repeat Patient Visits and Prevent Diagnostic Delays in Primary and Urgent Care**

This project combines software development, health informatics and clinical decision support to explore how existing healthcare data could be used more effectively to improve patient safety.

---

## Why This Project Matters

Patients with persistent or recurring symptoms may attend healthcare services several times before an underlying condition is recognised.

Although Electronic Health Records contain valuable information about previous encounters, clinicians often work in fast-paced environments where recognising patterns across multiple consultations can be challenging.

Following the death of **Jessica Boniface**, **Jess's Rule** was introduced across the NHS to encourage healthcare professionals to **"three strikes and rethink"** whenever patients repeatedly present with unresolved symptoms.

While this represents an important patient safety initiative, there is currently no widely available digital solution specifically designed to automate the identification of these repeat presentations within Electronic Health Record systems.

This project explores one possible approach.

---

## The Solution

The prototype analyses simulated Electronic Health Record data using transparent, rule-based logic to identify patients whose repeated presentations may warrant further clinical review.

Rather than replacing clinical judgement, it acts as a clinical decision support tool by highlighting presentation patterns that might otherwise be overlooked.

The system evaluates:

- Symptom similarity across patient visits
- Resolution status of previous encounters
- Number of repeat presentations
- Time between visits using configurable monitoring windows (30, 90 and 180 days)

Based on these criteria, the prototype generates three levels of alerts:

- 🟢 **Green** – Routine monitoring
- 🟠 **Amber** – Monitor closely
- 🔴 **Red** – Escalation recommended

The objective is to support earlier recognition of potential diagnostic delays while maintaining transparent, interpretable decision logic.

---

## Demonstration

🎥 **Watch the prototype in action**

https://youtu.be/smSS2uq9dUo

📖 **Read the full project article on Medium**

**Can Electronic Health Records Help Detect Diagnostic Delays Before They're Missed?**

https://medium.com/@haptunde/can-electronic-health-records-help-detect-diagnostic-delays-before-theyre-missed-3024f83e2ed4

---

## Technologies Used

- Python
- Gradio
- Figma
- PyCharm
- Google Forms

---

## Evaluation

The prototype was evaluated through both functional testing and user evaluation.

### Functional Testing

- Successfully implemented a working proof-of-concept prototype
- Passed all five predefined scenario-based functional test cases
- Produced consistent rule-based outputs across all test scenarios

### User Evaluation

Twenty-six NHS clinical and operational professionals evaluated the prototype using a structured questionnaire.

**Key findings:**

- ⭐ Understanding: **4.50 / 5**
- ⭐ Ease of use: **4.31 / 5**
- ⭐ Perceived clinical usefulness: **4.15 / 5**
- ⭐ **19 of 26 participants** agreed the prototype could help identify patients who may be at risk of diagnostic delay.

Although further validation using real-world clinical data would be required, these findings suggest that transparent rule-based approaches can provide understandable and clinically relevant decision support.

---

## Future Development

Potential future enhancements include:

- Integration with Electronic Health Record systems
- Automated patient record screening
- Natural Language Processing (NLP) for symptom recognition
- Machine learning-assisted risk prediction
- Validation using real-world NHS datasets
- Integration into clinical workflows following appropriate governance and regulatory approval

---

## Skills Demonstrated

- Python Programming
- Clinical Decision Support Systems
- Rule-Based System Design
- Health Informatics
- Software Prototyping
- Human-Centred Design
- User Interface Design
- Usability Evaluation
- Research Methods
- Technical Documentation

---

## About the Project

This project was independently conceived, designed and developed as an academic proof of concept inspired by my interest in digital health, patient safety and clinical decision support.

It reflects my passion for applying computing to real-world healthcare challenges and exploring how technology can support safer clinical decision-making without replacing professional judgement.

---

## Source Code

The source code is not currently publicly available while future development opportunities are being explored.

This repository provides an overview of the project together with a demonstration of the working prototype.

---

## Disclaimer

This project is an academic proof of concept developed exclusively using simulated Electronic Health Record data.

It is intended for research and educational purposes only and is **not** designed for direct clinical use or deployment within NHS systems without further development, clinical validation, regulatory approval and appropriate safety assurance.

---

## Connect

If you're interested in digital health, clinical informatics, patient safety or healthcare technology, I'd be delighted to connect.

- 💼 **LinkedIn:** https://www.linkedin.com/in/happiness-adenekan-046621267
- ✍🏽 **Medium:** https://medium.com/@haptunde
- 🎥 **YouTube:** https://youtu.be/smSS2uq9dUo

---

*Thank you for visiting this repository. Feedback, discussion and collaboration are always welcome.*
