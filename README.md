# Library-Management-System-SQL
SQL project on Library Management System including tables, relationships, sample data, and advanced queries.


# 📚 Library Management System – SQL Project

### 🔍 Overview
This project builds a complete **Library Management System database** using SQL. It represents real-world library operations, including books, borrowers, publishers, authors, branches, inventory, and book loans. Analytical SQL queries help understand how books are utilized across branches and how borrowers behave.

### 🏗 Database Structure (7 Tables)
| Table | Purpose |
|-------|---------|
| `tbl_publisher` | Stores publisher details |
| `tbl_book` | Stores book details with publisher info |
| `tbl_book_authors` | Stores authors for each book |
| `tbl_library_branch` | Stores library branch details |
| `tbl_book_copies` | Stores book inventory per branch |
| `tbl_borrower` | Stores borrower/member details |
| `tbl_book_loans` | Stores book loan/issue details |

📎 **Full SQL schema and queries are included in** `library_entry_full project.sql`.  
🔗 Contains all tables, constraints, sample data & analysis queries.

---

### 🎯 Project Objective
To understand how a library operates by building and analyzing a structured SQL database that manages books, branches, loans, and user activity. The goal is to convert raw data into insights that support decision-making in library management.

---

### 📌 Key Use Cases Solved (SQL Queries)
✔ Copies of a specific book at a given branch  
✔ Borrowers who have no issued books  
✔ Borrowers with more than 5 books issued  
✔ Branch-wise loan performance  
✔ Book availability & demand across branches  
✔ Author-based queries (e.g., Stephen King inventory)  
✔ Detailed loan summary for specific date and branch  

---

### 📊 Dataset Files Included
| File | Description |
|------|-------------|
| `authors.csv` | Author information |
| `books.csv` | Book details |
| `book copies.csv` | Copies available per branch |
| `book loans.csv` | Loan/issue records |
| `borrower.csv` | Library members |
| `publisher.csv` | Publisher information |
| `library branch.csv` | Branch-wise details (NEW data) 🏫 |

🆕 *`library branch.csv` was added to complete the database model.*

---

### 📎 Files in This Repository
| File | Type |
|------|------|
| `library_entry_full project.sql` | Full SQL schema + sample data + analytical queries |
| `SQL PROJECT PPT.pptx` | Project Presentation (ER model, schema explanation, insights) |
| `.csv` files | Raw datasets required to build the Library DB |

---

### 💡 Final Insights
- Book distribution varies by branches → **optimize inventory**
- Certain authors/titles are more popular → **increase copies**
- Few borrowers issue most books → **focused engagement strategy**
- Queries reveal patterns to **improve library services**

---

### 👩‍💻 Author
**M. Poojitha**  
📍 Telangana, India   
💡 Interested in SQL, Databases & Data Analysis  

---

### ⭐ If you like this project, give it a star!
