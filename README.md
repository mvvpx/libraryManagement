##### University Library Management Application #######

I developed a Python-based application to automate the management of the university library. This application handles two types of users: students and administrators.

**Administrator Features:**
- Manage the book inventory
- Manage student accounts
- Handle book borrowings
- View the list of students who exceed the borrowing duration
- Create and suspend user accounts

**Student Features:**
- Reserve books

**User Information:**
Each user is characterized by an ID, first name, last name, email address, login, and password.

**Book Information:**
Books are characterized by an ID, title, author, publisher, ISBN, number of copies, and publication year.

**Management Rules:**
- A student can borrow a book for a maximum duration of 7 days.
- Each student is limited to borrowing a maximum of 3 books at a time.
- The administrator can monitor students who do not comply with the 7-day borrowing limit.
- The administrator can manage book borrowings and user accounts.

**Technical Constraints:**
- Desktop application developed using Python.
