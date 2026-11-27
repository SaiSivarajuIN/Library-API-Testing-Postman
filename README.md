# Library API Testing – Postman

## 📌 Project Overview

This project demonstrates API testing using **Postman** for a Library Management API.

It covers the basic CRUD operations for managing books, including adding, retrieving, and deleting books.

The project uses Postman collection variables, environment variables, pre-request scripts, and automated test scripts to validate API responses.

## 🛠️ Tools & Technologies

- Postman
- REST API
- JavaScript (Postman Scripts)
- JSON
- Git & GitHub

## 📂 Project Structure

```text
Library-API-Testing/
│
├── Postman/
│   ├── LibraryAPI.postman_collection.json
│   └── LibraryEnvironment.postman_environment.json
│
├── README.md
└── .gitignore
```

## 🚀 API Operations

### 1. Add Book
- Method: POST
- Endpoint: `/Library/Addbook.php`
- Generates a random ISBN.
- Uses dynamic variables for book name, author, and ISBN.
- Validates response status, headers, response time, and book ID.

### 2. Get Book
- Method: GET
- Endpoint: `/Library/GetBook.php?ID={{bookID}}`
- Retrieves book details using the Book ID.
- Validates book information and JSON schema.

### 3. Delete Book
- Method: POST
- Endpoint: `/Library/DeleteBook.php`
- Deletes a book using its Book ID.
- Validates the response and JSON schema.

## ⚙️ Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/SaiSivarajuIN/Library-API-Testing.git
   ```

2. Open Postman.

3. Import the following files:
   - `LibraryAPI.postman_collection.json`
   - `LibraryEnvironment.postman_environment.json`

4. Select the imported **Library Environment**.

5. Configure the `companyCode` collection variable with your desired prefix.

6. Verify the `base_url` environment variable.

7. Run the collection using Postman Collection Runner.

## 🧪 Testing Features

- Dynamic test data generation.
- Pre-request scripts.
- Environment and collection variables.
- HTTP status code validation.
- Response header validation.
- Response time validation.
- JSON schema validation.
- Book ID logic validation.
- Automated cleanup using Delete Book.

## 🎯 Learning Outcomes

- Understanding REST API testing.
- Creating and executing Postman collections.
- Writing JavaScript-based automated test scripts.
- Working with dynamic variables.
- Validating API responses.
- Managing API testing projects using GitHub.

## 👨‍💻 Author

**Sai**

GitHub: https://github.com/SaiSivarajuIN

---

⭐ If you find this project useful, feel free to star the repository!
