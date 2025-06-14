# Bug Report: Sending an Order with an Empty Cart

| Category          | Label                 | Value                                               |
|-------------------|-----------------------|-----------------------------------------------------|
| **Bug ID**        | ID Number             | SwagLabs_06                                         |
| **Name**          |                       | Sending an Order with an Empty Cart                 |
| **Test Executed By** |                     | Marina Jakovljević                                  |
| **Submit Date**   |                       | 28-06-23                                            |

## Bug Overview

| Label           | Value                                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------|
| **Summary**     | The system allows submitting an order even when the cart is empty, without immediate validation or warning before submission. |
| **URL**         | [https://www.saucedemo.com/v1/index.html](https://www.saucedemo.com/v1/index.html)                 |
| **Screenshot**  | [Screenshot link](https://www.awesomescreenshot.com/video/18733937?key=f0facd0ee76521364e9d6299a714b0cd) |

## Environment

| Label           | Value                 |
|-----------------|-----------------------|
| **Platform**    | Web                   |
| **Operating system** | Microsoft Windows 10 Pro |
| **Browser**     | Google Chrome Version 114.0.5735.199 |

## Bug Details

| Label           | Value                                                                                      |
|-----------------|--------------------------------------------------------------------------------------------|
| **Steps to reproduce** | 1. Open the online store website  
2. Log in with valid credentials  
3. Navigate to the cart page  
4. Verify the cart is empty  
5. Proceed to checkout  
6. Enter required shipping info and click "Continue"  
7. Click "Finish" to submit order |
| **Expected result** | System should prevent submission and show an error message if the cart is empty.         |
| **Actual result**   | System allows submission of an order with an empty cart.                                  |
| **Description**    | Bug impacts cart functionality and order integrity by permitting empty orders.            |

## Bug Tracking

| Label           | Value                 |
|-----------------|-----------------------|
| **Severity**    | Major                 |
| **Assigned to** |                       |
| **Priority**    | High                  |

## Improvement Suggestion

| Label           | Value                                                                                              |
|-----------------|--------------------------------------------------------------------------------------------------|
| **Description of the improvement** | Implement client-side validation to block empty cart submissions, and show clear error messages and visual feedback to the user indicating the cart must contain items before placing an order. |
| **Rationale**    | Prevents confusion, avoids unnecessary processing of invalid orders, enhances user experience, and maintains order process integrity. |

