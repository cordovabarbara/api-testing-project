# API Testing with Postman

This repository contains **Postman collections** created to test the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/).  
The tests are organized into **Happy Path** (valid scenarios) and **Negative Cases** (error scenarios).

---

## 📂 Project Structure

api-testing-postman/
│── collections/
│ ├── happy-path-collection.json
│ ├── negative-cases-collection.json
│── README.md

- **happy-path-collection.json** → CRUD operations for `Users`, `Comments`, and `Photos`.
- **negative-cases-collection.json** → Invalid requests to verify error handling (e.g., 404 Not Found, 400 Bad Request).

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/api-testing-postman.git
   cd api-testing-postman
   ```
