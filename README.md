# **OWASP Juice Shop - Security Challenges Repository**

## **Disclaimer**

This repository is created for **educational purposes only**. The techniques and challenges presented here are meant to help developers and security professionals understand and mitigate common security vulnerabilities. Unauthorized use of these techniques against systems you do not own or have explicit permission to test is **strictly prohibited**.

---

## **Table of Contents**

1. [Introduction](#1-introduction)
2. [Project Structure](#2-project-structure)
3. [Challenges](#3-challenges)
   - [CAPTCHA Bypass](./challenges/captcha-bypass/README.md)
   - [Client-side XSS Protection](./challenges/client-side-xss-protection/README.md)
   - [Deluxe Fraud](./challenges/deluxe-fraud/README.md)
4. [About OWASP Juice Shop](#4-about-owasp-juice-shop)

---

## **1. Introduction**

This repository serves as a structured guide to understanding and exploiting common security vulnerabilities using the **OWASP Juice Shop**. Each challenge focuses on a different security issue, demonstrating how attackers could exploit weaknesses and, more importantly, how developers can prevent such vulnerabilities.

The main goal of this repository is to help learners:

- Gain **hands-on experience** with security flaws.
- Understand **how attackers think**.
- Learn **mitigation techniques** to secure applications.

Each challenge is documented with a **step-by-step guide**, explaining the attack process and the corresponding **countermeasures**.

---

## **2. Project Structure**

Each challenge is stored in the `challenges/` directory with its own `README.md` containing:

- **Challenge Description**
- **Procedure & Steps**
- **Solution & Explanation**
- **Countermeasures**

---

## **3. Challenges**

### **[CAPTCHA Bypass](./challenges/CAPTCHA_Bypass/README.md)**

- **Category:** Broken Anti-Automation
- **Objective:** Submit multiple customer feedback entries within a short time frame, bypassing CAPTCHA validation.
- **Key Learning:** How attackers exploit weak anti-bot measures and how to properly implement CAPTCHA validation.

### **[Client-side XSS Protection](./challenges/Client-side-XSS-Protection/README.md)**

- **Category:** Cross-Site Scripting (XSS)
- **Objective:** Perform a stored XSS attack by bypassing client-side validation.
- **Key Learning:** Why client-side validation alone is insufficient and how to implement secure input validation.

### **[Deluxe Fraud](./challenges/Deluxe_Fraud/README.md)**

- **Category:** Improper Input Validation
- **Objective:** Obtain a deluxe membership without making a payment.
- **Key Learning:** The dangers of weak server-side validation and how to prevent business logic vulnerabilities.

---

## **4. About OWASP Juice Shop**

[OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) is an intentionally vulnerable web application designed for security testing and training. It covers a wide range of **OWASP Top 10** vulnerabilities and provides a **real-world simulation** of common security issues.

Juice Shop is widely used for:

- **CTF Competitions**
- **Security Awareness Training**
- **Penetration Testing Practice**
- **Developer Security Education**

By interacting with Juice Shop, learners get practical exposure to web security flaws in a **safe, controlled environment**.
 
