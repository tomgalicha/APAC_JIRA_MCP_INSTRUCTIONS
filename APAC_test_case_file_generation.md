# Test Case file generation

## IMPORTANT: Wait for Go Signal
**DO NOT create the Excel file automatically. Always wait for explicit confirmation or "go signal" from the user before proceeding with Excel file generation.**

## IMPORTANT: Display the test cases first
**Always display the test cases first before the excel file generation.**

Ask the user: "Ready to create the Excel file? Please confirm to proceed."

#### Step 1: Generate excel file for the generated test cases

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

