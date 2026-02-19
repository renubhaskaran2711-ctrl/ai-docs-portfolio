# API Fundamentals

This document explains core API concepts.

---

## What is an API?

An API (Application Programming Interface) allows two systems to communicate.

Example:
A frontend app sends a request → The server responds with data.

---

## REST Basics

REST APIs use HTTP methods to perform actions.

| Method | Purpose |
|--------|----------|
| GET    | Retrieve data |
| POST   | Create data |
| PUT    | Update data |
| DELETE | Remove data |

---

## HTTP Status Codes

| Code | Meaning |
|------|----------|
| 200  | Success |
| 201  | Created |
| 400  | Bad Request |
| 401  | Unauthorized |
| 404  | Not Found |
| 500  | Server Error |
| 400  | Server test  |

---

## JSON Structure

Most APIs use JSON format.

Example:

```json
{
  "user_id": 123,
  "status": "active"
}
```
