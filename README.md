```
 https://1drv.ms/x/c/8E267B6AC18866C8/AUYUuc9cydRNoeeaOWR5oXk?e=QoU7UG
```# Equivalence Partitioning Testing Exercises

```
Name:Kavinraj.S
```
## About the Project

This project contains **Equivalence Partitioning (EP)** test cases for different application requirements.

Equivalence Partitioning is a software testing technique used to divide input data into different groups or **equivalence classes**. Each class contains inputs that are expected to behave in a similar way.

For each exercise, valid and invalid input partitions are identified and a suitable test value is provided.

## Exercises Included

### 1. Marks Input Validation

**Requirement:** Students can enter marks from 0 to 100.

Equivalence classes:

* Valid: 0–100
* Invalid: Less than 0
* Invalid: Greater than 100

### 2. ATM Withdrawal Validation

**Requirement:** Withdrawal amount must be between ₹500 and ₹20,000.

Equivalence classes:

* Valid: ₹500–₹20,000
* Invalid: Below ₹500
* Invalid: Above ₹20,000

### 3. Username Validation

**Requirement:** Username must contain 5 to 15 characters.

Equivalence classes:

* Valid: 5–15 characters
* Invalid: Less than 5 characters
* Invalid: More than 15 characters

### 4. Mobile Number Validation

**Requirement:** Mobile number must contain exactly 10 digits.

Equivalence classes:

* Valid: Exactly 10 digits
* Invalid: Less than 10 digits
* Invalid: More than 10 digits

### 5. Shopping Cart Quantity

**Requirement:** A customer can purchase 1 to 10 items.

Equivalence classes:

* Valid: 1–10 items
* Invalid: Less than 1 item
* Invalid: More than 10 items

### 6. Bank Account Balance

**Requirement:** Minimum balance is ₹1,000 and maximum allowed balance is ₹10,00,000.

Equivalence classes:

* Valid: ₹1,000–₹10,00,000
* Invalid: Below ₹1,000
* Invalid: Above ₹10,00,000

### 7. Employee Salary

**Requirement:** Salary must be between ₹15,000 and ₹2,00,000.

Equivalence classes:

* Valid: ₹15,000–₹2,00,000
* Invalid: Below ₹15,000
* Invalid: Above ₹2,00,000

### 8. Movie Ticket Booking

**Requirement:** A customer can book 1–6 tickets per transaction.

Equivalence classes:

* Valid: 1–6 tickets
* Invalid: Less than 1 ticket
* Invalid: More than 6 tickets

## Testing Technique

The following approach is used:

1. Identify the input requirement.
2. Divide the input range into valid and invalid classes.
3. Select one representative test value from each class.
4. Use the values to verify whether the application accepts or rejects the input correctly.

## Files Included

* `Equivalence_Partitioning_Test_Cases.xlsx` – Contains the EP test cases for all exercises.

## Objective

The objective of this project is to understand and apply **Equivalence Partitioning** in software testing and create effective test cases with minimum but meaningful test values.

## Conclusion

Equivalence Partitioning helps reduce the number of test cases while still providing good input coverage. It is useful for identifying valid and invalid input conditions during software testing.
