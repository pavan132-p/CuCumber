This project focuses on automating and validating the Login Functionality and Buzz Post Creation in the OrangeHRM portal. The goal is to ensure that users can successfully log in with valid credentials, are restricted from logging in with invalid credentials, and can create a post in the Buzz section after a successful login. The project follows Behavior-Driven Development (BDD) using Cucumber and is implemented with structured test scenarios.

2. Objectives
Validate the login functionality for both successful and unsuccessful attempts.
Ensure secure authentication mechanisms by verifying incorrect login attempts.
Test the Buzz section's functionality, including searching for and creating posts.
Automate test execution using the Cucumber framework with Gherkin syntax for easy readability.
3. Features Covered in the Project
1. Login Functionality Testing
The login functionality ensures that users can access the OrangeHRM system securely.

Valid Login Case:

Users should be able to log in with the correct username and password.
Upon successful login, the system should redirect them to the OrangeHRM homepage.
Invalid Login Case:

If incorrect credentials are entered, the system should not grant access.
The user should remain on the login page with an error message.
2. Buzz Post Creation
The Buzz section in OrangeHRM allows users to post updates, similar to a social media feed.

Buzz Post Creation Process:
User logs in with valid credentials.
The system navigates to the Buzz section.
User searches for existing posts.
A new post is created and submitted.
The system verifies that the post is successfully created and displayed.
4. Technologies and Tools Used
Cucumber (BDD Framework) – Used for writing test cases in Gherkin syntax.
Selenium WebDriver – Automates browser interactions.
Java – Programming language for test automation.
TestNG – Used for managing test execution.
Maven – For dependency management and project build.
GitHub – Version control and repository management.
Extent Reports – Generates detailed test execution reports.
5. Test Scenarios and Steps
Feature: Testing OrangeHRM Login Functionality
Background:
Given the user is on the OrangeHRM login page

@PositiveTesting - Scenario: Login with Valid Credentials
Enter valid Username: "Admin"
Enter valid Password: "admin123"
Click the Login button
Verify that the user is redirected to the OrangeHRM homepage
@NegativeTesting - Scenario: Login with Invalid Credentials
Enter incorrect Username: "admin"
Enter incorrect Password: "AdMin13"
Click the Submit button
Verify that the user remains on the login page and does not access the homepage
@CreatingPost - Scenario: Posting on the Buzz Section
Enter valid Username: "Admin"
Enter valid Password: "admin123"
Click the Login button
Navigate to the Buzz section
Search for existing buzz posts
Create a new post: "I am Pavan"
Click the Post button
Verify that the post is successfully created
6. Expected Outcomes
The system should allow login only with valid credentials.
Invalid login attempts should prevent access and display an appropriate error message.
After logging in successfully, the user should be redirected to the OrangeHRM homepage.
Users should be able to navigate to the Buzz section and create posts successfully.
7. Benefits of the Project
✅ Ensures secure authentication by verifying login attempts.
✅ Improves user experience by validating login errors.
✅ Automates the Buzz post creation process, saving manual effort.
✅ Provides a structured testing approach using BDD and Cucumber.
✅ Generates detailed test execution reports for better analysis.

8. Conclusion
This project successfully automates and validates the login functionality and Buzz post creation in OrangeHRM.
[https://drive.google.com/drive/folders/1kUavpzG0VuJyaYVoDJm_bkxoCPpUmRZg?usp=drive_link]
