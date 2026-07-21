# Week 7 Day 5 — Hashing & Password Security

# Warm-Up (Week 6 Review)

## Multiple Choice

### 1. What is a hypervisor?

A) A password manager

B) Software that creates and manages virtual machines

C) A Linux command

D) A network protocol

Answer: b

---

### 2. What is the Host OS?

A) The operating system running inside a VM

B) The operating system installed on the physical computer

C) A hypervisor

D) A network device

Answer: b

---

### 3. What is the Guest OS?

A) The operating system running inside a virtual machine

B) The operating system installed on physical hardware

C) A BIOS setting

D) A networking protocol

Answer: a

---

### 4. Which networking mode hides a VM behind the host's connection?

A) Bridged

B) Host-Only

C) NAT

D) Public

Answer: c

---

### 5. Which networking mode allows a VM to appear as its own device on the local network?

A) NAT

B) Bridged

C) Host-Only

D) Snapshot

Answer: b

---

### 6. Which networking mode isolates the VM from the internet while allowing communication with the host?

A) NAT

B) Bridged

C) Host-Only

D) Public

Answer: c

---

### 7. What is a VM snapshot?

A) A screenshot

B) A backup of Windows

C) A saved state of a virtual machine

D) A networking configuration

Answer: c

---

### 8. Why are snapshots useful?

A) They increase RAM

B) They allow quick recovery to a previous VM state

C) They improve internet speed

D) They replace antivirus software

Answer: b

---

### 9. Which Type 2 hypervisor have you been using?

A) VMware ESXi

B) Hyper-V Server

C) VirtualBox

D) KVM

Answer: c

---

### 10. What is Kali Linux primarily designed for?

A) Office work

B) Video editing

C) Cybersecurity and penetration testing

D) Gaming

Answer: c

---

# Task 1 — Hashing

# Hashing Fundamentals

---

## Multiple Choice

### What is hashing?

A) Encrypting data

B) Converting data into a fixed-length output

C) Compressing data

D) Backing up data

Answer: b

---

### Which of the following is a hashing algorithm?

A) AES

B) RSA

C) SHA-256

D) TLS

Answer: c

---

### Which hashing algorithm is considered weak and outdated?

A) SHA-256

B) SHA-512

C) MD5

D) bcrypt

Answer: c

---

### What is salting?

A) Encrypting data twice

B) Adding random data before hashing

C) Compressing a password

D) Backing up a database

Answer: b

---

## Short Answer

### What is hashing?
Hashing is a one-way mathematical process in cybersecurity that transforms input data into a fixed-length string of characters.
---

### What is a hash function?
A hash function is what performs the hashing transformation.
---

### What is MD5?
MD5 is a hash function that generates a 128-bit hash value from input data.
---

### What is SHA-256?
SHA-256 is a cryptographic hash function that belongs to the SHA-2 family and developed by the NSA. It is a one way hashing function that converts input data into a fixed length 256-bit hash. 
---

### What is salting?
Salting is a cryptographic security technique used to protect stored passwords by adding a random string of data (which is called the salt) to each password before it is hashed. 
---

### Why can't hashes normally be reversed?
Hashes can't be reversed because they are designed as one way functions that map unlimited input data to a fixed-size output, inherently discarding information. 
---

## Fill In The Blanks

Hashing converts input data into a fixed-length __________.
string of characters
---

Hashing is generally considered a __________ process.
one-way
---

MD5 is considered __________ for modern password storage.
Outdated
---

SHA-256 is part of the __________ family.
SHA-2
---

Salting adds __________ data before hashing.
Unique random
---

## In Your Own Words

### Explain hashing to a beginner.
Hashing is a one-way process of transforming input data into a fixed length output of characters.
---

### Explain why hashes cannot normally be reversed.
Hashes are meant to be one-way outputs, and are not designed to be reversed back to normal, as they disregard information. 
---

### Explain why salting improves security.
Salting improves security by adding a random string onto every password, ensuring that even identical passwords produce different hash values.
---

# Task 2 — Password Storage

# Password Security

---

## Multiple Choice

### Why do websites hash passwords?

A) To save storage space

B) To protect passwords if the database is stolen

C) To increase internet speed

D) To improve graphics

Answer: b

---

### What is a rainbow table?

A) A password database

B) A precomputed list of hashes used to crack passwords

C) An encryption algorithm

D) A firewall

Answer: b

---

### What is the purpose of a salt?

A) Speed up logins

B) Prevent identical passwords from having identical hashes

C) Encrypt passwords

D) Replace hashing

Answer: b

---

### What should a website store?

A) Plaintext passwords

B) Encrypted passwords

C) Hashed passwords

D) Screenshots of passwords

Answer: c

---

## Short Answer

### Why don't websites store passwords in plaintext?
Websites don't store passwords in plaintext because it creates a major security vulnerability, as if a data breach were to incure, every user's credentials would be exposed. 
---

### What is a password database?
A password database is a secure repository used by websites and applications to store user authentication credentials such as passwords (hashed with salt of course).
---

### What is a rainbow table?
A rainbow table is a large, precomputed database of plaintext passwords and their corresponding hash values, used to reverse engineer hashed passwords into readable text.
Note: Rainbow tables don't reverse hashes, they use precomputed hash data to find a likely password that produces a matching hash. (Graded)
---

### Why are salts important?
Salts are important because they ensure that identical passwords don't have the same hash value. This is done by adding a unique random string of character to the beginning of it in order to separate the values. 
---

### What is password cracking?
Password cracking is the process of using automated tools and algorithms to recover or dechiper passwords that have been hashed or encrypted, allowing unauthorized access.
---

## Fill In The Blanks

Passwords should be stored as __________.
salted hashes
---

A stolen password database should ideally contain only __________.
salted hash values
---

Rainbow tables are used to attack weak __________.
unsalted password hashes
---

Salts help defend against __________ table attacks.
rainbow
---

Strong password storage helps protect user __________.
credentials
---

## In Your Own Words

### Explain why websites hash passwords.
Websites hash passwords in order to keep the credentials of users private and secure. 
---

### Explain what a rainbow table is.
A rainbow table is a large database of passwords and their hash values and are generally used to reverse engineer hashed passwords into readable text. 
---

### Explain why salting is important.
Salting is important because it prevents two identical passwords from having the same hash value by adding a unique random string of characters to the beginning of it.
---

# Task 3 — Weekly Reflection & Assignment

# Security Fundamentals Review

---

## Multiple Choice

### 1. Which part of the CIA Triad focuses on preventing unauthorized access?

A) Integrity

B) Availability

C) Confidentiality

D) Authorization

Answer: c

---

### 2. Authentication answers which question?

A) What can you access?

B) Who are you?

C) What network are you on?

D) What operating system are you using?

Answer: b

---

### 3. Authorization determines:

A) Identity

B) Permissions

C) Encryption

D) Logging

Answer: b

---

### 4. MFA requires:

A) One authentication factor

B) Two or more authentication factors

C) Two passwords

D) Encryption

Answer: b

---

### 5. Which is an example of "something you are"?

A) Password

B) PIN

C) Fingerprint

D) Security Key

Answer: c

---

### 6. Which encryption type uses two keys?

A) Symmetric

B) Asymmetric

Answer: b

---

### 7. Which protocol secures web traffic?

A) HTTP

B) FTP

C) HTTPS

D) DNS

Answer: c

---

### 8. What do digital certificates primarily verify?

A) Passwords

B) Website identity

C) Network speed

D) File permissions

Answer: b

---

### 9. Which security principle says users should only have the permissions they need?

A) Availability

B) Encryption

C) Least Privilege

D) MFA

Answer: c

---

### 10. What is hashing primarily used for?

A) Reversible encryption

B) Secure password storage and integrity verification

C) Network routing

D) Compression

Answer: b

---

# Weekly Reflection

## Confidence Level (1–10)

Security Fundamentals:

5 / 10

---

## Which topic felt easiest this week?

A) CIA Triad

B) Authentication

C) Authorization

D) MFA

E) Encryption

F) HTTPS

G) Hashing

Answer: a

---

## Which topic felt hardest this week?

A) CIA Triad

B) Authentication

C) Authorization

D) MFA

E) Encryption

F) HTTPS

G) Hashing

Answer: g

---

## What was the biggest thing you learned this week?
I learned the basics and nuances of encryption and hashing, which is something that is going to be very important later on. 
---

## Which topic do you want to learn more about?
I would like to learn more about encryption and hashing, as I have a feeling I am going to be using those concepts often.
---

# In Your Own Words

### Explain the difference between hashing and encryption.
Encryption is converting readable data into unreadable data, while hashing is converting data into a fixed length output. And while Encrypted data can be decrypted, hashed data has to be reversed engineered to become readable again. 
Note: Encrypted data can be decrypted with the appropriate key, while hashed data cannot normally be reversed. An attacker can instead guess possible inputs and compare their hashes to the target hash. (Graded)
---

### Explain why password hashing is important.
Password hashing is important because it keeps a user's credentials private and secure, making sure hackers can't easily obtain them.
---

### Explain why cybersecurity professionals care about password storage.
Cybersecurity professionals care about password storage because protecting confidentiality is important, and if a database has weak security and isn't hashed, than it could lead to a massive data breach that can cost tons of money and put people's security at risk.
---