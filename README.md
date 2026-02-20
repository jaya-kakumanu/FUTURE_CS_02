# 🔐 Phishing Email Detection System

A simple Java-based phishing email detection program that analyzes suspicious emails and identifies common phishing indicators such as fake domains, insecure links, urgency tactics, and generic greetings.

---

## 📌 Project Overview

Phishing attacks are one of the most common cyber threats used to steal sensitive information like banking credentials, passwords, and OTPs.

This project demonstrates a basic phishing detection mechanism using Java by analyzing:

- Sender email domain
- Suspicious HTTP links
- Urgency keywords
- Generic greetings

The system classifies the email as:

✅ Safe  
❌ Phishing (High Risk)

---

## 🎯 Objective

- Detect phishing indicators in suspicious emails
- Classify email risk level
- Demonstrate cybersecurity awareness
- Provide a simple educational phishing detection model

---

## 🛠 Technologies Used

- Java
- String Processing
- Conditional Logic
- Basic Risk Scoring

---

## 🔍 Features

✔ Detects fake sender domains  
✔ Identifies insecure HTTP links  
✔ Checks urgency-based keywords  
✔ Detects generic greetings  
✔ Provides final risk classification  

---

## 📂 Project Structure

Phishing-Email-Detection/
│
├── PhishingDetector.java
└── README.md

---

## ▶ How to Run

1. Install Java (JDK 8 or above)
2. Compile the program:

   javac PhishingDetector.java

3. Run the program:

   java PhishingDetector

---

## ⚠ Sample Output

⚠ Fake sender domain detected.  
⚠ Insecure HTTP link detected.  
⚠ Urgency tactic detected.  
⚠ Generic greeting detected.  

❌ Classification: PHISHING EMAIL (High Risk)

---

## 🛡 Security Awareness

This project highlights the importance of:

- Verifying sender domains
- Avoiding suspicious links
- Checking HTTPS before entering credentials
- Not sharing OTP or passwords
- Enabling Two-Factor Authentication (2FA)

---

## 📊 Conclusion

This project demonstrates a simple phishing detection logic using Java. While basic, it helps understand how phishing emails can be identified through domain inspection and content analysis.

---

