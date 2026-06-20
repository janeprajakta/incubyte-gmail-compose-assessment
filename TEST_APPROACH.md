# Test Approach: Gmail Compose Functionality

## Introduction
This document defines the test approach for verifying Gmail Compose functionality. The primary objective is to validate that Gmail allows composing and sending an email with the required subject and body content.

## Scope
The scope covers functional validation of Gmail Compose for creating and sending an email. It focuses on the compose workflow, content entry, send operation, and verification in the sent folder.

## In Scope
- Opening the Gmail compose window.
- Entering the subject: `Incubyte`.
- Entering the body: `QA test for Incubyte`.
- Sending the email successfully.
- Verifying the email appears in Sent Items.
- Confirming the email subject and body content are correct.

## Out of Scope
- Gmail account creation and authentication flows.
- Email delivery verification on the recipient side.
- Attachments, formatting, or advanced mail options.
- Browser compatibility beyond the primary test environment.
- Performance, security, and accessibility testing.

## Assumptions
- A valid Gmail account is available for testing.
- The test environment has access to Gmail via a supported browser.
- The tester has permissions to send email from the account.
- The Gmail interface is in its standard, supported configuration.

## Test Design Techniques Used
- Equivalent Class Partitioning: Validate content entry for the required subject and body fields.
- Positive Functional Testing: Confirm the expected workflow succeeds with valid inputs.
- Exploratory Testing: Observe the compose experience and note any usability issues.

## Risks
- Changes in the Gmail UI may affect test steps or element identification.
- Network or service disruptions may prevent email send operations.
- Account restrictions, such as rate limits or security blocks, may prevent sending.
- Incorrect test environment configuration may produce false failures.

## Entry Criteria
- Gmail account credentials are available.
- Test environment and browser are prepared.
- The test case and supporting documentation are ready.
- Access to the Gmail Compose interface is confirmed.

## Exit Criteria
- The email was successfully sent with subject `Incubyte` and body `QA test for Incubyte`.
- The sent email is visible in Sent Items.
- Any defects found during testing are logged.
- The primary compose workflow has been executed and validated.
