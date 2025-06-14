# Test Scenarios and Test Cases for Swag Labs Store Website  
Project Name: **Swag Labs Store Website**  
URL: [www.saucedemo.com](https://www.saucedemo.com)  
Created By: Marina Jakovljević  
Creation Date: 28.6.2023.

| Test Scenario ID | Test Scenario Description                             | Test Case ID | Test Case Description                              | Test Steps                                                                                                                                                    | Preconditions                               | Test Data                                 | Post Condition                | Expected Result                                                 | Test passed/failed |
|-----------------|------------------------------------------------------|--------------|---------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|-------------------------------------------|------------------------------|----------------------------------------------------------------|--------------------|
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_001    | Enter valid Username and valid Password            | 1. Open the webpage  
2. Enter valid Username  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: standard_user  
Password: secret_sauce                  | User will land to the Home Page  | Home Page (Products)                                          | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_002    | Enter valid Username and invalid Password          | 1. Open the webpage  
2. Enter valid Username  
3. Enter invalid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: standard_user  
Password: secret_sauce123             | Epic sadface: Username and password do not match any user in this service | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_003    | Enter invalid Username and valid Password          | 1. Open the webpage  
2. Enter invalid Username  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: standard_user123  
Password: secret_sauce               | Epic sadface: Username and password do not match any user in this service | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_004    | Enter invalid Username and invalid Password        | 1. Open the webpage  
2. Enter invalid Username  
3. Enter invalid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: standard_user123  
Password: secret_sauce123           | Epic sadface: Username and password do not match any user in this service | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_005    | Login with empty Username field and empty Password field | 1. Open the webpage  
2. Empty Username field  
3. Empty Password field  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page                     | Username:  
Password:                                   | Epic sadface: Username is required              | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_006    | Login with valid Username and empty Password field | 1. Open the webpage  
2. Enter valid Username  
3. Empty Password field  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: standard_user  
Password:                                   | Epic sadface: Password is required              | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_007    | Login with empty Username field and valid Password | 1. Open the webpage  
2. Empty Username field  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username:  
Password: secret_sauce                     | Epic sadface: Username is required              | Unsuccessful login                                           | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_008    | Enter second valid username and valid Password    | 1. Open the webpage  
2. Enter second valid Username  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: locked_out_user  
Password: secret_sauce                 | Epic sadface: Sorry, this user has been locked out. | Home Page (Products)                                        | Failed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_009    | Enter third valid username and valid Password     | 1. Open the webpage  
2. Enter third valid Username  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: problem_user  
Password: secret_sauce                | User will land to the Home Page                     | Home Page (Products)                                          | Passed             |
| TS_001          | Verify the "Login" functionality of Swag Labs Store | TC_LI_010    | Enter fourth valid username and valid Password    | 1. Open the webpage  
2. Enter fourth valid Username  
3. Enter valid Password  
4. Click on LOGIN                                                                                                         | 1. Valid URL of Login Page  
2. Test Data                                | Username: performance_glitch_user  
Password: secret_sauce            | User will land to the Home Page                     | Home Page (Products)                                          | Passed             |

<!-- Za svaki sledeći scenario isto možeš ovako nastaviti -->

