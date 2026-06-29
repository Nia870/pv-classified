# PVCLASSIFIED

> NSA-Sponsored Senior Design Project — Prairie View A&M University | "Sistas in Syntax" Team
> Fall 2025 – Spring 2026

## Overview

PVCLASSIFIED is a secure web application designed to verify that government documents comply with classification marking requirements before they are shared or stored. Similar to how a spell checker identifies grammar errors, PVCLASSIFIED detects missing or incorrect classification markings to help prevent the accidental disclosure of sensitive information.

The project was developed as part of an NSA-sponsored senior design program, with the final solution and project outcomes presented directly to NSA mentors.

## The Problem

Government agencies rely on accurate classification markings to protect sensitive information. Errors such as incorrect classification labels, missing banner lines, or incomplete portion markings can create significant security risks.

PVCLASSIFIED automates the validation process by checking documents for compliance before they are accepted into the system, reducing manual review and supporting secure document handling.

## Key Features

- Secure user authentication and role-based access control (RBAC)
- Document upload support for PDF, DOCX, TXT, and HTML files
- Validation of supported file types and upload requirements
- Metadata collection, including document title, classification level, banner line, portion markings, and contact information
- Automated validation of:
  - Required metadata fields
  - Classification banner consistency
  - Missing or incorrect portion markings
  - User security clearance authorization
- Principle of Least Privilege (PoLP) enforcement to prevent users from submitting documents above their assigned clearance level
- Results dashboard displaying validation status, detected issues, document ID, timestamps, and activity logs for auditing

## Example Workflow

A user uploads a document and selects **Secret** as the classification level. During validation, the system detects that the document banner is marked **Top Secret** and identifies a missing portion marking.

The application immediately reports both issues and prevents the document from moving forward until all validation errors are resolved:

```
❌ Banner does not match classification
❌ Portion marking missing
```

## My Contribution

As a member of the **three-person development team**, I was responsible for developing the application's front-end experience. My work included:

- Designing and implementing the document upload interface
- Building metadata entry forms for document submission
- Developing user-facing components for validation results and feedback
- Collaborating with teammates using Git and GitHub throughout the development process
- Participating in regular project presentations and demonstrations to faculty advisors and NSA mentors

## Technologies & Concepts

`HTML` `CSS` `JavaScript` `Web Application Security` `Role-Based Access Control (RBAC)` `Principle of Least Privilege (PoLP)` `Document Validation` `Git & GitHub` `Secure Software Development`

## Team

Developed by the "Sistas in Syntax" team as part of Prairie View A&M University's NSA-sponsored Senior Design program.

