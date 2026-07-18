# Week 7 — Day 4
# Encryption Basics

---

# Warm-Up (Week 4 Review)

## Multiple Choice

### 1. Which Windows folder contains most operating system files?

A) C:\Users

B) C:\Windows

C) C:\Downloads

D) C:\Program Files

Answer: b

---

### 2. Which account type should be used for everyday activities?

A) Administrator

B) Standard User

Answer: b

---

### 3. Which Windows utility is used to manage background services?

A) Event Viewer

B) Services (services.msc)

C) Registry Editor

D) Task Scheduler

Answer: b

---

### 4. Which Registry hive stores settings for the currently logged-in user?

A) HKLM

B) HKCU

C) HKCR

D) HKU

Answer: b

---

### 5. Which Registry hive stores system-wide settings?

A) HKLM

B) HKCU

C) HKCR

D) HKU

Answer: a

---

### 6. Which Windows tool records system and application logs?

A) Task Manager

B) Registry Editor

C) Event Viewer

D) Services

Answer: c

---

### 7. Which component loads Windows after UEFI/BIOS?

A) Windows Explorer

B) Windows Boot Manager

C) Task Manager

D) Winlogon

Answer: b

---

### 8. Which Windows utility lets you monitor running programs and resource usage?

A) Services

B) Event Viewer

C) Task Manager

D) Device Manager

Answer: c

---

### 9. Which Windows log is generally most useful when troubleshooting application crashes?

A) Security

B) Application

C) System

D) Setup

Answer: b

---

### 10. Which principle recommends giving users only the permissions necessary to perform their job?

A) Availability

B) Confidentiality

C) Least Privilege

D) Encryption

Answer: c

---

# Task 1 — Encryption

# Encryption Fundamentals

---

## Multiple Choice

### What is encryption?

A) Compressing data

B) Converting readable data into unreadable data

C) Deleting data

D) Creating backups

Answer: b

---

### What is plaintext?

A) Encrypted information

B) Readable information before encryption

C) A password

D) A network packet

Answer: b

---

### What is ciphertext?

A) Readable information

B) Encrypted unreadable information

C) A file extension

D) A password manager

Answer: b

---

### What is decryption?

A) Destroying encrypted data

B) Restoring encrypted data back into readable form

C) Compressing files

D) Scanning for malware

Answer: b

---

## Short Answer

### What is encryption?
Encryption is the process of converting readable data into an unreadable scrambled format using algorithms and secret cryptographic keys. 
---

### What is plaintext?
Plaintext is unencrypted, readable data that is accessible and understandable without the need for specialized tools. 
---

### What is ciphertext?
Ciphertext is the unreadable, scrambled output produced by an encryption algorithm. 
---

### What is decryption?
Decryption is the process of converting encrypted data (ciphertext) back into a readable form (plaintext).
---

### Why is encryption useful?
Encryption is useful because it ensures an extra level of security for sensitive data, as even if it is stolen, the data remains secure. 
---

## Fill In The Blanks

Encryption converts __________ into ciphertext.
Plaintext
---

Decryption converts __________ back into plaintext.
Ciphertext
---

Ciphertext is designed to be __________ without the proper key.
unreadable
---

Encryption helps protect data from __________ access.
Unauthorized
---

## Multiple Choice

### Which of the following is the main goal of encryption?

A) Increase CPU speed

B) Protect confidentiality

C) Improve internet speed

D) Compress files

Answer: b

---

### Which part of the CIA Triad is encryption primarily used to protect?

A) Integrity

B) Availability

C) Confidentiality

Answer: c

---

# In Your Own Words

### Explain encryption to a beginner.
Encryption is the process of turning readable data into unreadable data. 
---

### Explain the difference between plaintext and ciphertext.
Plaintext is readable data without the need for special tools, while ciphertext is encrypted unreadable data that requires special tools to read. 
---

### Explain why encryption is important in cybersecurity.
Encryption is important in cybersecurity because it allows you to confidential data confidential easily, as even if it is stolen, the data remains secure.
Note: Encryption protects sensitive information by ensuring only authorized users with the correct decryption key can read it. (Graded)
---

# Task 2 — Symmetric vs Asymmetric Encryption

# Encryption Types

---

## Multiple Choice

### Which encryption type uses the same key for encryption and decryption?

A) Symmetric

B) Asymmetric

Answer: a

---

### Which encryption type uses two different keys?

A) Symmetric

B) Asymmetric

Answer: b

---

### Which encryption type is generally faster?

A) Symmetric

B) Asymmetric

Answer: a

---

### Which encryption type uses a public key?

A) Symmetric

B) Asymmetric

Answer: b

---

## Short Answer

### What is symmetric encryption?
Symmetric encryption is a cryptographic method that uses a single shared secret key for both encrypting and decrypting.
---

### What is asymmetric encryption?
Asymmetric encryption is a cryptographic method that uses a mathematically linked pair of keys, a public key for encryption, and a private key for decryption.
---

### What is a public key?
A public key is a large numerical value/cyrptographic code used to encrypt data, and is freely shared for anyone to use. 
---

### What is a private key?
A private key is a large numerical value/cryptographic code used to encrypt and decrypt data, and is kept from the general public. 
Note: A private key is a secret cryptographic key that is kept by its owner and is used to decrypt data encrypted with the matching public key or create digital signatures. (Graded)
---

### Why are both encryption methods important?
Both encryption methods are important because they offer strengths that complement each other. Symmetric encryption is used for speed and efficiency, while asymmetric encryption provide security and authentication. When combined, the two methods provide comprehensive data protection. 
---

## Fill In The Blanks

Symmetric encryption uses ______ key(s).
single shared secret key
---

Asymmetric encryption uses ______ key(s).
seperate public and private
---

The public key can be shared with ______.
anyone
---

The private key should remain ______.
secure/private
---

## Comparison Table

| Feature | Symmetric | Asymmetric |
|----------|-----------|------------|
| Number of Keys | 1 | 2 |
| Speed | Faster | Slower |
| Best Used For | Speed and Efficiency | Security and Authentication |
| Example Algorithm | Advanced Encryption Standard (AES) | Rivest-Shamir-Adleman (RSA) |

---

## Multiple Choice

### Which encryption type is commonly used for encrypting large amounts of data?

A) Symmetric

B) Asymmetric

Answer: a

---

### Which encryption type is commonly used during secure key exchange?

A) Symmetric

B) Asymmetric

Answer: b

---

# In Your Own Words

### Explain the difference between symmetric and asymmetric encryption.
Symmetric encryption is known for it's speed and efficiency along with it only having a single, secret key, while asymmetric encryption is known for it's security and authentication, along with the fact that it uses a separate public key and private key, with two in total.
---

### Explain why symmetric encryption is faster.
Symmetric encryption is faster than asymmetric encryption due to the fact that it uses simpler mathematical operations, which can be done much faster. 
---

### Explain why asymmetric encryption is still necessary.
Asymmetric encryption is still necessary because it solves the problem of secure key distribution over untrusted networks, which symmetric encryption cannot do independently. 
---

# Task 3 — HTTPS

# HTTPS & TLS

---

## Multiple Choice

### What does HTTPS stand for?

A) HyperText Transfer Protocol Secure

B) Hyper Transfer Text Protection Service

C) HyperText Terminal Protection System

D) High Transfer Protocol Security

Answer: a

---

### Which protocol provides encryption for HTTPS?

A) FTP

B) SSH

C) TLS

D) DNS

Answer: c

---

### What do digital certificates primarily do?

A) Increase internet speed

B) Verify a website's identity

C) Store passwords

D) Encrypt hard drives

Answer: b

---

## Short Answer

### What is HTTPS?
HTTPS (Hypertext Transfer Protocol Secure) is a protocol that is used to send data between a web browser and a website securely. 
Note: HTTPS is HTTP running over TLS, providing encryption, authentication, and integrity. (Graded)
---

### What is TLS?
TLS (Transport Layer Security) is a protocol that is used in HTTPS to encrypt communications between two parties using asymmetric encryption. 
Note: TLS uses both asymmetric and symmetric encryption. (Graded)
---

### What is a digital certificate?
A digital certificate is a public key certificate/identity certificate that is used to identify a user, device, server, or website. 
---

### Why is HTTPS considered secure?
HTTPS is considered secure due to the fact that it combines encryption, data integrity, and authentication to protect communication between a web browser and a server.
---

### What role does encryption play in HTTPS?
Encryption is the core mechanic of HTTPS, as TLS scrambles the data sent between the web browser and server, making it secure. 
Note: TLS provides confidentiality and integrity, while certificates provide authentication. (Graded)
---

## Fill In The Blanks

HTTPS uses the ______ protocol.
TLS
---

TLS encrypts data while it is ______.
transmitted
---

A certificate helps verify a website's ______.
Identity
---

Without HTTPS, attackers may be able to ______ transmitted data.
compromise
---

## Scenario Questions

### Scenario 1

You connect to your online bank.

Should HTTPS be used?

A) Yes

B) No

Answer: a

Why?
A bank has many details about your financials and personal life, which is something you don't want hackers getting a hold of. 
---

### Scenario 2

You log into your university account over public Wi-Fi.

Why is HTTPS especially important?

Answer:
HTTPS is especially important in this circumstance because it encrypts the data transmitted between your device and the university's server, preventing hackers from obtaining your credentials. 
---

### Scenario 3

What risks exist if a website only uses HTTP instead of HTTPS?

Answer:
The communications between the web browser and server aren't encrypted, which means the information in those communications can be compromised. 
---

# In Your Own Words

### Explain HTTPS to someone who has never heard of it.
HTTPS is a protocol that is used to send data between a web browser and server securely.
---

### Explain the role of TLS.
The role of TLS is to encrypt the communications between a web browser and a server using noth symmetric and asymmetric encryption to ensure it cannot be compromised. 
---

### Explain why websites should always use HTTPS when handling passwords or payment information.
Websites should always use HTTPS when handling private information like passwords or payment information because hackers are always trying to steal that kind of information, so encrypting the communications between the web browser and server in those situations is crucial. 
---