# Day 02 - Prime Number

## 📌 Problem
Write a Python program to check whether a given number is a prime number.

A prime number is a number greater than 1 that has exactly two divisors:
1 and itself.

---

## 🧠 Concepts Used
- Conditional statements (if-else)
- For loop
- Modulus operator (%)
- Mathematical optimization (√n approach)

---

## 🚀 Optimized Approach (O√n)

Instead of checking up to n-1, we check up to √n.

Reason:
If a number has a factor greater than √n,
it must also have a smaller factor less than √n.

---

## ⏱ Time Complexity
O(√n)

---

## ✅ Example

Input: 7  
Output: Prime  

Input: 6  
Output: Not Prime