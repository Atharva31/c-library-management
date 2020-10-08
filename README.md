# Library Management

#### Documentation:
    * https://gitlab.com/Atharva31/c-library-management

## This Software can be used by three types of user
    * Owner
    * Librarian
    * User

### Owner
     * Owner owns library.
     * He is interested into tracking assets and revenue.

### Librarian
     * Owner appoints a librarian for library management.
     * He handles all tasks including data entry, book issue, Payment Collection etc.

### Member
     * Members (reader) can find books and check availability.

## Important points to note.
    * This is console based menu driven application. Based on user login appropriate menu will be visible.
    * Each book can have multiple copies and organized into multiple racks.
    * Issue/return of individual copy is expected. For example, if “C Programming Language (by Ritchie)” have 10 copies, each copy can be issued and returned independently.
    * Book can be issued if and only if user is paid user. Otherwise error message will be displayed. Payment of each user will be collected by Librarian on monthly basis.
    * Book is expected to return in 7 days. If delayed, fine of Rs. is applicable and should be taken by Librarian while returning book.

## Technologies & tools
    * Programming language: C
    * Database: File IO
    * IDE: Eclipse or VIM or any other IDE