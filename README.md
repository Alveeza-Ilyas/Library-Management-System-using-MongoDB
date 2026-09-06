# 📚 Library Management System using MongoDB

A robust Library Management System designed to streamline library operations, manage book inventories, track member records, and handle borrowing/returning workflows using MongoDB.

<img width="1896" height="898" alt="image" src="https://github.com/user-attachments/assets/e7d523aa-a1e7-423b-8d36-ff7433da370c" />



## Features

* **Book Management:** Add, update, view, and remove books with details like title, author, category, ISBN, and availability.
* **Member Management:** Register new members, manage user profiles, and track active memberships.
* **Circulation Tracking:** Handle book checkouts, returns, issue dates, and due dates.
* **MongoDB Integration:** Flexible and scalable document-based data storage.
* **Search Functionality:** Quickly search books by title, author, or category.



## Tech Stack

* **Database:** MongoDB
* **Database Management:** MongoDB Compass
* **Version Control:** Git & GitHub



## Setup & Installation

1. **Clone the repository:**
```bash
git clone https://github.com/Alveeza-Ilyas/Library-Management-System-using-MongoDB.git




2. **Navigate to the project directory:**
```bash
cd Library-Management-System-using-MongoDB




3. **Database Configuration:**
* Ensure MongoDB is running locally or connect using a MongoDB Atlas connection string.





## Database Schema

* **`books`:** Stores book information (`title`, `author`, `isbn`, `category`, `copies`).
* **`members`:** Stores member details (`name`, `email`, `phone`, `join_date`).
* **`transactions`:** Tracks checkout history (`book_id`, `member_id`, `issue_date`, `due_date`, `status`).
