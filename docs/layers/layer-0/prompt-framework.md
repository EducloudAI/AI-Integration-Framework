# 📘 Prompt Framework, Prompt Templates and Prompt Definitions

The Prompt Framework is the foundation of Layer 0. It provides a structured and repeatable method for transforming vague ideas into precise, auditable and executable AI instructions. It ensures that every prompt, regardless of domain, complexity or risk level, is created with the same level of clarity, quality and governance.

---

## 🧱 1. The Prompt Framework (25 Questions)

The Prompt Framework consists of 25 universal questions, divided into two tiers.

### 📋 Tier 1: The Essentials (10 Questions)

For everyday AI tasks and non-critical processes.

### 🛡️ Tier 2: Advanced Governance (15 Questions)

For critical, regulated or high-risk applications.

These questions form a thinking structure that works across all roles and all domains. They help teams clarify:

- 🎯 What the AI must do  
- 📥 What inputs it needs  
- 📤 What outputs it must produce  
- ⭐ What quality expectations apply  
- ⚠️ What risks must be controlled  
- 👤 Who remains responsible  

---

## 🧩 2. Prompt Templates

A Prompt Template is a domain-specific selection of questions from the Prompt Framework.

Examples include:

- 📢 Marketing Template  
- 👥 HR Template  
- 🎧 Customer Service Template  
- 🚚 Logistics Template  

A Prompt Template:

- is not yet filled in  
- provides a fixed structure for a domain  
- ensures consistency across teams  
- acts as the blueprint for creating prompts in that domain  

Templates allow organizations to standardize prompting across departments while still adapting to domain-specific needs.

---

## 📝 3. Prompt Definitions

A Prompt Definition is a completed Prompt Template that contains concrete answers for a specific task.

Examples include:

- 📢 Marketing Social Media Post Prompt  
- 👥 HR Onboarding Prompt  
- 🎧 Customer Service Order Status Prompt  

A Prompt Definition is:

- ⚙️ executable  
- 🧪 testable  
- 🗂️ version controlled  
- 🔍 auditable  
- 🛡️ aligned with governance requirements  

It becomes the single source of truth for how AI should behave in that specific task.

---
## 🏛️ 4. Hierarchy of the Prompt Framework

The relationship between the three elements is clear and structured. Each level builds on the previous one and adds a new layer of specificity and operational value.


This hierarchy ensures:

- 🔄 Consistency across domains  
- 👥 Clarity for developers and business teams  
- 📑 Traceability for governance and compliance  
- 📈 Scalability across the entire organization  


### 📦 Overview of the Three Elements

| Element | Description |
|---------|-------------|
| **Prompt Framework** | All rules and all 25 universal questions. The complete thinking structure used across all domains. |
| **Prompt Template** | Domain template. A fixed selection of relevant questions tailored to a specific domain. |
| **Prompt Definitie** | Executable task. A fully completed template for a specific use case, ready for testing and deployment. |


---

## 📦 5. Example Prompt Definition

Below is an example Prompt Definition based on the first 10 questions of the Prompt Framework. This example illustrates how a vague instruction becomes a structured and high-quality prompt.

### 🛒 Example Prompt Definition: Webshop Customer Service Prompt

| # | Tier 1 Question | Answer for This Use Case |
|---|-----------------|--------------------------|
| **1** | **Task Description** | Support customer service agents by generating first‑draft responses to common customer questions. |
| **2** | **Intended Use** | Used internally to speed up response times and improve consistency. |
| **3** | **Non Intended Use** | - AI must not send final answers to customers<br>- AI must not make decisions without human review<br>- AI does not replace customer service staff |
| **4** | **Context** | Shoppie receives many similar questions about orders, deliveries and returns. Responses vary between agents. |
| **5** | **Input** | - Customer question<br>- Order number if available<br>- Relevant customer service guidelines |
| **6** | **Output** | A clear and friendly draft response that the agent reviews and adjusts. |
| **7** | **Quality Expectations** | - Accurate<br>- Relevant<br>- Consistent<br>- Professional and empathetic |
| **8** | **Human in the Loop** | A customer service agent reviews and approves the response before sending. |
| **9** | **Success Criteria** | - Agents understand the draft immediately<br>- Faster handling time<br>- More consistent customer communication |
| **10** | **Constraints** | No personal data exposure, no promises beyond policy, maximum 3 variations. |


---

## 📁 6. Resources

### Templates  
- 📥 Prompt Framework Template (Excel)  
- 📥 Prompt Definition Template (JSON)  
- 📖 Quick Start Guide (Markdown)  

### Examples  
- 👨‍💼 Customer Service Assistant  
- 👥 HR Onboarding Bot  
- 📢 Marketing Content Generator  

---

## 🔗 Next Steps

After mastering the Prompt Framework, continue with:

**➡️ Layer 1: Metadata and Governance**  
Add ownership, tracking and compliance to your prompts.


