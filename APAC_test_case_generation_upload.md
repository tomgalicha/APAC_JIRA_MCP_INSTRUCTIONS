# Jira Test Case Creation

**IMPORTANT: All test cases MUST be generated and presented in TABLE VIEW format for easy review and processing.**

**DO NOT create the Excel file automatically. Always wait for explicit confirmation or "go signal" from the user before proceeding with Excel file generation.**

**When go signal is received use APAC_test_case_file_generation.md file as instruction on generating excel file**

**DO NOT CREATE JIRA TICKET**

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


## Output Format Requirements

### Table View Generation
When generating test cases, **ALWAYS present them in table format** with the following columns:
- Test Plan
- Test Case ID
- Test Scenario
- Preconditions
- Action
- Expected Results
- Test Priority
- APACITINTAKE Ticket

The table should be clearly structured and easy to read, with each test case as a separate row.

## Examples

### Example for Manual Test 
#### Example Table Format:

TEST PLAN :  APACITINTAKE-3436: PRM Spex Check Outcome for Devices & Gadget 

|Test Case ID|Test Scenario | Preconditions | Action | Expected Results | Test Priority | APACITINTAKE Ticket |
|-----------|-----------|-------------|---------------|---------------|--------|------------------|---------------|-------------------|
|TST_001| Verify MobileSwopFam customer will complete the ChurnSave Journey | User should have a non Mobile Starter program to complete the Churnsave Journey | 1. Log in to ChurnSave using mdn with non MobileStarter program<br>2. Click Cancel my subscription | Successfully terminated the customer program | High | APACITINTAKE-3436 |
