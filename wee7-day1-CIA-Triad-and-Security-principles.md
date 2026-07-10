# Week 7 Day 1 — CIA Triad & Security Principles

---

# Warm-Up (Week 1 Review)

## Multiple Choice

### 1. Which command displays your current working directory?

A) ls

B) pwd

C) cd

D) mkdir

Answer: b

---

### 2. Which command lists files and directories?

A) chmod

B) touch

C) ls

D) sudo

Answer: c

---

### 3. Which command changes your current directory?

A) pwd

B) mkdir

C) cd

D) cp

Answer: c

---

### 4. Which command creates a new directory?

A) touch

B) mkdir

C) ls

D) rm

Answer: b

---

### 5. Which command changes file permissions?

A) chmod

B) chown

C) sudo

D) whoami

Answer: a

---

### 6. Which directory typically stores user home folders?

A) /etc

B) /home

C) /bin

D) /var

Answer: b

---

### 7. Which command allows a user to execute commands with elevated privileges?

A) root

B) chmod

C) sudo

D) ps

Answer: c

---

### 8. Which Linux permission allows a file to be modified?

A) r

B) w

C) x

D) d

Answer: b

---

### 9. What is a process?

A) A network connection

B) A running instance of a program

C) A user account

D) A directory

Answer: b

---

### 10. Which command displays currently running processes?

A) pwd

B) mkdir

C) ps

D) cd

Answer: c

---

# Task 1 — CIA Triad

# CIA Triad

---

## Multiple Choice

### What does the "C" in CIA stand for?

A) Compliance

B) Confidentiality

C) Communication

D) Control

Answer: b

---

### What does the "I" in CIA stand for?

A) Integrity

B) Identification

C) Internet

D) Isolation

Answer: a

---

### What does the "A" in CIA stand for?

A) Access

B) Authentication

C) Availability

D) Authorization

Answer: c

---

## Short Answer

### What is Confidentiality?
Confidentiality is the idea of limiting information access and disclosure strictly to authorized users, ensuring data privacy and security. 
---

### What is Integrity?
Intergrity is the idea that data remains accurate, consistent, and trustworthy throughout its entire lifecycle, confirming it hasn't been altered by unauthorized factors. 
---

### What is Availability?
Availability is the idea that systems and data are accessible to authorized users when needed, even under extreme circumstances like hardware failure or cyberattacks. 
---

### Why is the CIA Triad important?
The CIA Triad is important because it provides a foundational framework for information security, guiding organizations to protect sensitive data, manage risk, and ensure regulatory compliance. It helps businesses safeguard against cyberattacks in the long run. 
Note: The CIA Triad doesn't directly prevent cyberattacks. Rather, it provides a framework for designing systems that are resilient against them. Your overall point is still correct. (Graded)
---

## Fill In The Blanks

Confidentiality helps prevent:
unauthorized access.
---

Integrity helps ensure that data remains:
accurate, consistent, and trustworthy.
---

Availability ensures systems and data remain:
accessible by authorized personnel when needed. 
---

The CIA Triad is one of the foundational models of:
information security.
---

## Multiple Choice

### Which part of the CIA Triad focuses on preventing unauthorized access?

A) Confidentiality

B) Integrity

C) Availability

Answer: a

---

### Which part of the CIA Triad focuses on ensuring information is accurate?

A) Confidentiality

B) Integrity

C) Availability

Answer: b

---

### Which part of the CIA Triad focuses on keeping systems operational?

A) Confidentiality

B) Integrity

C) Availability

Answer: c

---

## In Your Own Words

### Explain Confidentiality to a beginner.
Confidentiality is the idea of ensuring that only authorized personnel has access to the desired data. 
---

### Explain Integrity to a beginner.
Integrity is the idea of ensuring that data is accurate and trustworthy. 
---

### Explain Availability to a beginner.
Availability is the idea of ensuring data is accessible for authorized personnel, even during extreme circumstances. 
---

### Explain why the CIA Triad is important in cybersecurity.
The CIA Triad is important in cybersecurity because it is the foundation for information security, and provides a framework for businesses to follow to ensure they are safe from cyberattacks. 
---

# Task 2 — Security Concepts

# Security Fundamentals

---

## Multiple Choice

### What is an asset?

A) Something valuable that needs protection

B) A malware infection

C) A password

D) A firewall

Answer: a

---

### What is a threat?

A) Something that could cause harm

B) A backup

C) A software update

D) An operating system

Answer: a

---

### What is a vulnerability?

A) A weakness that can be exploited

B) A security policy

C) A network cable

D) An antivirus program

Answer: a

---

### What is risk?

A) The combination of threats exploiting vulnerabilities

B) A password

C) A firewall

D) A user account

Answer: a

---

## Short Answer

### What is an asset?
An asset is any data, device, system, or resource that holds value in an organization that requires protection to maintain business operations. 
---

### What is a threat?
A threat is any malicious activity, event, or circumstance that has the potential to compromise the confidentiality, integrity, or availability of an information system or its components.
---

### What is a vulnerability?
A vulnerability is a weakness or flaw in an organization's tech system that an attacker can exploit to gain unauthorized access, steal data, or disrupt operations. 
---

### What is risk?
A risk is the potential for loss, harm, or adverse impact on an organization resulting from the exploitation of vulnerabilities by cyber threats. 
---

## Fill In The Blanks

A weakness in a system is called a:
vulnerability.
---

Something valuable that needs protection is called an:
asset. 
---

Something capable of causing damage is called a:
threat.
---

Risk exists when a threat can exploit a:
vulnerability. 
---

## Examples

Give one example of each.

### Asset

Answer: Sensitive data. 

---

### Threat

Answer: Ransomware. 

---

### Vulnerability

Answer: Open port in the network. 
Note: An unnecessary open port is more of a vulnerability. (Graded)

---

### Risk

Answer: Finanical loss due to ransomware. (Graded)
---

## In Your Own Words

### Explain the difference between a threat and a vulnerability.
A vulnerability is a weakness in an organizations tech structure that can be exploited, while a threat is any malicious activity that is willing to exploit that vulnerability to compromise the organization's information system. 
---

### Explain why identifying assets is important.
Identifying an asset is important because having knowledge of said asset allows you to put extra measures in place to ensure the security of it, like only allowing certain people access to it and requiring multi factor authentication. 
---

### Explain how risk is created.
A risk is created when a vulnerability is exploited by a threat to cause harm. This could happen due to a lack of focus on the security of an information system, or the lack of care operating it. 
---

# Task 3 — CIA Classification Lab

# Applying the CIA Triad

For each example, identify which part of the CIA Triad is **MOST** important.

Write:

- Confidentiality
- Integrity
- Availability

---

## Example 1

Hospital patient records

Answer: Confidentiality

Why?
There are many laws in place that are meant to keep sensitive health information between Doctors and Patients confidential, so making sure only the right people have access to that information is crucial. 
---

## Example 2

Online banking transactions

Answer: Integrity

Why?
Due to the fact that money is involved, making sure the amount is correct and accurate is crucial in this instance, as financial institutions insist upon secure transactions. 
---

## Example 3

School grading system

Answer: Availability 
Note: Integrity matters a little more. (Graded)

Why?
When it comes to grades, people being able to see their academic performance easily takes more importance over other aspects of the triad. 
---

## Example 4

Cloud file storage service

Answer: Availability/Confidentiality

Why?
People using cloud services like expect them to be easily accessible whatever device they choose. It is also equally as important to ensure the privacy of the data they have, as unauthorized access should not happen. 
---

## Example 5

Military secrets

Answer: Confidentiality

Why?
Having military secrets compromised can cause drastic consequences for the military, as they are kept from everyone for a reason. 
---

## Example 6

Emergency 911 dispatch system

Answer: Integrity
Note: Avaliability is more important. (Graded)

Why?
911 is for emergencies, so having the data accurate and trustworthy is important to make sure things go smoothly. 
---

## Example 7

A company's payroll database

Answer: Integrity

Why? 
Making sure everyone's payroll is correct and secure can alieviate concerns in the future. 
---

## Example 8

Software update server

Answer: Integrity

Why?
Making sure people are able to easily update their software without having to worry about it being compromised is something that should be universal when it comes to software updates in general. 
---

## Reflection

### Which part of the CIA Triad seems the most important?
I would say all the parts are important, but confidentiality is the most important, as only people authorized to see the information should be able to see it. 
---

### Which part was easiest to understand?
I would say confidentiality was the easiest to understand, as it is pretty self explanatory.
---

### Which part was most confusing?
I would say knowing what part corresponded to what example, as it wasn't as cut and dry as I thought. 
---

### Which security concept (asset, threat, vulnerability, or risk) was easiest to understand?
I would say vulnerabilities was the easiest to understand, as it was pretty self explanatory. 
---

### Which concept was hardest to understand?
I would say the risk section was the hardest, as the resources I was learning it from made it sound a lot more complicated than it really is. 
---
