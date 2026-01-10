# 🏷️ Naming Convention

A consistent naming convention ensures that all Prompt Templates and Prompt Definitions remain easy to find, maintain and scale across the organization.

## 🎯 Purpose
- Human‑readable  
- Machine‑friendly  
- Predictable and scalable  
- Supports governance and version control  

## 🧩 Naming Pattern

[domain]--[use-case]--[type]--v[number]

### Elements
| Element | Meaning |
|---------|---------|
| **domain** | Functional area (e.g., customer-service, hr) |
| **use-case** | Specific task (e.g., order-status, onboarding-email) |
| **type** | `template` or `definition` |
| **v[number]** | Version number (v1, v2, …) |


## 📘 Examples
### Templates
customer-service--order-status--template--v1

hr--onboarding-email--template--v1



### Definitions

customer-service--order-status--definition--v1

hr--onboarding-email--definition--v1


## 🏛️ Rules
- Use lowercase  
- Use `--` between components  
- Use `-` inside words  
- Keep names short but descriptive  
- Always include a version number  
- Template and Definition share the same base name (domain + use-case)  

## 🗂️ Recommended Folder Structure

```text
/prompts
  /customer-service
    customer-service--order-status--template--v1.md
    customer-service--order-status--definition--v1.md

  /hr
    hr--onboarding-email--template--v1.md
    hr--onboarding-email--definition--v1.md

```


## 🔗 Related
- Layer 0: Core  
- Prompt Framework  
- Prompt Templates  
- Prompt Definitions  
