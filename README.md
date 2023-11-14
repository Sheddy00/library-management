# library-management
API that manages library.

# SPECIFICATIONS FOR THE LIBRARY SYSTEM
## 1. Introduction
`Objectif :` 

To develop a library API for managing books, authors, visitors, loans and returns, while ensuring the security of operations.

# `Functional requirements`

`Book and author management :`

Add a book with details such as title, author, year of publication, etc.
Add an author with details such as name, biography, etc.

`Visitor management :`

Integrate visitors with properties such as ID, name and reference.
Allow visitors to borrow and return books.

`Book status :`

Indicate whether a book is available or borrowed.
Provide a list of books borrowed and available.

`Visitor Activity History :`

Allow administrators to see which books have been borrowed and returned by a visitor.
Filter activities by period (month, week, hourly interval).

# `Non-functional requirements`

`Security :`

Implement OAuth 2.0 to manage authorisations.
Restrict access to borrowing and rendering actions to administrators.

`Performance :`

Ensure fast API response even with large numbers of users.

# `Constraints`

`Technological :`

Use technologies compatible with OAuth 2.0.
Ensure compatibility with industry standards.

`Timeframe :`

Delivery of the project within six months of the start date.

# `Usage scenarios`

`Borrowing scenario :`

A visitor asks to borrow a book.
The authenticated administrator borrows on the visitor's behalf.

`Viewing activities :`

An administrator wishes to view a visitor's activities over a given period.

# `Deliverables`

`Functional API :`

Endpoint for adding a book, an author and a visitor.
Endpoints for borrowing and returning books.
Endpoints for consulting the status of books and visitor activities.

# ` Approvals`

`Customers :`

The functionalities described comply with customer expectations.
System security is approved by the parties concerned.