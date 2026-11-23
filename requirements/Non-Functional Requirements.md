# Non-Functional Requirements

## 1. Introduction
This document describes the non-functional requirements of LIBRORA, focusing on the quality attributes and constraints that define how the system should operate.

## 2. Usability

- **NFR-01:** The system shall provide a simple and user-friendly interface.
- **NFR-02:** The system shall provide clear navigation between its pages.
- **NFR-03:** The system shall display clear success and error messages.
- **NFR-04:** The system shall maintain a consistent design across all pages.

## 3. Performance

- **NFR-05:** The system should load pages within a reasonable time under normal conditions.
- **NFR-06:** The system should process user actions and requests efficiently.
- **NFR-07:** The system should handle multiple users without significant performance degradation.

## 4. Security

- **NFR-08:** The system shall restrict administrative features to authorized administrators.
- **NFR-09:** The system shall protect user account information from unauthorized access.
- **NFR-10:** The system shall validate user inputs before processing them.
- **NFR-11:** User passwords shall be securely hashed when stored in the database.

## 5. Reliability and Availability

- **NFR-12:** The system shall maintain accurate book availability information.
- **NFR-13:** The system shall prevent invalid borrowing status transitions.
- **NFR-14:** The system should remain available during normal operating conditions.
- **NFR-15:** The system should handle unexpected errors without crashing.

## 6. Maintainability

- **NFR-16:** The system shall use a modular structure to simplify maintenance.
- **NFR-17:** The system shall use clear and consistent naming conventions.
- **NFR-18:** The system shall separate frontend, backend, and database responsibilities.

## 7. Compatibility

- **NFR-19:** The system shall support modern web browsers such as Google Chrome, Microsoft Edge, and Firefox.
- **NFR-20:** The system shall provide a responsive interface for desktop, tablet, and mobile devices.

## 8. Scalability

- **NFR-21:** The system should support future additions of library features.
- **NFR-22:** The system should allow the database and application to grow as the number of users and books increases.
