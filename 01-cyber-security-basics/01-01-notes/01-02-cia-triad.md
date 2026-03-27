# 🔐 CIA Triad

## 🧠 What is the Goal of Cybersecurity?

Cybersecurity is not just about stopping attacks.

Its main goal is to ensure that systems and data are:

- Protected
- Reliable
- Accessible when needed

This is achieved through three core objectives known as the **CIA Triad**:

- Confidentiality
- Integrity
- Availability

---

## 🧩 What is the CIA Triad?

The CIA Triad is a foundational model used to guide security decisions and system design.

Each part focuses on a different aspect of protection.

---

## 🔒 1. Confidentiality

### 🎯 Goal:
Ensure that information is only accessible to authorized users.

---

### 🧪 Example (New)

A company stores employee salary data in an internal system.

Only HR staff can view this data, while other employees cannot access it.

👉 If unauthorized employees access it → confidentiality is broken

---

### 🛡️ How to Achieve:
- Access control (who can see what)
- Encryption
- Authentication systems

---

## 🧾 2. Integrity

### 🎯 Goal:
Ensure that data remains accurate and unchanged unless properly authorized.

---

### 🧪 Example (New)

A student submits an online exam.

If someone alters the submitted answers in the database, the results become incorrect.

👉 This is a violation of integrity

---

### 🛡️ How to Achieve:
- Data validation
- Hashing
- Permission control (who can edit data)

---

## ⏱️ 3. Availability

### 🎯 Goal:
Ensure that systems and data are accessible when needed.

---

### 🧪 Example (New)

An online learning platform crashes during an exam period.

Students cannot access their tests.

👉 This is a failure of availability

---

### 🛡️ How to Achieve:
- Backup systems
- Load balancing
- System monitoring

---

## ⚖️ Important Insight

These three objectives are connected.

👉 Improving one can sometimes affect the others.

Example:
- Very strict access control (confidentiality) may reduce usability (availability)

---

## 🏢 Real-World Priority Differences

Different organizations prioritize different objectives:

- Government agencies → focus on confidentiality  
- Financial systems → focus on integrity  
- Online services → focus on availability  

---

## 🎯 Key Takeaway

A secure system must balance all three:

- 🔒 Confidentiality → protect access  
- 🧾 Integrity → protect correctness  
- ⏱️ Availability → ensure access  

---

## 🧠 My Insight

In real-world systems, failures often occur when one of these three is ignored.

For example, a system may be highly available but insecure, or highly secure but unusable.

Designing systems requires balancing all three objectives based on context.
