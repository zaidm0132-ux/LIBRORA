# Functional Requirements

## 1. Introduction
This document describes the functional requirements of LIBRORA, a digital library management system that allows students to explore books, request borrowing services, and manage their accounts. Administrators can manage books, students, and borrowing requests.

## 2. User Authentication

- **FR-01:** The system shall allow students to create accounts using their name, email, and password.
- **FR-02:** The system shall validate registration information and prevent duplicate email addresses.
- **FR-03:** The system shall allow registered students to log in and log out.
- **FR-04:** The system shall allow administrators to log in using authorized credentials.
- **FR-05:** The system shall identify users according to their roles (Student or Admin).

## 3. Book Management and Browsing

- **FR-06:** The system shall display the available book catalog.
- **FR-07:** The system shall allow students to search for books by title or author.
- **FR-08:** The system shall allow students to filter books by category.
- **FR-09:** The system shall display detailed information for each book.
- **FR-10:** The system shall display the availability status of each book.
- **FR-11:** Administrators shall be able to add, edit, and delete books.

## 4. Borrowing Management

- **FR-12:** The system shall allow logged-in students to submit borrowing requests for available books.
- **FR-13:** The system shall prevent duplicate active borrowing requests for the same book by the same student.
- **FR-14:** Administrators shall be able to view all borrowing requests.
- **FR-15:** Administrators shall be able to approve or reject pending borrowing requests.
- **FR-16:** The system shall update book availability when a borrowing request is approved.
- **FR-17:** Administrators shall be able to confirm book returns.
- **FR-18:** The system shall update the book status to Available after a return is confirmed.
- **FR-19:** Students shall be able to view their borrowing history and request statuses.

## 5. User Profile Management

- **FR-20:** Students shall be able to view their profile information.
- **FR-21:** Students shall be able to update their full name and phone number.
- **FR-22:** Administrators shall be able to view and search registered student information.

## 6. Notifications

- **FR-23:** The system shall notify administrators when a student submits a borrowing request.
- **FR-24:** The system shall notify students when their borrowing requests are approved or rejected.
- **FR-25:** The system shall notify students when a book return is confirmed.
- **FR-26:** Users shall be able to view notifications and mark them as read.

## 7. Reports and Contact

- **FR-27:** The system shall display library statistics, including total, available, and borrowed books.
- **FR-28:** The system shall display borrowing request statistics.
- **FR-29:** The system shall display book statistics grouped by category.
- **FR-30:** The system shall provide a contact form for users to submit inquiries.
