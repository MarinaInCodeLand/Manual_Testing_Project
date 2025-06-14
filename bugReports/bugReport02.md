# Bug Report

**Bug ID:** SwagLabs_02  
**Bug Name:** The blocked username is listed as acceptable for entry.  
**Test Executed By:** Marina Jakovljević  
**Submit Date:** 28-06-2023  

## Bug Overview

**Summary:**  
It is stated on the website that the following usernames are accepted:  
- standard_user  
- locked_out_user  
- problem_user  
- performance_glitch_user  

Upon entering the username: **locked_out_user**, the message  
*'Sorry, this user has been locked out'* is displayed.

**URL:**  
[https://www.saucedemo.com/v1/index.html](https://www.saucedemo.com/v1/index.html)

**Screenshot:**  
[https://tinyurl.com/2723tqqd](https://tinyurl.com/2723tqqd)

## Environment

- **Platform:** Web  
- **Operating system:** Microsoft Windows 10 Pro  
- **Browser:** Google Chrome Version 114.0.5735.199  

## Bug Details

**Steps to reproduce:**  
1. Navigate to the login page: `https://www.saucedemo.com/v1/index.html`  
2. Enter username: `locked_out_user`  
3. Enter password: `secret_sauce`  
4. Click on the **Login** button.

**Expected result:**  
The website should **not** list the username as acceptable if it is actually locked out.

**Actual result:**  
The username is presented as acceptable for entry, leading users to believe it can be used. However, upon entering the username, an error message is displayed stating that the user has been locked out.

**Description:**  
A bug related to the login functionality – login with a locked-out username.

## Bug Tracking

- **Severity:** Major  
- **Assigned to:** *(not assigned)*  
- **Priority:** Medium  

## Improvement Suggestion

**Description of the improvement:**  
This bug significantly impacts the user experience and can lead to unnecessary login attempts with a locked-out username. It is crucial to address this issue by precisely indicating which usernames are acceptable during the entry process, offering clear instructions to users, and preventing any further confusion.

**Rationale:**  
This bug causes significant user confusion and frustration by misleadingly indicating a locked-out username as acceptable, resulting in wasted time and effort as users attempt to log in with it. By resolving this issue, we can enhance user satisfaction, reduce frustration, and optimize the efficiency of the login process.
