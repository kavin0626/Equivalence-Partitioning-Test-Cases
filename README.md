                   https://1drv.ms/x/c/8E267B6AC18866C8/AUYUuc9cydRNoeeaOWR5oXk?e=9KeN9P
# Equivalence Partitioning Test Cases

## Description

This project contains **Equivalence Partitioning (EP) test cases** for different input validation requirements in software testing.

Equivalence Partitioning is a black-box testing technique used to divide input data into different groups called **equivalence classes**. Each class contains inputs that are expected to behave similarly.

## Exercises Covered

### Exercise 1 – Marks Input

**Requirement:** Students can enter marks from 0 to 100.

Partitions:

* Valid: 0–100
* Invalid: Less than 0
* Invalid: More than 100

### Exercise 2 – ATM Withdrawal

**Requirement:** The ATM allows customers to withdraw ₹500 to ₹20,000.

Partitions:

* Valid: ₹500–₹20,000
* Invalid: Less than ₹500
* Invalid: More than ₹20,000

### Exercise 3 – Username Validation

**Requirement:** Username must contain 5 to 15 characters.

Partitions:

* Valid: 5–15 characters
* Invalid: Less than 5 characters
* Invalid: More than 15 characters

### Exercise 4 – Mobile Number Validation

**Requirement:** Mobile number must contain exactly 10 digits.

Partitions:

* Valid: Exactly 10 digits
* Invalid: Less than 10 digits
* Invalid: More than 10 digits

### Exercise 5 – Shopping Cart Quantity

**Requirement:** Customer can purchase 1 to 10 items.

Partitions:

* Valid: 1–10 items
* Invalid: Less than 1 item
* Invalid: More than 10 items

### Exercise 6 – Bank Account Balance

**Requirement:** Minimum balance is ₹1,000 and maximum balance is ₹10,00,000.

Partitions:

* Valid: ₹1,000–₹10,00,000
* Invalid: Less than ₹1,000
* Invalid: More than ₹10,00,000

### Exercise 7 – Employee Salary

**Requirement:** Salary must be between ₹15,000 and ₹2,00,000.

Partitions:

* Valid: ₹15,000–₹2,00,000
* Invalid: Less than ₹15,000
* Invalid: More than ₹2,00,000

### Exercise 8 – Movie Ticket Booking

**Requirement:** Customer can book 1 to 6 tickets per transaction.

Partitions:

* Valid: 1–6 tickets
* Invalid: Less than 1 ticket
* Invalid: More than 6 tickets

## Testing Technique

**Technique Used:** Equivalence Partitioning

Each exercise contains:

* Valid equivalence class
* Invalid equivalence class below the allowed range
* Invalid equivalence class above the allowed range
* One suitable test value for each class

## Matrix Requirement

The application requirement also includes a square matrix as input. The system calculates eigenvalues and eigenvectors and determines whether the matrix is diagonalizable. If the matrix is diagonalizable, it displays matrices **P** and **D** such that:

`A = P D P⁻¹`

## Purpose

The purpose of these exercises is to understand how Equivalence Partitioning can reduce the number of test cases while still providing effective input validation coverage.
