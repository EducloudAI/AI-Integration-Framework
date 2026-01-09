# Prompt Framework: A 25-Question Structure for Responsible AI

### 📋 Tier 1: The Essentials (10 Questions)
**For everyday AI tasks and non-critical processes.**

### 🛡️ Tier 2: Advanced Governance (15 Questions)
**For critical business processes, regulated industries, or high-risk applications.**


| #  | Tier | Question                 | Purpose                                              | Example Answer |
|----|------|--------------------------|------------------------------------------------------|----------------|
| 1  | 1 | Task Description          | What should AI do?                                   | "Generate first-draft responses to customer FAQ about shipping" |
| 2  | 1 | Intended Use              | Where and when will this be used?                    | "Internal helpdesk during peak hours" |
| 3  | 1 | Non-Intended Use          | What should AI not do?                               | "Make final decisions or process refunds" |
| 4  | 1 | Context                   | Provide relevant background information              | "We are an e-commerce store with a 2-day delivery promise" |
| 5  | 1 | Input                     | What data does AI receive?                           | "Customer question plus order number" |
| 6  | 1 | Output                    | What should AI produce?                              | "150-word draft response in a friendly tone" |
| 7  | 1 | Quality Criteria          | Define success and quality indicators                | "Accurate, empathetic, includes tracking link" |
| 8  | 1 | Human Oversight           | Who reviews or approves the output?                  | "Helpdesk supervisor reviews all responses" |
| 9  | 1 | Success Criteria          | How do we know it works?                             | "30% faster response time, 90% approval rate" |
| 10 | 1 | Constraints               | Define limits and boundaries                         | "No personal data, maximum three variations" |
| 11 | 2 | Risk Awareness            | Identify risks and mitigation measures               | "Human review required; automated risk flags enabled" |
| 12 | 2 | Business Alignment        | Connect to KPIs and strategic objectives             | "Supports KPI: reduced incident resolution time" |
| 13 | 2 | Legal Compliance          | Ensure regulatory alignment                          | "Complies with GDPR Art. 6 and EU AI Act transparency rules" |
| 14 | 2 | Ethical Considerations    | Address fairness, bias and accountability            | "Bias checks applied; reasoning steps documented" |
| 15 | 2 | Data Governance           | Define data sources, quality and lineage              | "Verified internal datasets; lineage tracked; PII masked" |
| 16 | 2 | Version Control           | Track changes and maintain history                   | "Semantic versioning in Git with full change log" |
| 17 | 2 | Testing Protocol          | Define validation and acceptance criteria             | "Safety and scenario tests; accuracy threshold ≥95%" |
| 18 | 2 | Performance Metrics       | Measure performance, cost and reliability             | "Latency <2s; accuracy >90%; cost <€0.01 per run" |
| 19 | 2 | Security Requirements     | Define access control and encryption                  | "RBAC enforced; encrypted at rest and in transit" |
| 20 | 2 | Audit Trail               | Ensure logging and traceability                       | "All interactions logged with timestamp and reviewer ID" |
| 21 | 2 | Stakeholder Roles         | Define RACI responsibilities                         | "Ops responsible; Manager accountable; Legal consulted" |
| 22 | 2 | Review Cycle              | Define reassessment frequency                         | "Quarterly review of risks and performance" |
| 23 | 2 | Escalation Path           | Define incident escalation procedures                | "Critical failures escalate within one hour" |
| 24 | 2 | Training Requirements     | Define competency and certification needs             | "AI Safety Level 1 training required before access" |
| 25 | 2 | Documentation Standards   | Define documentation format and maintenance           | "Stored centrally; updated on each version release" |

## 📥 Download Templates

### Excel Template (Recommended)
**[📥 prompt-framework-template.xlsx](https://github.com/EducloudAI/AI-Integration-Framework/raw/main/templates/prompt-framework-template.xlsx)**

*The Complete the 25 Prompt Questions with:*
- Sector-specific examples (Healthcare, Finance, Education)
- AI Act compliance checklist
- Auto-quality scoring
- Structured export formats such as JSON and YAML

### JSON Template (for Developers)
**[📄 prompt-definition.json](../../templates/prompt-definition.json)**  

*Machine-readable format for API integration:*
- Structured JSON schema
- Compatible with CI/CD pipelines
- Version control ready
- Easy to parse programmatically

### Online Collaborative Version
*For now, download the Excel template or JSON file and share with your team*  
*Google Sheets collaborative version coming soon*

- ### Quick Start Guide
**[📖 quick-start-guide.md](../../templates/quick-start-guide.md)**  
*5-minute tutorial for beginners:*
- How to use the templates
- Tier 1 vs Tier 2 explained
- Real-world examples
- Next steps

## Usage Tips
- **Start with Tier 1** for most use cases
- **Add Tier 2 questions** when dealing with:
  - Regulatory compliance requirements
  - High-stakes business decisions
  - Customer-facing applications
  - Sensitive data processing

## Related Resources
- [Layer 0 Documentation](README.md) - Complete Layer 0 overview
- [Framework Home](../../README.md) - AI Integration Framework main page
- [Example: Customer Service Prompt](../../examples/customer-service/README.md)
- [Quick Start Guide](../../templates/quick-start-guide.md)
---

*Part of the [AI Integration Framework](https://github.com/EducloudAI/AI-Integration-Framework)*
