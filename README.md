# Digital Automation of Jess's Rule

What if Electronic Health Records could automatically recognise when a patient keeps returning with the same unresolved symptoms before a serious diagnosis is missed?

This project explores that question by digitally operationalising **Jess's Rule**, transforming the NHS "three strikes and rethink" principle into a transparent, rule-based clinical decision support prototype.

Using simulated Electronic Health Record (EHR) data, the system detects repeated unresolved patient presentations, identifies patterns across multiple visits, and generates intelligent alerts that could support earlier recognition of potential diagnostic delays in primary and urgent care.

---

## Research Context

This project was independently conceived, designed, and developed as my final-year BSc Computer Science dissertation at the University of West London.

**Dissertation Title**

**Digital Automation of Jess's Rule: A Smart Alert System to Detect Repeat Patient Visits and Prevent Diagnostic Delays in Primary and Urgent Care**

The work combines software development, health informatics, and clinical decision support to explore how existing NHS data could be used more intelligently to improve patient safety.

---

# Why This Project Matters

Every day, patients return to healthcare services with symptoms that have not been resolved.

Although Electronic Health Records contain a complete history of previous visits, clinicians often work under significant time pressure and may not immediately recognise patterns that develop across multiple consultations.

Jess's Rule, introduced by NHS England following the death of Jessica Boniface, encourages clinicians to **"three strikes and rethink"** whenever patients repeatedly present with unresolved symptoms.

Despite this important patient safety initiative, there is currently no widely available digital system that automatically identifies these repeat presentations.

This project explores how that gap could be addressed.

---

# The Solution

I designed and developed a rule-based smart alert prototype that analyses simulated Electronic Health Record data and automatically identifies clinically significant repeat presentations.

Rather than replacing clinical judgement, the prototype acts as a decision support tool by highlighting patients whose presentation history may warrant further review.

The system evaluates:

- Symptom similarity across visits
- Resolution status of previous encounters
- Number of repeat presentations
- Time between visits using configurable monitoring windows (30, 90 and 180 days)

Based on these criteria, the system generates three levels of clinical alerts:

🟢 **Green** – Routine monitoring

🟠 **Amber** – Monitor closely

🔴 **Red** – Escalation recommended

The objective is to help clinicians recognise potential diagnostic delays earlier while reducing unnecessary alerts through transparent rule-based logic.

---

# Watch the Prototype

A demonstration of the working prototype is available here:

🎥 https://youtu.be/smSS2uq9dUo

---

# Technologies Used

- Python 3
- Gradio
- Figma
- PyCharm
- Google Forms (questionnaire design and analysis)

---

# Project Evaluation

The prototype was evaluated through both technical testing and user feedback.

### Functional Testing

- Successfully implemented a working proof-of-concept prototype
- Successfully passed all five predefined scenario-based functional test cases

### User Evaluation

The system was evaluated by **26 NHS clinical and operational professionals**.

Key findings included:

- **4.50 / 5** average understanding score
- **4.31 / 5** average ease of use score
- **4.15 / 5** average perceived clinical usefulness score
- **19 of 26 participants** agreed the system could help identify patients at risk of diagnostic delay

These findings suggest that the prototype was considered understandable, usable, and clinically relevant as an early-stage proof of concept.

---

# Future Development

Potential future enhancements include:

- Integration with NHS Electronic Health Record systems
- Automated patient record screening
- Intelligent symptom matching using Natural Language Processing (NLP)
- Machine learning-assisted risk prediction
- Clinical validation using real-world NHS datasets
- Integration into existing NHS clinical workflows

---

# Skills Demonstrated

- Python Programming
- Clinical Decision Support Systems
- Rule-Based System Design
- Health Informatics
- Software Prototyping
- User Interface Design
- Human-Centred Design
- Research Methods
- Usability Evaluation
- Technical Documentation

---

# About the Project

This project was independently conceived, designed, and implemented by me.

It was inspired by my interest in patient safety, healthcare technology, and the opportunity to explore how software can support earlier recognition of diagnostic risk through transparent and interpretable decision support.

---

# Source Code

The full source code is not currently publicly available while future development opportunities are being explored.

This repository provides an overview of the project together with a demonstration of the working prototype.

---

# Disclaimer

This project is an academic proof of concept developed exclusively using simulated patient data.

It is intended for research and educational purposes only and is not designed for direct clinical deployment without further development, validation, regulatory approval, and clinical evaluation.

---

# Let's Connect

If you are interested in digital health, clinical decision support, health informatics, or potential collaboration, I would be happy to connect and discuss this project further.
