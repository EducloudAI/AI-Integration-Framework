# 📘 Universal Questions — Complete Overview  

This page provides a practical, table‑based overview of the 25 Universal Questions.  
It complements the conceptual explanation by showing how each question is used in real components.

This format makes the Universal Questions directly applicable in workshops, templates, governance reviews and component design.

---

## 🔹 Clarity Questions (1–5)

| Question | Purpose | Example Answer |
|---------|----------|----------------|
| What is the goal of this component | Define purpose and direction | "Provide a clear summary of operational risks for managers" |
| Who is the intended user or stakeholder | Identify who benefits or interacts | "Operations managers and team leads" |
| What problem does this solve | Clarify the underlying need | "Fragmented incident information slows decision‑making" |
| What outcome should this produce | Define the expected result | "A concise, actionable overview of key issues" |
| What does success look like | Establish success criteria | "Managers can make decisions within 5 minutes" |

---

## 🔹 Quality Questions (6–10)

| Question | Purpose | Example Answer |
|---------|----------|----------------|
| How do we know this is correct | Define validation approach | "Cross‑check with source data and verify key fields for accuracy" |
| What tests or validations are required | Ensure reliability | "Run scenario tests and confirm consistent results across datasets" |
| What could cause inconsistent results | Identify instability | "Outdated context, missing fields or inconsistent ticket labeling" |
| What are the failure modes | Anticipate breakdowns | "Misclassified incidents, missing details or incorrect prioritization" |
| How do we ensure reproducibility | Guarantee consistent output | "Use fixed templates, version control and standardized inputs" |

---

## 🔹 Governance & Risk Questions (11–15)

| Question | Purpose | Example Answer |
|---------|----------|----------------|
| What risks are associated with this component | Identify potential harm | "Incorrect summaries could mislead managers" |
| Does this require human oversight | Define human‑in‑the‑loop | "Manager must approve all outputs" |
| Are there compliance or ethical considerations | Ensure responsible use | "Must comply with GDPR and internal audit rules" |
| What controls or safeguards are needed | Add protective measures | "Enable logging and restrict access to sensitive data" |
| Who is responsible for decisions and outcomes | Assign accountability | "Operations manager is accountable; analyst is responsible" |

---

## 🔹 Data & Context Questions (16–20)

| Question | Purpose | Example Answer |
|---------|----------|----------------|
| What data or context does this depend on | Identify required inputs | "Incident logs, capacity reports and customer tickets used to understand the operational situation" |
| Is the data fresh, accurate and authorized | Ensure data integrity | "Data is updated daily, validated by the operations team and only accessible to authorized staff" |
| What assumptions does this component rely on | Make implicit logic explicit | "Assumes ticket categories are consistently labeled and timestamps are reliable across all systems" |
| What happens if the context or data changes | Assess adaptability | "If data changes, the analysis must be re‑run and the manager notified of any significant differences" |
| What are the limitations of the data or inputs | Identify constraints | "Some inputs lack real‑time GPS data or complete customer history, which may limit precision" |

---

## 🔹 Value & Impact Questions (21–25)

| Question | Purpose | Example Answer |
|---------|----------|----------------|
| How does this create value | Connect to business outcomes | "Reduces decision time and improves reliability" |
| Which KPI or objective does this influence | Link to measurable goals | "Supports OTIF and incident resolution KPIs" |
| How will we measure success | Define metrics | "Time‑to‑decision and accuracy of summaries" |
| What is the expected impact on users or processes | Describe operational effect | "Managers gain clarity faster and escalate less" |
| What happens if this component fails or underperforms | Assess risk of failure | "Delayed decisions and increased operational risk" |

---

# 🌟 How to Use This Table

This overview is designed for:

- component design  
- governance reviews  
- training and workshops  
- maturity assessments  
- documentation generation  
- cross‑functional alignment  

It provides a practical, ready‑to‑use reference for applying the Universal Questions across all layers and components of the AI Integration Framework.

---

## 📎 Related Pages

- [The Five Categories of Universal Questions](five-categories.md)  
- [Integration Across the Framework](framework-integration.md)  
- [Prompt Framework (Layer 0)](../layers/layer-0/)  

