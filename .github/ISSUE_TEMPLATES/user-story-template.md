**As a** customer account manager
**I need** to be able to update customer information
**So that** I can ensure the accuracy of customer data and provide better service

### Details and Assumptions
* The customer information includes fields like name, address, contact details, etc.
* The system should validate and enforce data integrity rules during the update process.

### Acceptance Criteria
gherkin
Given an existing customer account with outdated address details
When I update the customer's address
Then the system should save the new address successfully
And I should receive a confirmation that the address has been updated
