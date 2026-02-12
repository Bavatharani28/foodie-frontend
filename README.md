# Foodie Frontend

This repository contains the frontend interface of the **Foodie Web Application** developed using HTML.  
It is integrated with a Spring Boot REST API backend and PostgreSQL database.

The application allows users to add food items through a clean and user-friendly interface.

---

## Project Description

Foodie is a full-stack web application built to manage food items.  
This repository contains only the frontend part of the application, which provides a form to add food details such as name, price, quantity, and add-ons.

The frontend communicates with the backend API to store data in the PostgreSQL database.

---

## Features

- Add new food items
- Submit food name, price, quantity, and add-ons
- Basic form validation using required fields
- Clean card-based UI design
- Direct integration with Spring Boot backend API

---

## Tech Stack

- HTML
- CSS (Internal Styling)
- Spring Boot (Backend – Separate Repository)
- PostgreSQL (Database)

---

## Project Structure

foodie-frontend
 foodie-frontend/index.html
 foodie-frontend/README.md


---

## API Integration

The form sends data to the following backend endpoint:

POST http://localhost:8080/food


Make sure the Spring Boot backend is running before submitting the form.

Backend should contain:

```java
@PostMapping("/food")
```
How to Run the Project

Clone or download this repository.

Ensure the Spring Boot backend is running on:
http://localhost:8080
Open index.html in your browser.
Fill in the form and click Add Food.
Data will be stored in the PostgreSQL database through the backend API.

---
Developed By
Bavatharani
Full Stack Developer | Web Development Learner
