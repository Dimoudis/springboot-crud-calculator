# Spring Boot CRUD API

This project demonstrates a simple Spring Boot application with two main components:

## 1. NumbersController
- Provides a REST API to manage a list of numbers stored **in-memory**
- Endpoints:
  - `GET /numbers` → Returns the current list of numbers
  - `POST /numbers?value=X` → Adds a new number to the list
  - `DELETE /numbers/{index}` → Removes a number at the given index
  - `PUT /numbers/{index}?value=X` → Updates the number at the given index

## 2. CalculatorController
- Provides a REST API for basic calculator operations
- Endpoints
  - `GET /add?a=X&b=X` → Returns the sum of two numbers
  - `GET /multiply?a=X&b=X` → Returns the product of two numbers
  - `GET /square?a=X` → Returns the square of a number
