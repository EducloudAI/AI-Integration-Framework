# 👨‍💼 Customer Service Assistant Example

## Overview
A complete implementation example using **Layer 0: Core Prompt Framework** to create an AI-powered customer service assistant for an e-commerce company.

## Business Context
**Company:** Shoppie (fictional e-commerce clothing retailer)  
**Challenge:** High volume of repetitive customer inquiries, inconsistent responses, and slow resolution times.  
**Solution:** AI assistant that generates first-draft responses for common customer questions.

## Prompt Definition

### Tier 1: Essentials
| Question | Answer |
|----------|--------|
| **Task Description** | Generate first-draft responses to common customer inquiries about orders, shipping, and returns |
| **Intended Use** | Internal helpdesk system during business hours (9 AM - 6 PM CET) |
| **Non-Intended Use** | Not for handling complaints, refund decisions, or personal data updates |
| **Context** | E-commerce clothing retailer with 10,000+ monthly orders, 2-day delivery promise, 30-day return policy |
| **Input** | Customer email text + order ID (to fetch order details from database) |
| **Output** | Professional, empathetic draft response (100-150 words) with tracking info and next steps |
| **Quality Criteria** | Accurate information, empathetic tone, includes tracking link if available, under 2 minutes to review |
| **Human Oversight** | Customer service agent reviews, edits if needed, then sends to customer |
| **Success Criteria** | Reduces agent drafting time by 70%, maintains CSAT > 4.5/5, consistent brand voice |
| **Constraints** | No financial advice, no promises beyond store policy, no personal data exposure |

### Tier 2: Advanced Governance
| Question | Answer |
|----------|--------|
| **Risk Awareness** | Medium risk - incorrect shipping info could cause customer dissatisfaction |
| **Business Alignment** | Supports KPI: "First Contact Resolution Rate" and "Average Handling Time" |
| **Legal Compliance** | GDPR compliant (customer data handling), right to accurate information |
| **Ethical Considerations** | Fair treatment for all customer segments, no bias in response quality |
| **Data Governance** | Uses only order database (no external sources), 90-day data retention |

## Implementation

### Excel Template Usage
1. **Download** `prompt-framework-template.xlsx`
2. **Open Sheet 3: Sector Templates**
3. **Select "Retail" template** (pre-filled with e-commerce examples)
4. **Customize** for your specific business context

### JSON Output (Generated from Template)
```json
{
  "task_description": "Generate first-draft responses to common customer inquiries",
  "intended_use": "Internal helpdesk system 9-18 CET",
  "context": "E-commerce clothing retailer with 10k+ monthly orders",
  "quality_criteria": "Accurate, empathetic, includes tracking link",
  "human_oversight": "Agent reviews before sending"
}

## Results & Metrics

- **Before AI:** 15 minutes average per email response
- **After AI:** 5 minutes average (67% reduction)
- **Consistency:** 95% brand voice alignment (vs. 70% previously)
- **Customer Satisfaction:** 4.6/5 average (maintained)

## Testing Scenarios

1. **Order Status Inquiry** → Provides tracking info + expected delivery
2. **Return Request** → Explains return process + provides RMA number
3. **Size/Product Question** → Links to size guide + suggests alternatives
4. **Shipping Delay** → Apologizes + provides updated ETA + coupon if appropriate

## Integration Steps

1. **Start small:** Implement for 1-2 most common inquiry types
2. **Train team:** Conduct 30-minute workshop on AI collaboration
3. **Monitor:** Weekly review of AI-generated drafts
4. **Iterate:** Update prompt based on agent feedback

## Files in This Example

- `prompt-definition.json` - Complete prompt specification
- `sample-conversations.md` - Real customer-AI interaction examples
- `implementation-guide.md` - Step-by-step rollout plan

## Related Resources

- [Layer 0 Documentation](../docs/layer-0-core/README.md)
- [Excel Template](../../templates/prompt-framework-template.xlsx)
- [HR Onboarding Example](../hr-onboarding/README.md)
- [Marketing Content Example](../marketing-content/README.md)
