# API Test Technical Assessment

## 📌 Overview
This project contains automated API tests developed using Postman as part of a technical assessment.

The test suite validates authentication, business rules, and data integrity of the API.

---

## 🛠 Tools Used
- Postman
- JavaScript (Postman Tests)
- Newman (optional CLI execution)

---

## ✅ Test Coverage

- Status code validation
- Response body validation
- Schema validation
- Dynamic data handling
- Token management
- Environment variable usage

---

## ▶ How to Run

### Option 1 – Using Postman
1. Import the collection
2. Import the environment
3. Select the environment
4. Run using Collection Runner

### Option 2 – Using Newman (CLI)

Install Newman:

Run:
newman run postman/API_Tests_Collection.json -e postman/environment.example.json

## 🧪 Example Validations Implemented

- UUID format validation
- Array length validation
- Field type validation
- Conditional token storage