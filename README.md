# 🔐 Cloud Security Project – SSH Misconfiguration Analysis (AWS)

## 📌 Project Overview
This project demonstrates a common cloud security misconfiguration where **SSH access is exposed to the internet** due to improper security group rules.  
The project focuses on **identification, analysis, logging, and mitigation** of the issue using **AWS cloud services**.

This project is developed as part of a **college major project** following ethical and defensive security practices.

---

## 🏢 Selected Scenario
- **Group:** 3  
- **Company Name:** AstraNode Corp  
- **Scenario:**  
  Misconfigured security group allows unrestricted SSH access from the internet.

---

## 🎯 Objectives
- To demonstrate how cloud misconfigurations create security risks
- To analyze unrestricted SSH access as an attack surface
- To enable logging and monitoring using AWS CloudTrail
- To apply mitigation using cloud security best practices
- To follow ethical guidelines (no real attack performed)

---

## ☁️ Cloud Platform Used
- **AWS (Amazon Web Services)**

---

## 🛠️ Services & Tools Used
- Amazon EC2
- Amazon VPC
- Security Groups
- AWS CloudTrail
- Ubuntu Linux
- Apache Web Server
- GitHub (documentation)

---

## 🏗️ Architecture Overview
- VPC with a public subnet
- EC2 instance deployed in public subnet
- Security group controlling SSH and HTTP access
- Apache web server hosted on EC2
- CloudTrail enabled for logging

---

## ⚠️ Misconfiguration / Attack Simulation
- SSH (Port 22) was intentionally allowed from `0.0.0.0/0`
- This represents a real-world scenario where attackers can attempt brute-force SSH attacks
- **No real attack was performed** to avoid ethical and legal issues

---

## 📊 Logging & Monitoring
- AWS CloudTrail enabled as a **multi-region trail**
- Logs all management events and configuration changes
- Used for detection and audit purposes

---

## 🛡️ Mitigation / Solution
- SSH access restricted to **administrator IP only**
- Public SSH access removed
- Followed principle of **least privilege**

---

## ✅ Result
- Vulnerability successfully identified and mitigated
- Cloud environment secured using best practices
- Logging enabled for future monitoring and auditing

---

## 🧠 Key Learnings
- Cloud misconfigurations are a major security risk
- Proper network access control is critical
- Logging and monitoring are essential for detection
- Ethical security practices must always be followed

---

## 🚫 Disclaimer
This project is strictly for **educational purposes only**.  
No real attacks were conducted. All scenarios were simulated through configuration analysis.

---

## 📚 References
- AWS Documentation: https://docs.aws.amazon.com
- Cloud Security Best Practices

---

## 👤 Author
Name: Bhavesh Verma  
Course:  Certified Ethical Hacking 
Semester:5th  

