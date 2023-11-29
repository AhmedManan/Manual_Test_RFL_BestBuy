# RFL Best Buy User Management Module Test Report

Welcome to the Test Report for the RFL Best Buy User Management Module. This document provides a comprehensive overview of the testing process, test metrics, SQA Mind Map, Test Cases, and Bug Reports related to the User Management Module.

## Table of Contents
- [Introduction](#introduction)
- [Features Tested](#features-tested)
- [Test Metrics](#test-metrics)
- [Test Cases](#test-cases)
- [SQA Mind Map](#sqa-mind-map)
- [Bug Report](#bug-report)

## Introduction
The RFL Best Buy User Management Module is a critical component of our application responsible for managing user accounts and authentication. This test report aims to ensure the reliability, functionality, and security of this module. URL: https://rflbestbuy.com/

## Features Tested
We have thoroughly tested the following features of the User Management Module:

1. **Profies Add**
   - Ensure new users can register with valid information.
   - Verify email confirmation process.

2. **User Sign In**
   - Confirm users can log in with valid credentials.
   - Validate password recovery functionality.

3. **User Sign In -> Forget Password**
   - Test the assignment and revocation of Forget Password option.

## Test Metrics
During the testing process, we collected the following metrics to evaluate the quality of the User Management Module:

- **Percentage of Test Case Executed:** 100%
- **Test Cases Executed:** 48 out of 48
- **Pass Percentage:** 85.42%
- **Fail Percentage:** 14.58%
- **Percentage of Test Case Blocked:** 0%
- **Bug Severity Distribution:** (See Bug Report Section)

## Test Cases
We have designed and executed a set of test cases to validate the functionality of the User Management Module. Here are some representative test cases:

1. **Profiles Add**
   - **Test Objective:** To verify that a new user can successfully register.
   - **Test Cases:**
     ![Profiles Add Test Cases](Screenshots/profiles_add.png)

2. **User Sign In**
   - **Test Objective:** To confirm that a registered user can log in.
   - **Test Cases:**
     ![Sign In Test Cases](Screenshots/sign_in.png)

For a complete list of test cases, please refer to the [Test Case Documentation](RFL_Best_Buy.xlsx).

## SQA Mind Map
![SQA Mind Map](Mindmap/mindmap.png)

The SQA mind map illustrates the various aspects of Software Quality Assurance for **User Management** module that were considered during testing. It helps to ensure a comprehensive approach to quality assurance.

## Bug Report
We discovered and documented several bugs during our testing phase. Here is a summary:

| Bug ID | Description | Screenshot |
| ------ | ----------- | -------- |
| BUG-001 | Firstname and lastname field takes blank at first position | [Bug_1](/Screenshots/Screenshot_blank_at_first_position_of_Name_Field.png) |
| BUG-002 | Firstname and lastname field takes blank at last position | [Bug_2](/Screenshots/Screenshot_blank_at_last_position_of_Name_Field.png) | 
| BUG-003 | Firstname and lastname field takes special characters input | [Bug_3](/Screenshots/Screenshot_name_fields_with_special_characters.png) | 
| BUG-004 | Firstname and lastname field takes numbers input | [Bug_4](/Screenshots/Screenshot_firstname_and_lastname_with_numbers.png) |
| BUG-005 | Firstname and lastname field takes decimal numbers input | [Bug_5](/Screenshots/Screenshot_firstname_and_lastname_with_decimal_numbers.png) |
| BUG-006 | Firstname and lastname field takes alphanumeric characters input | [Bug_6](/Screenshots/Screenshot_name_fields_with_alphanumeric.png) |
| BUG-007 | Firstname and lastname field takes comma (,) in input field | [Bug_7](/Screenshots/Screenshot_name_fields_with_comma.png) |

For more details about each bug, please refer to the [complete Bug Report](RFL_Best_Buy.xlsx).

---

This Test Report provides an overview of our testing process, test cases, and the status of the User Management Module. Feel free to reach out for any questions or clarifications.

**You May Also See:** 
- [Test Report Of Academy LMS (WordPress Plugin)](https://github.com/AhmedManan/Manual_Test_RFL_BestBuy)
- [Shop API Test Report](https://github.com/AhmedManan/Shop_API_Test_Report)
- [JMeter Performance Test Report](https://github.com/AhmedManan/JMeter_Performance_Test_Report)
- [Automation Testing With Selenium For Digital AID Web Application (Ongoing Project)](https://github.com/AhmedManan/Digital_Aid_Selenium_Test)
- [Mobile Automation Testing With Appium (Upcoming Project)](https://github.com/AhmedManan/Appium_Mobile_Automation_Test)

**Read My Blogs:** [Manan's Blog](https://ahmedmanan.com/blog/)

[⬆️Back to Top](#rfl-best-buy-user-management-module-test-report)
