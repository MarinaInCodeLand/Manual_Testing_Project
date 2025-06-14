# Bug Report

**Bug ID:** SwagLabs_01  
**Bug Name:** No indication that fields are required.  
**Test Executed By:** Marina Jakovljević  
**Submit Date:** 28-06-2023  

## Bug Overview

**Summary:**  
When attempting to log in without entering a username and password and clicking the **Login** button, there is no immediate indication that the username and password fields are required. The error message only appears **after** clicking the **Login** button, stating that the fields are mandatory.

**URL:**  
[https://www.saucedemo.com/v1/index.html](https://www.saucedemo.com/v1/index.html)

**Screenshot:**  
[https://tinyurl.com/239o758z](https://tinyurl.com/239o758z)

## Environment

- **Platform:** Web  
- **Operating System:** Microsoft Windows 10 Pro  
- **Browser:** Google Chrome Version 114.0.5735.199  

## Bug Details

**Steps to reproduce:**  
1. Navigate to the login page: `https://www.saucedemo.com/v1/index.html`  
2. Leave the username and password fields empty.  
3. Click the **Login** button.

**Expected result:**  
The user should see a prompt or visual indication that the username and password fields are mandatory **before** attempting to log in.

**Actual result:**  
The error message appears **only after** clicking the **Login** button, indicating the fields are required.

**Description:**  
A bug related to login functionality where no indication is provided upfront that username and password fields are mandatory.

## Bug Tracking

- **Severity:** Minor  
- **Priority:** Medium  
- **Assigned to:** *(not assigned)*  

## Improvement Suggestion

**Description:**  
Add visual indicators (like asterisks `*` or placeholder text) or labels to clearly mark the username and password input fields as mandatory during the login process.

**Rationale:**  
Currently, users are unaware that these fields are mandatory until they attempt to log in and receive an error notification. Adding visible mandatory field indicators will improve the user experience by reducing confusion, increasing efficiency, and prompting users to fill in the necessary information before clicking login.
