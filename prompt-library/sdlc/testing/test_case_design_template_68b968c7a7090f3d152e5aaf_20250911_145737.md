---
title: Test Case Design Template
weight: 45
---

Structured template for creating comprehensive test cases

```
# Test Case Design Template

## Test Case Information
- **Test Case ID**: TC_[MODULE]_[NUMBER]
- **Test Case Title**: [DESCRIPTIVE TITLE]
- **Module/Feature**: [MODULE NAME]
- **Priority**: High/Medium/Low
- **Test Type**: Functional/Integration/System/Regression

## Test Objective
**Purpose**: What is this test case trying to verify?

## Preconditions
- [ ] System is in [REQUIRED STATE]
- [ ] Test data is prepared
- [ ] User has [REQUIRED PERMISSIONS]
- [ ] Environment is configured correctly

## Test Data
| Field | Value | Notes |
|-------|-------|-------|
| [FIELD_NAME] | [TEST_VALUE] | [DESCRIPTION] |

## Test Steps
| Step | Action | Expected Result |
|------|--------|-----------------|
| 1 | [ACTION DESCRIPTION] | [EXPECTED OUTCOME] |
| 2 | [ACTION DESCRIPTION] | [EXPECTED OUTCOME] |
| 3 | [ACTION DESCRIPTION] | [EXPECTED OUTCOME] |

## Expected Results
- **Primary Result**: [MAIN EXPECTED OUTCOME]
- **Secondary Results**: [ADDITIONAL OUTCOMES]
- **System State**: [FINAL SYSTEM STATE]

## Actual Results
- **Status**: Pass/Fail/Blocked
- **Actual Outcome**: [WHAT ACTUALLY HAPPENED]
- **Screenshots**: [IF APPLICABLE]

## Defect Information (if failed)
- **Defect ID**: [DEFECT_ID]
- **Severity**: Critical/High/Medium/Low
- **Description**: [DEFECT DESCRIPTION]

## Post-conditions
- [ ] System returned to stable state
- [ ] Test data cleaned up
- [ ] Logs captured if needed

## Notes
[ADDITIONAL OBSERVATIONS OR COMMENTS]
```