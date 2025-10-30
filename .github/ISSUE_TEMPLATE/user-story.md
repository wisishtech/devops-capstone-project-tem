**As a** new user  
**I need** to create an account with email and password  
**So that** I can access personalized features and save my preferences  

### Details and Assumptions
* Email must be unique and valid format
* Password must be at least 8 characters
* Confirmation email will be sent after registration
* User can optionally add profile picture later

### Acceptance Criteria
```gherkin
Given I am on the registration page
When I enter a valid email and password
And I click the "Sign Up" button
Then my account is created
And I receive a confirmation email
And I am redirected to my dashboard
```
