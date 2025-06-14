# Bug Report

**Bug ID:** SwagLabs_01  
**Bug Name:** No indication that fields are required.  
**Test Executed By:** Marina Jakovljević  
**Submit Date:** 28-06-2023  

## Bug Overview

**Summary:**  
When attempting to log in without entering a username and password and clicking the **Login** button, there is no immediate indication that the username and password fields are required. The error message only appears **after** clicking the **Login** button, stating that the fields are mandatory.

**URL:**  
# Bug Report: Failed Image Loading after Login

| Category          | Label                 | Value                                              |
|-------------------|-----------------------|----------------------------------------------------|
| **Bug ID**        | ID Number             | SwagLabs_03                                        |
| **Name**          |                       | Failed Image Loading after Login                   |
| **Test Executed By** |                     | Marina Jakovljević                                 |
| **Submit Date**   |                       | 28-06-23                                           |

## Bug Overview

| Label           | Value                                                                                       |
|-----------------|---------------------------------------------------------------------------------------------|
| **Summary**     | After successfully logging into the online store, product images fail to load on the pages. Instead, a placeholder image is shown, impacting user experience and purchase decisions. |
| **URL**         | [https://www.saucedemo.com/v1/inventory.html](https://www.saucedemo.com/v1/inventory.html)  |
| **Screenshot**  | [Screenshot link](https://tinyurl.com/28lkcnac)                                            |

## Environment

| Label           | Value                 |
|-----------------|-----------------------|
| **Platform**    | Web                   |
| **Operating system** | Microsoft Windows 10 Pro |
| **Browser**     | Google Chrome Version 114.0.5735.199 |

## Bug Details

| Label           | Value                                                                                     |
|-----------------|-------------------------------------------------------------------------------------------|
| **Steps to reproduce** | 1. Navigate to login page: `https://www.saucedemo.com/v1/index.html`  
2. Enter username: `problem_user`  
3. Enter password: `secret_sauce`  
4. Click the "Login" button. |
| **Expected result** | After login, product images should load and display correctly on the pages.           |
| **Actual result**   | After login, product images fail to load and are not displayed correctly on the page.  |
| **Description**    | Bug affects online store functionality and user experience due to missing product images.|

## Bug Tracking

| Label           | Value                 |
|-----------------|-----------------------|
| **Severity**    | Major                 |
| **Assigned to** |                       |
| **Priority**    | High                  |

## Improvement Suggestion

| Label           | Value                                                                                       |
|-----------------|---------------------------------------------------------------------------------------------|
| **Description of the improvement** | This bug significantly impacts the online store functionality and user experience due to lack of product visuals, which affects users' purchase decisions and can reduce sales. |
| **Rationale**    | Resolving this issue is critical to ensure product images load properly after login, maintaining user satisfaction and store operations. |

