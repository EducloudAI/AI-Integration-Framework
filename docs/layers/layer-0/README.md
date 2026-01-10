# 🏗️ Layer 0: Core

## 📖 What is Layer 0?

**The foundation of everything.** Before you can manage, govern, or scale AI prompts, you need a consistent way to create them. Layer 0 provides that standard through a structured, repeatable process for transforming vague ideas into precise, executable AI instructions.

## 🎯 Why Layer 0 Matters

Without a standardized approach, organizations face:

- **Inconsistent results** from AI systems
- **Unrepeatable experiments** that can't be scaled
- **Hidden risks** in poorly defined prompts
- **Wasted resources** on trial-and-error prompting

Layer 0 solves this by using a universal set of 25 Prompt Questions that work across every sector, including healthcare, finance, education and government. It creates a common language that translates domain expertise into precise AI instructions, regardless of industry.

**Universal application examples:**
- **Healthcare:** Draft patient discharge instructions
- **Finance:** Generate regulatory compliance summaries  
- **Education:** Create personalized learning plans
- **Government:** Draft public service responses
- **Retail:** Generate product descriptions
- **Logistics:** Optimize delivery routes

## 🔧 The Prompt Framework: 25 Questions

The core of Layer 0 is a structured questionnaire with **25 carefully designed questions**, divided into two tiers:

### 📋 Tier 1: The Essentials (10 Questions)
**For everyday AI tasks and non-critical processes.**

| # | Question | Purpose | Example Answer |
|---|----------|---------|----------------|
| 1 | Task Description | What should AI do? | "Generate first-draft responses to customer FAQ about shipping" |
| 2 | Intended Use | Where/when will this be used? | "Internal helpdesk during peak hours" |
| 3 | Non-Intended Use | What shouldn't AI do? | "Make final decisions or process refunds" |
| 4 | Context | Background information | "We're an e-commerce store with 2-day delivery promise" |
| 5 | Input | What data does AI receive? | "Customer question + order number" |
| 6 | Output | What should AI produce? | "150-word draft response in friendly tone" |
| 7 | Quality Criteria | Success metrics | "Accurate, empathetic, includes tracking link" |
| 8 | Human Oversight | Who checks the output? | "Helpdesk supervisor reviews all responses" |
| 9 | Success Criteria | How do we know it works? | "30% faster response time, 90% supervisor approval" |
|10 | Constraints | Limits and boundaries | "No personal data, maximum 3 variations" |

### 🛡️ Tier 2: Advanced Governance (15 Questions)
**For critical business processes, regulated industries, or high-risk applications.**

Additional questions cover:
- **Risk Awareness** (alignment with EU AI Act)
- **Business Alignment** (KPIs and ROI)
- **Legal & Compliance** (jurisdiction-specific rules)
- **Version Control & Maintenance**
- **Ethical Considerations**

➡️ [View the complete 25-question list](prompt-questions.md)

---

## 🔧 The Prompt Framework

For a full explanation of the Prompt Framework, Prompt Templates and Prompt Definitions, see:

➡️ [Discover the Prompt Framework](prompt-framework.md)

---

## 🚀 How to Use the Framework

### Step 1: Choose Your Starting Point
- **For daily, non-critical tasks:** Use Tier 1 questions only (10 questions)
- **For business-critical, regulated, or high-risk applications:** Use both Tier 1 and Tier 2 (25 questions)

### Step 2: Answer the Questions
1. **Download** the appropriate template from `/templates/`
2. **Work collaboratively** with stakeholders (business, legal, IT)
3. **Be specific** - vague questions get vague answers
4. **Test early** with a small pilot

### Step 3: Create Your Prompt Definition

A filled template becomes a **Prompt Definition**, a living document that:
- Can be version controlled
- Is auditable
- Can be tested and validated
- Serves as a single source of truth

---

## ✅ The Three Components of Layer 0

Layer 0 produces three concrete artefacts that form the foundation for consistent and scalable prompt creation across an organization.

| # | Component | Function |
|---|-----------|----------|
| **1** | **Prompt Template** | The domain template. A fixed selection of relevant questions from the Prompt Framework, tailored to a specific domain (for example HR, Marketing, Customer Service). |
| **2** | **Prompt Definition** | The executable task. A fully completed Prompt Template for a specific use case, ready for testing, governance and deployment. |
| **3** | **Naming Convention** | The standard for how Prompt Templates and Prompt Definitions are named, ensuring everything remains findable, consistent and scalable. |


---



## 📊 Real-World Example

### Before: Vague Instruction
```
"Help me with customer service emails"
```

### After: Layer 0 Prompt Definition
### 📦 Example Prompt Definition (All 10 Tier‑1 Questions)

| # | Question | Answer |
|---|----------|---------|
| **1** | **Task Description** | Generate first‑draft responses to customer inquiries about order status. |
| **2** | **Intended Use** | Support ticket system during business hours (09:00–17:00 CET). |
| **3** | **Non Intended Use** | - AI must not send final answers to customers<br>- AI must not make decisions without human review<br>- AI does not replace customer service staff |
| **4** | **Context** | E‑commerce company with 10,000+ monthly orders and a 2‑day delivery promise. |
| **5** | **Input** | - Customer email text<br>- Order ID from database (if available)<br>- Relevant customer service guidelines |
| **6** | **Output** | Professional, empathetic draft response (100–150 words) including tracking information. |
| **7** | **Quality Criteria** | - Acknowledgement of the customer's question<br>- Accurate current order status<br>- Clear next steps<br>- Contact option for follow‑up<br>- Tone must be friendly and professional |
| **8** | **Human Oversight** | Customer service agent reviews, edits and sends the final response. |
| **9** | **Success Criteria** | - Reduces agent drafting time by 70%<br>- Maintains CSAT above 4.5 out of 5<br>- Improves consistency across all customer responses |
| **10** | **Constraints** | - No personal data exposure<br>- No promises beyond company policy<br>- Maximum of 2 response variations |

**Result:** Consistent, reliable AI outputs that align with business goals.

---

## 📁 Templates & Resources

### Ready-to-Use Templates

| Template | Format | Best For |
|----------|--------|----------|
| [📥 Prompt Framework Template](../templates/prompt-framework-template.xlsx) | Excel | Collaborative business teams |
| [📥 Prompt Definition JSON](../templates/prompt-definition.json) | JSON | Developers & automated systems |
| [📖 Quick Start Guide](../templates/quick-start-guide.md) | Markdown | Fast prototyping |

### Example Implementations

- [👨‍💼 Customer Service Assistant](../examples/customer-service/)
- [👥 HR Onboarding Bot](../examples/hr-onboarding/)
- [📢 Marketing Content Generator](../examples/marketing-content/)

## 🎓 Learning Path

### For Beginners
1. Start with **Tier 1 questions only**
2. Practice with non-critical use cases
3. Review the [example implementations](../examples/)

### For Advanced Users
1. Master both Tier 1 and Tier 2
2. Implement version control for Prompt Definitions
3. Integrate with your CI/CD pipeline (Layer 5)

## 🔗 Next Steps

Once you've mastered Layer 0, proceed to:

**→ [Layer 1: Metadata & Governance](../layer-1-metadata-governance/)**  
*Add tracking, ownership, and compliance to your prompts*

---

## ❓ Frequently Asked Questions

**Q: Do I need to answer all 25 questions every time?**  
A: No. Use Tier 1 for daily tasks. Tier 2 is for critical/high-risk applications.

**Q: How long does it take to create a Prompt Definition?**  
A: 15-30 minutes for Tier 1, 60-90 minutes for Tier 1+2.

**Q: Can I modify the questions?**  
A: Yes! The framework is adaptable. Document any changes in your organization's version.

**Q: What if I don't know all the answers?**  
A: That's the point! The framework reveals knowledge gaps. Use it to identify what you need to clarify with stakeholders.

---

## 📝 Contribution & Feedback

Found an issue? Have a suggestion?

- [Open an Issue](https://github.com/EducloudAI/AI-Integration-Framework/issues)
- [Submit a Pull Request](https://github.com/EducloudAI/AI-Integration-Framework/pulls)
- [Join the Discussion](https://github.com/EducloudAI/AI-Integration-Framework/discussions)

*Maintained by [EducloudAI](https://educloud-ai.vercel.app/)*
