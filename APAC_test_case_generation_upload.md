# Jira Test Case Creation and Upload File Generation

## Template Format

When creating the test cases and upload file on Jira. Follow the structured format below for consistency and completeness

### Basic Template for Description Field

```
Preconditions:
- [List any preconditions required for the test]

Test Scenario: 
- [Any specific test data required]

Action: 
- [What is the action required to execute the scenario]

Expected Results:
- [What is expected after executing the test]
```

NOTE: Include the APACINTAKE ticket in the Description field for traceability (e.g., "APACITINTAKE-3436").

## Best Practices

1. *Test Plan*: it should be the combination of the APACITINTAKE ticket and the ticket Summary
2. *Test Summary*: it should be the combination of the Test Plan: + Test Scenario
3. *Scenario Format*: Always follow the Gherkin syntax (Given-When-Then) for clear steps
4. *Description*: It should be a combination of Test Scenario and Preconditions
5. *Preconditions*: Be specific about environment state, data requirements, and user permissions
6. *Expected Results*: Define clear success criteria that can be verified
7. *Test Data*: Provide specific values or reference test data sources
8. *Test Priority*: it should be based on the criticality of the scenario


## Examples

### Example for Manual Test 
Test Plan: APACITINTAKE-3436: PRM Spex Check Outcome for Devices & Gadget
APACITINTAKE TICKET: APACITINTAKE-3436

Test Scenario:
-Verify MobileSwopFam customer will complete the ChurnSave Journey

Preconditions:
- User should have a non Mobile Starter program to complete
the Churnsave Journey

Action:
1. Log in to ChurnSave using mdn with non MobileStarter program
2. Click Cancel my subscription

Expected Results:
- Succesffully terminated the customer program

Test Priority:
- High

