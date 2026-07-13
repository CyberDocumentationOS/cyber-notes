# Week 7 Day 2 — Authentication & Authorization

---

# Warm-Up (Week 2 Review)

## Multiple Choice

### 1. Which permission allows a file to be read?

A) w

B) x

C) r

D) d

Answer: c

---

### 2. Which permission allows a file to be modified?

A) r

B) w

C) x

D) s

Answer: b

---

### 3. Which Linux command changes file permissions?

A) chown

B) chmod

C) sudo

D) groups

Answer: b

---

### 4. Which Linux command changes the owner of a file?

A) chmod

B) chown

C) pwd

D) ls

Answer: b

---

### 5. Which command displays the groups a user belongs to?

A) whoami

B) id

C) groups

D) ps

Answer: c

---

### 6. What does `sudo` allow a user to do?

A) Delete Linux

B) Run commands with elevated privileges

C) Create new hard drives

D) Change IP addresses

Answer: b

---

### 7. What is the Principle of Least Privilege?

A) Every user should be an administrator.

B) Users should only have the permissions necessary to perform their job.

C) Every file should be executable.

D) Every account should share one password.

Answer: b

---

### 8. What does file ownership determine?

A) The file size

B) Which user controls the file

C) The network connection

D) The file extension

Answer: b

---

### 9. What does `umask` control?

A) Network speed

B) Default permissions for newly created files and directories

C) CPU usage

D) Installed packages

Answer: b

---

### 10. Which permission string represents `chmod 644`?

A) rwxrwxrwx

B) rw-r--r--

C) rwxr-xr-x

D) rw-------

Answer: b

---

# Task 1 — Authentication

# Authentication Fundamentals

---

## Multiple Choice

### What is authentication?

A) Determining what a user can access

B) Verifying the identity of a user or device

C) Encrypting a password

D) Installing antivirus software

Answer: b

---

### What is identification?

A) Claiming an identity to a system

B) Giving permissions to a user

C) Encrypting files

D) Backing up data

Answer: a

---

### What are credentials?

A) Network cables

B) Information used to prove identity

C) Firewalls

D) User permissions

Answer: b

---

### Which of the following is a credential?

A) Password

B) Username

C) Smart card

D) All of the above

Answer: d

---

## Short Answer

### What is authentication?
Authentication is the process of verifying the identity of a user, device, or system before granting access to sensitive information. 
---

### What is identification?
Identification is the process to which a user, device, or entity declares their identity to a system. 
---

### What are credentials?
Credentials are pieces of information to identify the identity of a user, system, or service. 
---

### Why are passwords commonly used?
Passwords are commonly used because they are a simple, convenient, and effective way to verify a user's identity. 
---

## Fill In The Blanks

Authentication answers the question:
are you who you say you are?
---

Identification happens ________ authentication.
Answer: Before
---

A username is commonly used for:
Identification
---

A password is used to:
authenticate. 
---

## Multiple Choice

### Which comes first?

A) Authentication

B) Identification

Answer: b

---

### Which statement is true?

A) Authentication proves who you are.

B) Authentication decides what you can access.

Answer: a

---

## In Your Own Words

### Explain authentication to a beginner.
Authentication is the process of verifying the identity of a user, device, or system. 
---

### Explain identification to a beginner.
Identification is the process where a user, device, or entity declares their identity to a system. 
---

### Explain why credentials are important.
Credentials are important because they are an effective means of proving who you are to a system without compromising the security of the sensitive information in question. 
---

# Task 2 — Authorization

# Authorization & Access Control

---

## Multiple Choice

### What is authorization?

A) Verifying identity

B) Determining what an authenticated user is allowed to do

C) Encrypting passwords

D) Logging events

Answer: b

---

### Which security principle says users should receive only the permissions they need?

A) Defense in Depth

B) Least Privilege

C) Availability

D) Integrity

Answer: b

---

### What is access control?

A) Managing what resources users can access

B) Encrypting network traffic

C) Updating Windows

D) Installing Linux

Answer: a

---

## Short Answer

### What is authorization?
Authorization is the process of determining what actions, resources, or data a user, device, or application is permitted to access. 
---

### What is access control?
Access Control is a practice that restricts access to digital and physical resources to authorized users only. 
---

### Why is Least Privilege important?
Least Privilege is important because it minimizes risk by ensuring the users and systems only have the minimum access necessary in order to perform their tasks. 
---

### How are authentication and authorization different?
Authentication is the process of verifying an identity, while authorization is the process of determining what a user, device, or application is permitted to access. 
---

## Fill In The Blanks

Authentication verifies:
identity. 
---

Authorization determines:
permissions.
---

Least Privilege reduces:
risk. 
---

Permissions are a form of:
Authorization.
---

## Multiple Choice

### Which happens first?

A) Authorization

B) Authentication

Answer: b

---

### Which principle helps reduce damage if an account is compromised?

A) Availability

B) Least Privilege

C) Encryption

D) Compression

Answer: b

---

## In Your Own Words

### Explain authorization to a beginner.
Authorization is the process of determining what a user, device, or application has access to. 
---

### Explain Least Privilege to a beginner.
Least Privilege is a practice where users, devices, or applications have the minimum amount of access to perform their job/task.
---

### Explain why authentication alone is not enough.
Authentication alone is not enough because if an account gets compromised, then everything is at risk. It is important to have multiple layers of defense, as it reduces damage by a significant amount. 
---

# Task 3 — Authentication Methods

# Authentication Methods

---

## Multiple Choice

### Which authentication method is considered "something you know"?

A) Password

B) Fingerprint

C) Smart card

D) Security key

Answer: a

---

### Which authentication method is "something you are"?

A) Password

B) PIN

C) Biometric

D) Security key

Answer: c

---

### Which authentication method is "something you have"?

A) Password

B) Smart card

C) PIN

D) Security question

Answer: b

---

## Authentication Comparison

Fill in the table.

| Method | Strengths | Weaknesses | Common Uses |
|----------|-----------|------------|-------------|
| Password | Universality | Predictable and easy to crack | Online Accounts |
| PIN | Easy to remember and fast to use | Limited amount of combinations | Financial Transactions |
| Smart Card | Tamper Resistant | External hardware is required | Login to work computers |
| Biometrics | Hard to replicate | permanent and irreversible | device unlocking |
| Security Key | Strongest form of phishing resistance | Cost and Maintenance | Enterprise Security |

---

## Short Answer

### Which authentication method do you think is the strongest?
I would say the Security keys are the strongest due to the fact they require physical hardware to unlock, and are the most secure out of the all the methods. 
---

### Which authentication method is the weakest?
I would say Passwords are the weakest because they are far easier to crack than compared to the other methods, and many passwords can be predictable across multiple platforms. 
---

### Why are passwords still widely used?
Passwords are still widely used due to the convenience of it. It is the easiest and most cost efficient way to authenticate, and they aren't going away any time soon. 
---

### Why are security keys becoming more popular?
Security keys are becoming more popular because they offer the strongest phishing-resistant authentication available, making them the most secure out of all the methods. 
---

## Fill In The Blanks

Biometrics use a person's:
physical attribute.
---

Smart cards are an example of something you:
carry on you.
---

Passwords are something you:
know. 
---

Security keys help protect against:
phishing. 
---

## Reflection

### Which authentication method surprised you the most?
I would say the PIN method surprised me the most, as I didn't know it locally stored info on the device itself. 
---

### Which method do you personally trust the most?
The Security Key seems like the most trustworthy, as it requires it's own physical hardware, which is a lot harder to compromise than other methods. 
---

### Which method would you least like to rely on?
I would say I trust the Password method the least due to the fact that they are way easier to crack and compromise than other methods. 
---

## In Your Own Words

### Explain the difference between passwords, biometrics, smart cards, and security keys.
Passwords are pieces of information that you remember to access the subject at hand, biometrics is the process of using something like your face or finger print to access the subject, smart cards are cards that you use to access the subject, and security keys are keys that are used to acces the subject at hand.
Note: Security keys are physical cryptographic devices that prove your identity to a website or computer. (Graded) 
---

### Explain why organizations often use multiple authentication methods together.
Organizations use multiple authentication methods together to strengthen the security of the asset they have in question, making it difficult to compromise the asset. 
---
