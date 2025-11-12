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

#### Step 2: Generate excel file for the generated test cases

When creating generated excel file for the file name refer on the sample file name

Excel Filename should be on this format: APACITINTAKE - 3333: Churn Save Flow - Hardstop for Starter Programs Test Scenarios.


# Excel file content
Sheet 1 name should be: HL and Detailed Test Cases iWeb

Column fields on the excel file sheet 1
1. *TCID*: Test Case ID usually the numbering of the test cases
2. *Test Summary*: it should be the combination of the Test Plan: + Test Scenario
3. *Description*: It should be a combination of Test Scenario and Preconditions
4. *Test Scenario*: it should be the generated scenarios
5. *Pre-condition*: Be specific about environment state, data requirements, and user permissions
6. *Action*: it should be steps on executing the scenario
7. *Result*: it should be the expected result
8. *Status*: For Review
9. *Test Repository*: null
10. *Test Type*: Manual
11. *Test Priority*: it should based on the criticality of the scenario
12. *Test Plan*: it should be the combination of the APACITINTAKE ticket and the ticket Summary
13. *Test Plan Summary*: it should be the combination of the APACITINTAKE ticket and the ticket Summary
14. *Assignee*: username of the jira user created the test cases
15. *Reviewer*: default to christine.biteng
16. *Component*: null
17. *In Scope*: default to Yes
18. *Test Script Planning Complexity*: it should based on the criticality of the scenario
19. *Test Script Execution Complexity*: it should based on the criticality of the scenario
20. *Link To Requirement*: This should be the ticket reference of the scenarios.


Sheet 2 name should be: Test Cases
Column fields on the excel file sheet 2
1. *TCID*: Test Case ID usually the numbering of the test cases
2. *Test Scenario*: it should be the generated scenarios
3. *Result*: it should be the expected result
4. *Test Scenario Type*: Identification if the scenario is happy path or negative test 

TEST COMMIT
