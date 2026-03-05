## LibraX — Smart Library Management System

LibraX is a modern **Library Management System** built using **JavaScript and core Data Structures concepts inspired by C++**.

This project demonstrates how **Linked List and Queue** can be used in real-world applications like managing books and processing issue requests.

---

## Features

### Book Management

* Add new books
* Search books by ID
* Edit book details
* Delete books

### Dashboard

* Total books
* Available books
* Issued books
* Pending queue requests

### Book Issue System

* Students request books
* Requests stored using **Queue (FIFO)**
* Admin processes issue requests sequentially

### Return System

* Books can be returned using a confirmation modal
* Status updates automatically

### Sorting

Books can be sorted by:

* ID
* Title
* Author

---

## Data Structures Used

### Linked List

Books are stored using a **Linked List structure**.

Operations implemented:

* Insert Book
* Search Book
* Delete Book
* Traverse List

Time Complexity:

| Operation | Complexity |
| --------- | ---------- |
| Insert    | O(n)       |
| Search    | O(n)       |
| Delete    | O(n)       |
| Traverse  | O(n)       |

---

### Queue (FIFO)

Queue is used to handle **Book Issue Requests**.

Operations:

* enqueue()
* dequeue()
* peek()
* size()

Equivalent C++ concept:

```cpp
queue<Request> issueQueue;
```

---

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Data Structures & Algorithms

---

## Project Structure

```
LibraX
│
├── index.html
├── README.md
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/your-username/librax-library-system.git
```

Open the project folder and run:

```
index.html
```

No installation required.

---

## Learning Outcomes

This project demonstrates:

* Implementation of Linked List
* Queue (FIFO) structure
* CRUD operations
* Sorting logic
* DOM manipulation
* UI interaction with DSA logic

---

## Future Improvements

Possible upgrades:

* Database integration
* Authentication system
* Admin dashboard
* Book categories
* Borrow history

---

## Author

**Shivnarayan Dwivedi**
Computer Science Student

DSA Project demonstrating **Linked List and Queue concepts** in a Library System.

EOF

echo "README.md created successfully!"
