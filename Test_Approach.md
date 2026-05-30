Scope : The scope of this assessment is to validate Gmail's Compose Email functionality for sending an email with:

Subject: Incubyte
Body: QA test for Incubyte

The testing covers:

Compose Email Window
Recipient Validation
Subject Field Validation
Email Body Validation
CC and BCC Functionality
Attachments
Draft Functionality
Email Sending Functionality
Error Handling
Positive and Negative Test Scenarios
Assumptions
User has a valid Gmail account.
User is able to successfully log in to Gmail.
Stable internet connection is available unless explicitly testing network-related scenarios.
Gmail application is accessible through a supported browser.
Recipient email addresses used during testing are valid and accessible.
Test Design Techniques Used
1. Boundary Value Analysis (BVA)

Used to verify system behavior at boundary conditions.

Examples:

Maximum subject length
Maximum email body length
Maximum attachment size supported by Gmail
2. Equivalence Partitioning (EP)

Used to divide input data into valid and invalid partitions.

Examples:

Valid Inputs:

Valid email address format
Valid attachment types

Invalid Inputs:

Invalid email address format
Unsupported attachment types
3. Negative Testing

Performed to ensure the application handles invalid inputs gracefully.

Examples:

Empty recipient field
Invalid email address
Sending email without internet connection
Attachment exceeding maximum allowed size
4. Exploratory Testing

Performed to identify unexpected issues beyond predefined test cases.

Areas explored:

UI behavior during rapid user actions
Multiple browser tabs
Refreshing browser during email composition
Simultaneous draft creation
Unexpected user inputs
Test Coverage Summary

The test cases cover:

Functional Testing
UI Testing
Validation Testing
Positive Testing
Negative Testing
Error Handling
Usability Testing
Deliverables

This repository contains:

Incubyte_Test_Cases_Excel.xlsx
Incubyte_BDD_Test_Cases.xlsx
README.md
Test_Approach.md
