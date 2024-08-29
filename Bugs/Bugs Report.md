# ecore
QA assessment - Bugs

# Bug report
- Title: BG001 - Application is allowing log in with invalid credential

- Description: When testing TC022, TC023 and TC024, the application is allowing a successful log in, after use back button functionality, even using INVALID credentials.

- Severity: Major

- Environment: QA/Pre-Prod

- Browser: Chrome, Edge and Chrome Mobile

- Steps to reproduce:
 1 - Open the web application
 2 - Insert a valid User and Password and click Login
 3 - After been successfully logged, hit the back button of the browser
 4 - Back in the log in home, insert now any INVALID credentials

- Expected behavior: the log in must fail

- Actual behavior: the application is allowing the log in with sucess

- Evidence: Check video attached

Note: the video is also published on my drive https://drive.google.com/file/d/1Vk9gY7ObBDdae9V0Zfp8eehF-VOwrK-Z/view?usp=sharing