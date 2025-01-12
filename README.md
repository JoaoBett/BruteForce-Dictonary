# Brute-force and Dictionary Attacks

## Overview

Brute-force and dictionary attacks are among the most common methods used by malicious actors to compromise digital systems. These attacks exploit weaknesses in password security, targeting accounts, systems, or encrypted data by systematically guessing passwords until access is granted. This document provides insights into how these attacks work and suggests mitigation strategies to enhance security.

---

## What is a Brute-force Attack?

A brute-force attack involves trying every possible combination of characters until the correct password is found. 

### Characteristics

- **Exhaustive Search**: Attempts all possible combinations.
- **Time Complexity**: Depends on password length and character set.

---

## What is a Dictionary Attack?

A dictionary attack uses a precompiled list of potential passwords, often compiled from common passwords or leaked credentials. It relies on users choosing weak or predictable passwords.

### Characteristics

- **Word Lists**: Based on common passwords or patterns.
- **Efficiency**: Faster than brute-force as it reduces the number of guesses.

---

## Mitigation Strategies

### Strengthening Passwords

1. **Complex Passwords**: Encourage the use of long and complex passwords with a mix of characters.
2. **Avoid Predictable Choices**: Avoid dictionary words, birthdays, or commonly used phrases.

### System Security Measures

1. **Rate Limiting**: Limit the number of login attempts to prevent automated attacks.
2. **Account Lockout**: Temporarily lock accounts after multiple failed attempts.
3. **Multi-Factor Authentication (MFA)**: Add an additional layer of security beyond the password.

### Advanced Techniques

1. **Password Hashing**: Use strong and salted cryptographic hashing algorithms.
2. **CAPTCHA**: Implement CAPTCHA challenges to block automated scripts.

---

## Conclusion

Brute-force and dictionary attacks pose significant threats to digital security. By understanding their mechanisms and implementing robust security measures, individuals and organizations can mitigate these risks effectively. Adopting strong password policies, enforcing MFA, and leveraging modern security tools are essential steps in combating these attack vectors.
