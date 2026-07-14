# Week 7 — Day 3
# Multi-Factor Authentication (MFA)

---

# Warm-Up (Week 3 Review)

## Multiple Choice

### 1. What is the primary purpose of an IP address?

A) Identify a user

B) Identify a device on a network

C) Encrypt data

D) Store files

Answer: b

---

### 2. Which networking device forwards traffic between different networks?

A) Switch

B) Router

C) Hub

D) Firewall

Answer: b

---

### 3. Which device forwards traffic based on MAC addresses?

A) Router

B) Switch

C) DNS Server

D) DHCP Server

Answer: b

---

### 4. What does DNS do?

A) Assigns IP addresses

B) Translates domain names into IP addresses

C) Encrypts network traffic

D) Scans networks

Answer: b

---

### 5. What is the primary purpose of DHCP?

A) Encrypt data

B) Automatically assign IP addresses

C) Translate website names

D) Block malicious traffic

Answer: b

---

### 6. Which protocol is connection-oriented?

A) UDP

B) TCP

C) ICMP

D) ARP

Answer: b

---

### 7. Which protocol is connectionless?

A) TCP

B) UDP

C) HTTPS

D) SSH

Answer: b

---

### 8. What is the primary purpose of NAT?

A) Encrypt network traffic

B) Translate private IP addresses to public IP addresses

C) Resolve domain names

D) Assign MAC addresses

Answer: b

---

### 9. Which subnet mask is commonly used on home networks?

A) 255.0.0.0

B) 255.255.0.0

C) 255.255.255.0

D) 255.255.255.255

Answer: c

---

### 10. Which port is commonly used by HTTPS?

A) 22

B) 53

C) 80

D) 443

Answer: d

---

# Task 1 — Multi-Factor Authentication (MFA)

# Multi-Factor Authentication

---

## Multiple Choice

### What does MFA stand for?

A) Multiple File Access

B) Multi-Factor Authentication

C) Managed Firewall Access

D) Multi-File Authentication

Answer: b

---

### Which statement best describes MFA?

A) Using one strong password

B) Using two or more different authentication factors

C) Encrypting a password twice

D) Logging in with two usernames

Answer: b

---

### Why is MFA more secure than a password alone?

A) It makes passwords longer.

B) It requires additional proof of identity.

C) It changes your IP address.

D) It hides your username.

Answer: b

---

### Which of the following is an authentication factor?

A) Username

B) Password

C) Security Key

D) Both B and C

Answer: d

---

## Short Answer

### What is Multi-Factor Authentication (MFA)?
Multi-Factor Authentication is a method that verifies a user's identity by requiring two or more types of authentication. 
---

### Why is MFA important?
MFA is important to use because it significantly reduces the risk of unauthorized access, as hackers would not be able to steal an account with only one stolen credential. 
---

### Why isn't a password alone enough?
A password alone isn't strong enough due to how easily it can be cracked and compromised. Having another layer of authentication reduces the likelihood of an account being fully compromised. 
---

### How does MFA help prevent unauthorized access?
MFA helps prevent unauthorized access due to the multiple methods of authentication used. Many times, hackers just have access to a password, but having to go through multiple layers to compromise an account is generally much more difficult and time consuming to do, and they usually don't bother with that account in particular anymore. 
---

## Fill In The Blanks

MFA requires at least ______ different authentication factors.
two
---

Passwords are considered something you ______.
know.
---

A fingerprint is something you ______.
are.
---

A security key is something you ______.
have.
---

MFA greatly reduces the risk of ______.
unauthorized access.
---

## Multiple Choice

### Which of the following is NOT a valid authentication factor?

A) Something you know

B) Something you have

C) Something you are

D) Something you download

Answer: d

---

### Which authentication method is considered phishing-resistant?

A) SMS Codes

B) Passwords

C) Security Keys

D) Email Verification

Answer: c

---

# In Your Own Words

### Explain MFA to a beginner.
Multi-factor authentication (MFA) is a cybersecurity method where two or more authentication methods are used to verify a user's identity. 
---

### Explain why organizations require MFA.
Organizations require MFA because they have assets that the general public shouldn't have access to, and require multiple authentication methods to ensure only authorized personnel has access to it.
---

### Explain why adding another authentication factor improves security.
Adding another authentication factor improves security because it layers the authentication process and makes it more difficult for hackers to get into the account, reducing the risk of it happening. 
---

# Task 2 — Authentication Factors

# Authentication Factors

---

## Multiple Choice

### Which category does a password belong to?

A) Something you know

B) Something you have

C) Something you are

Answer: a

---

### Which category does a fingerprint belong to?

A) Something you know

B) Something you have

C) Something you are

Answer: c

---

### Which category does a USB security key belong to?

A) Something you know

B) Something you have

C) Something you are

Answer: b

---

## Classification Table

Complete the table.

| Authentication Method | Authentication Factor | Strengths | Weaknesses |
|-----------------------|----------------------|-----------|------------|
| Password | Something you know | Universality/Easy to remember | Easy to compromise |
| Phone | Something you have | No special hardware required | Vulnerable to SIM card attacks |
| Fingerprint | Something you are | Hard to replicate | Permanent and Irreplaceable |
| Face ID | Something you are | Difficult to spoof | Permanent and Irreplaceable |
| USB Security Key | Something you have | Strongest form of phishing resistance | Cost and maintenance |
| Authenticator App | Something you have | Offline accessibility | Device dependency |

---

## Short Answer

### Which authentication method do you think is the strongest?
Security Keys are the strongest form of authentication because of the use of external hardware, which makes it extremely difficult to compromise.
---

### Which authentication method do you think is the weakest?
Passwords are the weakest form of authentication because they can be compromised fairly easily. 
---

### Why are authenticator apps generally more secure than SMS codes?
Authenticator apps are generally more secure than SMS because they run through and external app that generates codes locally on the device to authenticate rather than SMS. A phone number is easier to compromise than an authenticator app. 
---

### Why are security keys considered phishing-resistant?
Security keys are considered phishing-resistant due to the fact they use public-key cryptography and origin binding, which ensures security even if it is input into a phishing site. It is much more difficult to compromise than something like a password. 
---

## Fill In The Blanks

Passwords are something you ______.
know.
---

Biometrics are something you ______.
are.
---

Security keys are something you ______.
have.
---

Authenticator apps generate ______ codes.
one-time
---

## In Your Own Words

### Explain the three authentication factors.
Passwords: Input a piece of information to prove identity. 
    Note: Something you know (password or PIN) (Graded)
Biometrics: Use something like your face or fingerprint to prove your identity. 
Security Keys: A physical USB stick/Key used to prove your identity. 
---

### Explain why different authentication methods have different strengths.
All authentication methods have strengths and weaknesses of their own, and this is because there is no one definitive authentication to use all the time. This is why MFA is a thing, to make up for those weaknesses and take advantage of those strengths. 
---

# Task 3 — MFA Case Studies

# MFA Scenarios

---

## Multiple Choice

### Which scenario uses two different authentication factors?

A) Password + PIN

B) Password + Fingerprint

C) Fingerprint + Face ID

D) Password + Security Question

Answer: b

---

### Which authentication combination is generally the strongest?

A) Password + SMS

B) Password + Authenticator App

C) Password + Security Key

D) Password + Password Hint

Answer: c

---

## Case Study 1

A company requires:

- Password
- SMS Code
- Fingerprint

### How many authentication factors are being used?
Three authentication factors are being used. 
---

### Which authentication factors are present?
Password
SMS
Fingerprint
---

### Which method is the weakest?
Passwords are the weakest due to the fact that they can be compromised easier than others. 
---

## Case Study 2

A bank requires:

- Password
- Authenticator App

### How many authentication factors are being used?
Two authentication factors are being used. 
---

### Is this MFA?

A) Yes

B) No

Answer: a

---

### Why?
MFA require at least two different types of authentication factors, which this has. 
---

## Case Study 3

A school requires:

- Password
- Security Question

### Is this Multi-Factor Authentication?

A) Yes

B) No

Answer: b

---

### Why or why not?
Passwords and Security Questions are both the same type of authentication question and do not meet the requirement for MFA. 
---

## Case Study 4

A company requires:

- Security Key
- Fingerprint

### How many authentication factors are present?
Two factors are present. 
---

### Which factor is "something you have"?
Security Key fills the something you have portion. 
---

### Which factor is "something you are"?
Fingerprint fills the something you are portion.
---

## Reflection

### Which authentication method would you use to protect your own important accounts?
If available, I would use the Face ID + authenticator app method as it is the most secure, cost effective, and reasonable method out there.
---

### Which authentication method do you trust the least?
I would say just Password I wouldn't trust, as it is the easiest to compromise out of all the factors present. 
---

### What surprised you most about MFA?
I was surprised that Password + Security Question didn't count as MFA, as it was something didn't think about in detail before hand. 
---

# In Your Own Words

### Explain why using two passwords is NOT Multi-Factor Authentication.
Using two passwords doesn't count as MFA due to the fact that they are the same authentication factor. Something like Password + Authentication app would be MFA because they are two different types of authentication factors, hence the name "Multi-Factor Authentication". 
---

### Explain why security professionals strongly recommend enabling MFA whenever possible.
Security professionals strongly recommend enabling MFA whenever possible because having just one layer of authentication is not that secure, and having multiple layers will make it more difficult for your account to be compromised. 
---