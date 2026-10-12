# Marketplace Error Troubleshooting

A structured playbook for diagnosing **Amazon, Walmart, and multi-channel catalog errors**.

## Common Problem Types
- Missing required attributes
- Invalid category values
- Variation relationship issues
- Duplicate identifiers
- Conflicting product data
- Spreadsheet/feed upload failures
- Suppressed or incomplete listings
- Image/content requirement problems

## Included Files
- [Troubleshooting Playbook](troubleshooting_playbook.md)
- [Error Log Template](error_log_template.csv)

## Diagnostic Method

**Reproduce → Identify Scope → Validate Source Data → Check Marketplace Rules → Correct → Re-upload → Verify**

## Error Log Structure

| Marketplace | SKU | Error | Root Cause | Fix | Status |
|---|---|---|---|---|---|
| Demo | DEMO-001 | Required attribute missing | Source data incomplete | Populate required field | Resolved |

## Principle
Fix the **source data/root cause**, not only the visible symptom, so the error is not reintroduced in the next bulk update.

**Upwork:** https://www.upwork.com/freelancers/~0115a312ed543a19a1
