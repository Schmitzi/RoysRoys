# Notes for Testing Presentation<br>
## Slide 2: Tier 1 - Intended Use Cases<br>
### Description: <br>
Tier 1 focuses on the primary and most common scenarios that the software is designed to handle.<br>
### Example:<br>
For example, think about a login function that processes valid usernames and passwords smoothly.<br>
<br>
### Importance:<br>
Why is this important? These tests confirm that our core functionalities work as expected for the majority of users.<br>
<br>
### Additional Points:<br>
This tier ensures that the basic, expected operations are flawless, forming the foundation of user trust in the software.<br>
<br>
## Slide 3: Tier 2 - Alternative Use Cases<br>
### Description:<br>
Tier 2 testing covers alternative use cases, which are less common but still valid scenarios.<br>
<br>
### Example:<br>
For instance, a login function that handles usernames with special characters or different formats.<br>
<br>
### Importance:<br>
This tier is crucial because it ensures flexibility and robustness in handling a wider range of valid inputs.<br>
<br>
### Additional Points:<br>
By accounting for these variations, we enhance the user experience and prevent potential issues from overlooked edge conditions.<br>
<br>
## Slide 4: Tier 3 - Edge Cases<br>
### Description:<br>
Edge cases are at the boundary of what is considered valid input.<br>
<br>
### Example:<br>
Testing the login function with the shortest and longest possible passwords.<br>
<br>
### Importance:<br>
These tests are vital for understanding the limits of our system and ensuring it can handle inputs at the extreme ends.<br>
<br>
### Additional Points:<br>
Identifying how the software behaves in these scenarios helps prevent crashes or unexpected behavior in real-world use.<br>
<br>
## Slide 5: Tier 4 - Negative Cases<br>
### Description:<br>
Negative cases involve inputs and scenarios that the system should reject or handle gracefully.<br>
### Example:<br>
Examples include attempting to log in with incorrect passwords or trying to exploit the system with SQL injection.<br>
<br>
### Importance:<br>
"These tests ensure the system's security and robustness by validating how it handles invalid or malicious inputs."<br>
<br>
### Additional Points:<br>
"A strong defense against invalid operations protects both the system and its users, maintaining integrity and trust."<br>
<br>
## Slide 6: Tier 5 - Validation and Error Handling Cases<br>
### Description:<br>
Tier 5 evaluates how the system handles validation and error scenarios, such as checking if an email already exists or processing invalid payment methods."<br>
### Example: <br>
"For instance, attempting to sign up with an email that is already in use or trying to complete a transaction with an invalid credit card number."<br>
<br>
### Importance:<br>
"These tests are crucial for ensuring that the system provides clear, informative feedback to users and maintains data integrity."<br>
<br>
### Additional Points:<br>
"Validation tests check if the system correctly identifies and responds to specific user input errors."<br>
"By catching errors such as existing emails during sign-up, the system can prompt users to choose a different email, thereby preventing duplicate accounts."<br>
"Proper handling of invalid payment methods not only prevents transaction failures but also protects against potential fraud attempts."<br>
"Ensuring that validation checks work correctly helps maintain the integrity of the user database and transaction records."<br>
"Effective error messages guide users to correct their input, enhancing usability and reducing frustration."<br>
<br>
### Additional Example:<br>
#### Scenario: Testing the system’s response when a user tries to sign up with an email already associated with an account.<br>
#### Response: The system should inform the user that the email is already in use and suggest options such as logging in or using a different email.<br>


