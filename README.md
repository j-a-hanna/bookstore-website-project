
# UML INFO 2480 — Bookstore Website Project

This repository contains coursework and the final project for the **University of Massachusetts Lowell INFO 2480 — Website Database Implementation** course.  
The project demonstrates a **dynamic online bookstore** built with **ColdFusion** and integrated with a **relational database** to manage book listings and user accounts.

---

## 📚 Project Overview

The Bookstore Website allows users to:
- Browse available books stored in a connected database  
- View detailed information about each book (title, author, ISBN, publisher, etc.)  
- Add, update, or delete book records (CRUD operations)  
- Create and manage user accounts  
- Log in and maintain session-based interactions  

The goal of this project was to understand and implement **web database integration** through server-side scripting using ColdFusion and SQL.

---

## 🗂️ Repository Structure

```text
uml_info_2480_061/
│
├── index.cfm              # Homepage displaying book listings
├── details.cfm            # Book detail view page
├── addBook.cfm            # (If applicable) Form to add new book entries
├── updateBook.cfm         # (If applicable) Modify existing records
├── deleteBook.cfm         # (If applicable) Delete book records
│
├── login.cfm              # Login page for users
├── loginForm.cfm          # Form handling login submissions
├── newAccount.cfm         # Page for creating new user accounts
├── sessionDump.cfm        # Used for testing and session tracking
│
├── header.cfm             # Common page header
├── footer.cfm             # Common page footer
├── horizontalNav.cfm      # Navigation bar component
├── genreNav.cfm           # Genre-based navigation component
│
├── styles.css             # CSS stylesheet for layout and design
│
├── bookstore.cfc          # ColdFusion component (CFC) managing backend logic
├── stateInfo.cfm / .cfc   # Data and helper files
│
├── /images/               # Folder containing static image assets
├── /MANAGEMENT/           # Administration tools or database management scripts
└── LICENSE                # MIT License file
```

⚙️ How to Run This Project

To run the Bookstore Website locally or on a ColdFusion server:

1. Install a ColdFusion Server

Use Adobe ColdFusion Developer Edition or Lucee (open-source alternative).

Configure your local web root (e.g., C:\ColdFusion2023\cfusion\wwwroot\ on Windows).

2. Clone the repository

  git clone https://github.com/j-a-hanna/uml_info_2480_061.git

Place the cloned folder inside your ColdFusion web root directory.

3. Set up the database

Import the SQL script (if provided) from the /MANAGEMENT/ or /database/ folder.

Name the database (e.g., bookstore_db).

Ensure the table includes fields such as id, title, author, isbn, publisher, and year.

4. Configure the data source

Open ColdFusion Administrator (http://localhost:8500/CFIDE/administrator/).

Create a new Data Source matching the database name used in your .cfm or .cfc files.

Test the connection to confirm it works.

5. Run the application

Start the ColdFusion server.

Visit the site at:

  http://localhost:8500/uml_info_2480_061/

The homepage (index.cfm) should display the list of books.

🧠 Learning Objectives

Build a complete data-driven website using ColdFusion and SQL.

Implement user authentication and session management.

Apply CRUD operations to real-world data models.

Integrate backend logic with frontend presentation layers.

💻 Technologies Used

ColdFusion (CFML)

SQL (Relational Database)

HTML5 / CSS3

Git / GitHub for version control

✍️ Author

Jeanette Attia Hanna
University of Massachusetts Lowell
INFO 2480 — Website Database Implementation







