# Working-with-Generics
# Task 1

This project demonstrates how to use **Java Generics** to perform conditional checks on a collection of integers.

We define reusable "checker" classes (`CheckOdd`, `CheckPrime`, `CheckPalindrome`) that implement a common interface(`Check`), 
and then apply them with a generic counter (`CountElement`) to count and print numbers matching each condition.

---

## 📌 Features

1. **Odd Number Check**
    - Counts how many odd numbers are in a collection.
    - Prints all odd numbers.

2. **Prime Number Check**
    - Counts how many prime numbers are in a collection.
    - Prints all prime numbers.

3. **Palindrome Number Check**
    - Counts how many palindrome numbers are in a collection.
    - Prints all palindrome numbers.

---

## 📂 Project Structure
├── checkers/
│ ├── CheckOdd.java
│ ├── CheckPrime.java
│ ├── CheckPalindrome.java
│ └── Check.java # Common interface
├── CountElement.java # Generic counter utility
└── Main.java # Entry point